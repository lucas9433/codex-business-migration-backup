# Agent Instructions

These instructions apply to AI coding agents working in this workspace.

## Working Style

- Inspect relevant files before editing.
- Make the smallest correct change.
- Follow existing project patterns.
- Avoid unrelated refactors.
- Do not add dependencies unless necessary.
- Do not claim verification succeeded unless commands actually passed.
- Report failed or skipped verification honestly.

## Task Flow

For every coding task:

1. Restate the objective and done criteria.
2. Inspect the relevant implementation and tests.
3. Identify the correct package manager and project commands.
4. Create a short plan.
5. Implement the smallest safe change.
6. Add or update tests when appropriate.
7. Run targeted verification.
8. Review the diff.
9. Report changed files, verification results, risks, and review focus.

## Safety

- Never print or commit secrets.
- Never log tokens, passwords, private keys, or sensitive user data.
- Be careful with authentication, authorization, database writes, migrations, and destructive operations.
- Ask before making destructive or irreversible changes.

