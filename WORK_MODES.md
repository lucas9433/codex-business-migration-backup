# Work Modes

Choose the mode based on the task.

## Fast Fix Mode
Use for small bugs, typo fixes, simple test updates, and narrow changes.

Behavior:
- Inspect only directly relevant files.
- Make the smallest change.
- Run targeted verification only.
- Keep final report brief.

## Standard Engineering Mode
Use for normal feature work, backend/frontend changes, refactors, and test additions.

Behavior:
- Follow the full workflow.
- Add or update tests when appropriate.
- Run targeted tests plus static checks when available.

## High-Risk Mode
Use for auth, payments, permissions, database migrations, security, data deletion, infrastructure, CI/CD, or public API changes.

Behavior:
- Slow down.
- Explicitly identify risks.
- Check backward compatibility.
- Prefer adding tests before implementation.
- Do not make destructive changes without explicit user approval.
- Include rollback or migration notes.

## Efficiency Rules

- Do not read the entire repository unless necessary.
- Start with the smallest relevant file set.
- Prefer search over broad file browsing.
- Prefer nearby examples over global style inference.
- Run targeted tests before full suites.
- Do not run expensive commands repeatedly without a reason.
- If a command is slow or unavailable, switch to the next strongest practical verification.
- Avoid summarizing obvious repository structure unless it affects the task.

## Completion Gate

Before final response, confirm:

- The requested behavior was implemented or the blocker is clearly reported.
- The diff was reviewed.
- Changed files are listed.
- Relevant verification was run or explicitly marked as not run.
- Any failing command is reported honestly.
- Assumptions are stated.
- Risks are stated for non-trivial changes.
- No unrelated changes remain.
- No secrets or sensitive data were exposed.

