# Migration Protocol

## Goal
Move safely from a ChatGPT Business + Codex environment to a Personal Pro/Codex environment without losing important work.

## Safe order
1. Inventory everything in the Business workspace.
2. Export whatever is exportable from Personal workspaces.
3. Manually copy everything important from Business into GitHub or another external backup.
4. Recreate the setup in Personal Pro/Codex.
5. Test the Personal environment before canceling Business.
6. Only after validation, cancel Business.

## What to inventory
- Custom GPTs
- Projects
- Chats that matter
- Uploaded files
- Custom instructions
- Prompt libraries
- GitHub repo links
- Notion pages or databases
- Browser/bookmark shortcuts
- Any OAuth-connected tools

## What to back up
- GPT instructions and knowledge file names
- Project instructions and files
- Key chat transcripts
- Prompt templates in Markdown
- Integration notes for GitHub, Notion, Google, Slack, and similar tools
- Any screenshots that document workflows or UI state

## What to reconnect in Personal
- GitHub account and repo access
- Google account and Sheets/Drive access
- Notion workspace and database connections
- Any project-specific OAuth connections
- Custom GPTs recreated from the inventory
- Any codex workspace settings or shortcuts

## Validation checklist before canceling Business
- Personal workspace can open and edit the key repos
- Personal workspace can access the important documents
- The recreated GPTs behave correctly
- The important prompts are available
- The user can reproduce the same workflows in the Personal environment
- A small test task succeeds end-to-end

## Cancellation rule
Do not cancel Business until the Personal setup has passed a real test for the most important workflow.
