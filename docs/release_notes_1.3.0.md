# codex_workflow 1.3.0 — Simplified deployment closure

- Removed the built-in deployment usage report skill, parser, and mandatory
  Archivist reporting step. Deployment closure retains documentation and the
  read-only Git handoff.
- Upgrades remove the retired workflow-owned report skill through the existing
  ownership manifest while preserving unrelated user skills.
- Senior Executor remains on `gpt-6.1-sol` with `medium` reasoning.
- Corrected the README release link to `zzJune/codex_workflow`.

Release assets: `codex_workflow-1.3.0.zip` and `SHA256SUMS`.

Validation: 64 runtime tests passed on Python 3.12.10, package-schema validation,
release archive construction, and archive verification.
