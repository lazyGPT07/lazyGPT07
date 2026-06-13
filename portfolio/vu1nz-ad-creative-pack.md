# vu1nz Starter Ad Creative Pack

## 1. Campaign Summary

vu1nz helps engineering teams find risky CI/CD workflow patterns and suspicious
package changes before they merge. The product installs as a GitHub App, scans
pull requests automatically, and posts findings as GitHub Check Runs.

Primary offer:

- Scan any public GitHub repository free, with no signup.
- Install the GitHub App for a 14-day organization trial with no card required.
- Add CI/CD and package supply-chain coverage alongside Dependabot, CodeQL,
  Snyk, and Semgrep.

Primary CTA: **Scan your public GitHub repo free.**

Secondary CTA: **Start a 14-day free trial.**

## 2. Target Audience

- Security engineers responsible for application and software supply-chain risk.
- Platform and DevOps engineers maintaining GitHub Actions across many repos.
- Engineering leaders who want useful PR checks without another per-seat tool.
- Technical founders who need practical security coverage with little setup.
- Open-source maintainers handling dependency and workflow changes from outside
  contributors.

Key pains:

- GitHub Actions referenced by mutable tags instead of commit SHAs.
- Secrets exposed through unsafe workflow triggers or shell interpolation.
- New packages with malicious install scripts, typosquatted names, or little
  publisher history.
- Security findings arriving after merge rather than inside the PR workflow.
- Per-repository configuration drift and security tools priced per developer.

## 3. Messaging Pillars

### The overlooked attack surface

Application code is only one path to production. Workflow files and dependency
changes often run with privileged credentials but receive less review.

### Useful in seconds

The public scanner accepts a GitHub repository and returns CI/CD findings
without signup. The GitHub App adds automatic scanning on every PR.

### Complements the existing stack

Dependabot is useful for known dependency vulnerabilities. CodeQL is useful for
application code. vu1nz adds checks designed for CI/CD workflow and package-diff
risks.

### Low-friction rollout

Install one GitHub App, select repositories, and receive Check Runs in pull
requests. No card is required for the 14-day trial.

### Auditable by developers

vu1nz is MIT-licensed and presents findings with file, line, CWE, and a
recommended remediation.

## 4. Meta Ads

### Primary Text 1: The breach may be in YAML

Your application code may not be where the next breach starts. A mutable
GitHub Action, unsafe PR trigger, or malicious package update can run inside a
trusted pipeline. vu1nz checks CI/CD workflows and package changes on every PR,
then posts findings directly in GitHub. Scan a public repo free.

### Primary Text 2: A missing layer

Keep Dependabot. Keep CodeQL. Add the layer that checks workflow YAML and newly
introduced packages. vu1nz runs deterministic CI/CD checks, reviews package
changes across six ecosystems, and reports results before merge.

### Primary Text 3: Thirty-second rollout

Protect the repositories your team ships from without maintaining another
workflow file. Install the vu1nz GitHub App once, select your repos, and get
automatic PR Check Runs. Start with a 14-day trial, no card required.

### Headlines

1. Scan CI/CD Risk Before Merge
2. Your Workflow YAML Needs Review
3. Add the Supply-Chain Layer

### Descriptions

1. Scan a public GitHub repo free. No signup required.
2. CI/CD checks and package-change analysis inside every PR.
3. One GitHub App. Automatic Check Runs. 14 days free.

### Image Concept 1: The security stack gap

Canvas: 1080x1080 or 1080x1350.

Show a clean three-column developer-tool comparison. Column one is Dependabot
with "known dependency CVEs." Column two is CodeQL with "application code."
Column three is vu1nz with "workflow YAML + package changes." Use simple check
and gap markers rather than competitor logos. Headline: "Cover the layer
between code and production." Footer CTA: "Scan a public repo free."

### Image Concept 2: PR checkpoint

Canvas: 1200x628.

Show a realistic pull-request interface with two findings: "Action uses mutable
tag" and "Suspicious install script introduced." A green checkpoint appears
before the Merge button. Headline: "Catch supply-chain risk while it is still a
diff." Avoid fake GitHub endorsements and label the screen "illustrative."

### Short Video Concept: The silent tools

Length: 15 seconds, 9:16 and 1:1.

1. 0-3s: A dependency update and workflow YAML change enter a PR. Text:
   "Known CVE? No. App-code flaw? No."
2. 3-7s: Dependabot and CodeQL panels show "no relevant finding."
3. 7-11s: vu1nz flags a mutable action tag and suspicious install script.
4. 11-15s: "Add the missing CI/CD and package-diff layer." CTA:
   "Scan your public repo free at vu1nz.com."

## 5. Reddit Ads

### Promoted Post Titles

1. We scanned the layer Dependabot does not: GitHub Actions YAML
2. A free CI/CD security scanner for public GitHub repos, no signup
3. Your PR adds one package. Who reviews what its install script does?

### Body Copy 1: Builder-first

We built vu1nz because dependency CVE scanning and application-code analysis
leave a practical gap: the workflow YAML that holds deploy permissions and the
new packages entering through a PR.

Paste any public `owner/repo` into the scanner. It checks CI/CD patterns and
returns findings without an account. If it is useful, the GitHub App can run on
every PR and post a Check Run.

It is designed to sit alongside Dependabot, CodeQL, Snyk, or Semgrep, not
replace them. Feedback on noisy checks and missed patterns is welcome.

### Body Copy 2: Incident angle

The uncomfortable part of modern supply-chain incidents is that many malicious
updates have no CVE when they land. A workflow action can also be compromised
without changing your application source.

vu1nz checks for risky GitHub Actions patterns and suspicious package changes
before merge. The public repo scanner is free and requires no signup:
https://vu1nz.com

### Body Copy 3: Platform-team angle

Maintaining security YAML in every repository becomes its own source of drift.
vu1nz now installs as a GitHub App: select repositories once, then receive
automatic Check Runs on PRs. Findings include file, line, CWE, and suggested
remediation. The organization trial is 14 days with no card.

### Reddit-Native Angle 1: Ask for counterexamples

Title: "What is your worst GitHub Actions footgun?"

Post around a concrete workflow pattern, show the exact finding format, and ask
readers for repositories or patterns that produce false positives. Keep the
product link at the end rather than leading with it.

### Reddit-Native Angle 2: Open benchmark

Scan five prominent public repositories and publish an anonymized table of
finding categories, not a fear-based "most vulnerable projects" ranking.
Invite maintainers to dispute results and document every corrected false
positive.

### Reddit Image Concept 1

A terminal-style result with three rows: severity, file/line, remediation.
Headline: "A security finding developers can act on before merge."

### Reddit Image Concept 2

A simple diagram: `PR diff -> workflow checks + package sweep -> GitHub Check
Run`. Caption: "No security dashboard required to see the first result."

### Reddit GIF Concept

Six-second loop: paste `owner/repo`, click Scan, findings populate, then zoom to
the file and CWE fields. Use a real permitted demo repository and avoid
fabricated scan results.

## 6. Google Search Ads

### Short Headlines

1. Scan GitHub Actions Risk
2. CI/CD Security Scanner
3. Scan a Public Repo Free
4. Secure GitHub Workflows
5. Catch Risk Before Merge
6. Package Supply-Chain Scan
7. GitHub PR Security Checks
8. Find Unsafe Action Tags
9. Add a CI/CD Security Layer
10. 14-Day GitHub App Trial

### Long Headlines

1. Scan GitHub Actions and Package Changes Before They Merge
2. Add CI/CD Supply-Chain Checks Alongside Dependabot and CodeQL
3. Scan Any Public GitHub Repository for CI/CD Risk Without Signup
4. Install One GitHub App and Receive Security Check Runs on Every PR

### Descriptions

1. Find risky workflow patterns and suspicious package changes inside pull
   requests.
2. Scan a public GitHub repo free. No signup or email required.
3. Install once for automatic GitHub Check Runs across selected repositories.
4. Get findings with severity, file, line, CWE, and recommended remediation.
5. Keep your current security tools and add CI/CD and package-diff coverage.
6. Start a 14-day organization trial with no card required.

## 7. Google Display Ads

### Combination 1

Headline: **Your CI Pipeline Has Production Keys**

Body: Check risky workflow patterns before they merge. Scan a public repo free.

CTA: **Scan Repo**

### Combination 2

Headline: **A Package Can Be Malicious Before It Has a CVE**

Body: Review suspicious package changes and install scripts inside the PR.

CTA: **See How It Works**

### Combination 3

Headline: **Dependabot + CodeQL + The Missing Layer**

Body: Add CI/CD workflow and package-diff checks with the vu1nz GitHub App.

CTA: **Start Free Trial**

### Banner Concept 1: Compact pipeline

For 728x90, 970x250, and 320x100. Use three steps:
`Pull request` -> `vu1nz scan` -> `Check Run before merge`.
Keep one benefit and one CTA visible at all sizes.

### Banner Concept 2: Layer comparison

For 300x250, 336x280, 160x600, and 300x600. Stack three labeled layers:
application code, dependencies, and CI/CD/package changes. Highlight the third
layer with the copy "Add coverage here."

## 8. YouTube and Video Concepts

### Vertical Short: The ordinary PR

Length: 20 seconds, 9:16.

Voiceover:

> This pull request looks ordinary. One workflow action changed. One package
> was added. There is no known CVE, and the application code is clean. vu1nz
> checks the workflow and package diff, then flags the risky pattern before
> merge. Scan a public GitHub repo free at vu1nz.com.

Visual sequence:

1. PR diff with one YAML and one lockfile change.
2. Existing scanners focus on CVEs and application source.
3. vu1nz Check Run identifies the workflow/package finding.
4. Free scanner input and CTA.

### Fifteen-Second Pre-Roll

> Your CI/CD pipeline can deploy production, read secrets, and install code.
> Who reviews its changes? vu1nz checks workflow YAML and new packages on every
> pull request. Add it alongside Dependabot and CodeQL. Scan your public repo
> free at vu1nz.com.

On-screen end card:

**Catch CI/CD and package risk before merge.**

**Scan your public repo free.**

## 9. Image Creative Briefs

### Brief A: Real finding, not a shield illustration

Use an inspectable PR-style interface showing a specific unsafe pattern and a
specific remediation. The finding should include file, line, severity, and CWE.
Avoid generic padlocks, hooded figures, glowing code, or claims that the product
prevents every attack.

### Brief B: Security coverage map

Use a restrained technical diagram showing what common tools inspect and where
vu1nz adds coverage. Phrase differences as product focus, not universal claims
about every competitor configuration.

### Brief C: Five-second public scan

Show the actual `owner/repo` input flow and a real, permitted example result.
The strongest visual proof is the product working, not an abstract security
metaphor.

## 10. Recommended Ad Sizes

- Meta square: 1080x1080
- Meta portrait: 1080x1350
- Meta landscape: 1200x628
- Display: 300x250, 336x280, 728x90, 970x250, 160x600, 300x600
- Mobile display: 320x50, 320x100
- Video vertical: 1080x1920
- Video square: 1080x1080
- Video landscape: 1920x1080

## 11. Suggested Keywords

High intent:

- github actions security scanner
- ci cd security scanner
- scan github workflows
- github action vulnerability scanner
- software supply chain scanner
- package supply chain security
- pull request security checks
- npm malware scanner
- malicious package detection
- github app security scanning

Comparison and education:

- dependabot alternative
- dependabot limitations
- codeql supply chain
- codeql github actions security
- secure github actions
- pin github actions sha
- pull request target security
- ci cd secrets exposure
- package install script security

Use comparison keywords with copy that says "use alongside" or "add coverage,"
not "replace."

## 12. Suggested Negative Keywords

- jobs
- salary
- certification
- course
- tutorial
- definition
- pdf
- cracked
- pirated
- antivirus download
- windows malware removal
- phone virus scanner
- website vulnerability scan
- network port scanner
- barcode scanner
- document scanner
- qr scanner
- free forever

Review query reports weekly and separate research queries from purchase-intent
queries before excluding broad security terms.

## 13. Best Three Ads to Test First

### Test 1: Product proof

Channel: Google Search.

Headline: **Scan a Public Repo Free**

Description: **Find risky GitHub Actions patterns in seconds. No signup or
email required.**

Why first: It matches a concrete, low-friction action and can be measured by
completed public scans.

### Test 2: Stack gap

Channel: Meta retargeting or developer newsletter display.

Headline: **Dependabot + CodeQL + The Missing Layer**

Body: **Add workflow YAML and package-change checks before merge.**

Why first: It explains positioning quickly without asking teams to replace
tools they already trust.

### Test 3: Incident-shaped Reddit post

Channel: Reddit.

Title: **A package can be malicious before it has a CVE**

Body: Use the incident explanation from Reddit Body Copy 2, followed by a
transparent public-scanner link and a request for false-positive reports.

Why first: It fits how security practitioners discuss real failures and opens a
technical conversation instead of presenting generic fear-based advertising.

## Measurement Plan

- Public scanner completion rate from each campaign.
- GitHub App install starts and completed installations.
- Trial activation and first successful PR Check Run.
- Cost per repository scanned and cost per activated organization.
- Finding-detail engagement: users who open remediation guidance.
- Search-term quality and Reddit comment sentiment.

Do not optimize only for clicks. The strongest early activation event is a team
seeing a credible finding on its own repository.
