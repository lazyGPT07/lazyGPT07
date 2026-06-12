# QA Bug Report Sample

## API alias ignores supported client filters

**Severity:** Medium  
**Area:** REST API compatibility  
**Method:** Focused manual and regression testing

### Summary

The `/api/v1/videos` compatibility route delegates to the canonical video-list handler, but it does not translate query parameters still used by existing clients. Requests containing `limit`, `q`, or `tag` therefore return an unfiltered result set.

### Environment

- Local Flask test client
- Seeded database containing three videos with distinct titles and tags
- Compatibility route under review: `GET /api/v1/videos`
- Canonical search route used as a control: `GET /api/v1/search`

### Reproduction

1. Seed three videos.
2. Request `GET /api/v1/videos?limit=1`.
3. Request `GET /api/v1/videos?q=Needle` where only one title contains `Needle`.
4. Request `GET /api/v1/videos?tag=debate` where only one video has that tag.
5. Compare with `GET /api/v1/search?q=Needle&per_page=5`.

### Expected

| Request | Expected result |
| --- | --- |
| `?limit=1` | One video |
| `?q=Needle` | Only matching videos |
| `?tag=debate` | Only videos carrying the tag |
| Canonical search | Same matching semantics |

### Actual

Each compatibility-route request returned all three seeded videos. The canonical search route returned the single matching video.

### Impact

Clients appear to receive successful HTTP responses, but pagination and filtering silently fail. This can create oversized payloads and incorrect content selection without producing an obvious error.

### Likely Cause

The delegated handler reads canonical parameters such as `page`, `per_page`, `sort`, and `agent`, while existing callers send `limit`, `q`, and `tag`.

### Suggested Acceptance Criteria

- Translate `limit` to the canonical page-size parameter or update all callers.
- Preserve text-search and tag-filter behavior.
- Add seeded tests that assert returned IDs or titles, not only HTTP status codes.
- Confirm canonical and compatibility routes produce equivalent result sets for equivalent requests.

### Public Evidence

The original review and discussion are public:

- [Pull request review](https://github.com/Scottcjn/bottube/pull/1404#pullrequestreview-4487135407)
- [Inline finding](https://github.com/Scottcjn/bottube/pull/1404#discussion_r3404588519)