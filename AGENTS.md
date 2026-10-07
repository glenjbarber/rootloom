# Repository guidance

## Shared coordination policy

Canonical policy: [ADR-0000000](https://app.notion.com/p/3f0f5fa187af812b837eecf5b6d0cec5).

Policy revision retrieved for repository setup: **2026-10-06T22:36:06.708Z**. At the start of each task, retrieve the current accepted policy and record the revision used. If retrieval fails, pause project actions. The accepted shared policy takes precedence over conflicting repository instructions for shared workflow; report conflicts explicitly. Repository-specific build, test, ledger, and commit rules remain local.

Shared assistant preferences: [preferences](https://app.notion.com/p/3f2f5fa187af8113a274c0f89d185eb8). Retrieve them at task start and context refresh.

## Branch and pull request workflow

- Do work on a branch and open a pull request against `main`.
- Do not commit directly to `main`, push to `main`, or merge without review.
- Use worktrees at `/Users/gjb/work/rootloom-worktrees/<type>-<name>` when a separate worktree is needed. Remove a worktree after its merge/push workflow is verified complete.
- Keep architecture and project documentation under `docs/`.

## Scope and decisions

`Milestone0` is the project name and `rootloom` is the repository name. Consult [docs/scope.md](docs/scope.md) and current accepted decision records for project scope. Glen controls acceptance and supersession of decision records; drafts and task progress may be prepared by authorized contributors.
