# Security Policy

## Current support status

BrowserFlow Recorder is in the design and prototype phase. No released version should be treated as production-ready until a preview release is explicitly published.

## Reporting a security problem

Do not place private browsing data, account information, screenshots, or detailed reproduction material in a public Issue.

Use GitHub private vulnerability reporting when available. Otherwise open a minimal Issue requesting a private communication channel and include only the affected component and general impact.

A useful private report includes the affected commit, operating system, browser and Playwright versions, reproduction steps, observed impact, and a sanitized example.

## Sensitive areas

- Persisting browser-session or form data.
- Exporting private values into generated scripts or fixtures.
- Executing irreversible actions without explicit review.
- Running a workflow against an unintended host or account.
- Unsafe file upload or download paths.
- Browser integrations with permissions broader than required.
- Retry behavior that repeats irreversible actions.

## Expected safeguards

Workflows should display their target origin, variables, generated selectors, and executable steps before a run. Private values should use local references rather than committed plaintext. Preview runs should use bounded retries and produce sanitized diagnostics.

## Disclosure

Validated reports will be investigated privately where practical. Public release notes should explain affected versions, impact, and remediation without exposing user data.