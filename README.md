# Merge queue test harness

Mirrors artemis `ci_checks.yml` with sleeps instead of builds. Marker files drive the scenarios:
`need-sdk` makes `ensure_sdk` run, `fail-format` fails the PR-level check, `fail-heavy` fails Artemis CI in the queue.
