# marr-linux-releases

Preserve existing application behavior, credentials and unrelated work.

## Validation

Follow [TESTING.md](TESTING.md). Test only the exact merged `beta` candidate,
once per relevant scope, and reuse its receipt for production promotion.
Feature branches and PRs use code/diff review; do not run test suites,
watchers or repeated build/lint/typecheck loops. Keep meaningful regression
coverage and release safeguards.
