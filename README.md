# MyAIOS Workspace

This repository is the source of truth for a MyAIOS company workspace.

AIOS reads the root `aios.yaml` file to discover departments. The `_root`
scope is the company root, and each department is a top-level folder listed in
`aios.yaml`.

## Structure

- `aios.yaml` defines departments and ignored folders.
- `CLAUDE.md` and `AGENTS.md` hold root operating context.
- `org.md` holds company-level context shared into departments.
- `sample/` is an example department with provider context and a scheduled task.
- `outbox/` is for owner-facing status messages.

## Next Steps

1. Rename or replace the `sample` department.
2. Update `org.md`, `CLAUDE.md`, and `AGENTS.md` with your real company context.
3. Add department folders to `aios.yaml`.
4. Connect Claude Code and/or Codex in MyAIOS settings.
