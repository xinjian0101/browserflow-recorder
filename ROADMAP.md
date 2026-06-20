# BrowserFlow Recorder Roadmap

Last reviewed: 2026-06-20

## Phase 0 — Foundation

- [x] Define positioning, intended users, and usage boundaries.
- [x] Publish the initial workflow and interface direction.
- [ ] Select the project license and prepare third-party notices.
- [ ] Add contribution, security, and conduct policies.
- [ ] Define the versioned flow schema.

## Phase 1 — Recorder prototype

- [ ] Open a local Playwright session.
- [ ] Capture navigation, click, input, select, and wait events.
- [ ] Store events in a readable local project file.
- [ ] Show captured events in a basic timeline.
- [ ] Add start, pause, resume, and stop controls.

**Exit criteria:** a short browser session can be recorded and reopened without losing ordered steps.

## Phase 2 — Stable editing model

- [ ] Rank semantic selector candidates.
- [ ] Add step editing, grouping, disabling, and reordering.
- [ ] Add reusable variables and local configuration references.
- [ ] Add URL, text, visibility, and download checks.
- [ ] Add schema validation and migration fixtures.

## Phase 3 — Preview runner and diagnostics

- [ ] Add preview runs with clear confirmation.
- [ ] Capture screenshots and structured failure reports.
- [ ] Add bounded retries and timeouts.
- [ ] Show exact generated actions before a run.
- [ ] Add deterministic regression fixtures.

## Phase 4 — Exporters

- [ ] Export Playwright TypeScript projects.
- [ ] Export Playwright Python projects.
- [ ] Add data-driven CSV and JSON examples.
- [ ] Add optional continuous-integration examples.
- [ ] Document unsupported actions and manual-review requirements.

## Phase 5 — Preview release

- [ ] Package the desktop application.
- [ ] Publish real screenshots and a demonstration workflow.
- [ ] Add accessibility and keyboard-navigation review.
- [ ] Publish checksummed preview artifacts.
- [ ] Collect structured feedback before declaring stability.