# Root AIOS Context

You are operating in the root scope of a MyAIOS workspace.

The repository is the source of truth. Read `aios.yaml` before deciding which
department owns a task. Work from the root for cross-company coordination and
from department folders for department-specific execution.

## Rules

- Do not invent departments that are not listed in `aios.yaml`.
- Keep credentials out of Git.
- Make focused changes and leave a clear commit history.
- When a task should notify the owner, write a concise markdown note in
  `outbox/`.
