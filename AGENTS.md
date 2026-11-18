# marr-linux-releases

## Completing work

- Carry the requested outcome through the next authorized steps. Make reasonable, reversible implementation choices and explain consequential assumptions. Ask only for a real access blocker, a material scope decision, or an action whose target or effect is not authorized; continue independent work meanwhile.
- Preserve the user's selected model, provider and reasoning effort. Use supported runtime options and task-appropriate defaults when no choice was specified; do not silently add paid services or change provider settings.
- Read relevant code and instructions, then implement. Reuse existing logic and preserve caller contracts unless the task changes them. Prefer readable names and direct control flow over code golf, unnecessary helpers or speculative abstractions.
- Check current ownership and Git state. Isolate concurrent edits and delegate independent scopes when useful; avoid duplicate sessions or validation. Preserve unrelated changes and leave enough state for a handoff.
- Review the requested outcome before reporting completion. State what changed, the actual evidence, pending beta validation and any concrete blocker. Make the final report understandable without progress updates. Repository instructions do not grant production, publication or destructive-action authority.

This repository distributes Linux release information and artifacts. Preserve published artifact identities and download links. Source edits do not authorize replacing binaries or publishing a release.

## Validation

Follow [TESTING.md](TESTING.md). Test only the exact merged `beta` candidate,
once per relevant scope, and reuse its receipt for production promotion.
Feature branches and PRs use code/diff review; do not run test suites,
watchers or repeated build/lint/typecheck loops. Keep meaningful regression
coverage and release safeguards.
