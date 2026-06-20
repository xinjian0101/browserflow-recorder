# Contributing to BrowserFlow Recorder

BrowserFlow Recorder is intended to turn authorized browser interactions into reviewable Playwright workflows. Contributions must improve reliability, transparency, maintainability, or safe local execution.

## Before starting

1. Read `README.md`, `ABOUT.md`, and `ROADMAP.md`.
2. Search existing Issues and pull requests.
3. Open a proposal before changing the flow schema, selector strategy, recorder bridge, execution model, or export format.
4. Do not claim support for actions, browsers, platforms, or export targets that have not been implemented and tested.

## Useful contribution areas

- Semantic selector ranking and explanations.
- Event capture for navigation, click, input, select, upload, download, and waits.
- Editable timeline interactions and accessibility.
- Variable extraction and environment-reference handling.
- Deterministic TypeScript and Python Playwright exporters.
- Failure screenshots, bounded retries, diagnostics, fixtures, and documentation.

## Safety and product boundaries

- Only automate systems the user is authorized to use.
- Keep destructive actions disabled during preview unless explicitly enabled.
- Never embed credentials or personal session data in examples.
- Make every generated step inspectable before execution.
- Prefer stable semantic selectors over coordinates or brittle DOM paths.

## Branches and commits

Use focused branch names such as `feat/selector-ranking`, `fix/timeline-order`, or `docs/flow-schema`.

Use Conventional Commit prefixes: `feat:`, `fix:`, `docs:`, `test:`, `refactor:`, and `chore:`.

## Pull-request requirements

Include the user problem, intended behavior, non-goals, affected flow-schema fields, validation steps, browser versions tested, and compatibility impact. Recorder or exporter changes should include deterministic fixtures showing the captured input and generated output.

Keep unrelated formatting, dependency changes, and feature work in separate pull requests.

## AI-assisted contributions

AI tools may assist implementation or documentation, but contributors remain responsible for correctness, licensing, and review. Disclose substantial generated content and explain how it was validated.

## Conduct

Use precise technical language, respect authorization boundaries, and do not publish private browsing data or sensitive failure artifacts.