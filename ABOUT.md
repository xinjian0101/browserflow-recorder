# About BrowserFlow Recorder

## One-line description

A local-first visual recorder for turning authorized browser interactions into reviewable, editable, and exportable Playwright workflows.

## Suggested GitHub About text

Record browser actions, review selectors and variables, test locally, and export maintainable Playwright workflows in TypeScript or Python.

## Suggested topics

`playwright`, `browser-automation`, `workflow-recorder`, `developer-tools`, `testing`, `typescript`, `python`, `local-first`, `desktop-app`, `no-code`

## Mission

BrowserFlow Recorder will help users create reliable browser workflows without treating recorded steps as an opaque script. The recorder should explain what was captured, why a selector was chosen, which values are configurable, and what happened during a test run.

## Intended users

- QA engineers creating reproducible browser scenarios.
- Operations teams documenting repetitive web workflows.
- Developers prototyping Playwright tests.
- Educators demonstrating browser automation concepts.
- Independent builders who need maintainable local automation.

## Scope

The planned product includes action capture, semantic step representation, visual editing, variable extraction, assertions, local execution, diagnostics, and Playwright export.

## Non-goals

- Operating against systems without authorization.
- Hiding generated behavior from the user.
- Guaranteeing that recorded selectors remain stable forever.
- Replacing code review or application-specific testing strategy.
- Claiming official affiliation with Playwright or Microsoft.

## Quality bar

The first preview should produce deterministic exports from the same reviewed flow, show clear failure evidence, avoid embedding sensitive values in generated examples, and make every action editable before execution.

## Maintenance policy

Changes to the flow schema and exporters require migration notes, fixtures, and regression tests. User-visible behavior should be documented in release notes. Screenshots and badges must represent released software only.

## Current phase

Foundation and interaction design. No executable release has been published yet.