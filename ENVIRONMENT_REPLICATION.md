# Environment Replication Snapshot

This document captures the current working environment so it can be recreated as closely as possible in a Personal Pro/Codex setup.

## Current Codex settings snapshot
- Default model: `gpt-5.4-mini`
- Reasoning effort: `medium`
- Sandbox mode on Windows: `elevated`
- Enabled plugins:
  - `google-drive@openai-curated`
  - `notion@openai-curated`
  - `browser-use@openai-bundled`
  - `chrome@openai-bundled`
  - `canva@openai-curated`
- Trusted project paths:
  - `C:\Users\Lucas. J\Documents\Codex\2026-05-13\codex-threads-019e175d-82ce-7e02-89c1`
  - `C:\Users\Lucas. J\Documents\Codex\2026-05-13\codex-threads-019e201b-5264-7fd3-b223`
  - `C:\Users\Lucas. J\Documents\Codex\2026-05-13\codex-threads-019e201b-5264-7fd3-b223-2`
  - `C:\Users\Lucas. J\Documents\Codex\2026-05-13\codex-wsl2-ubuntu-codex-1-powershell`
  - `C:\Users\Lucas. J\Documents\Codex\2026-05-14\files-mentioned-by-the-user-1`

## What must be recreated in the new environment
- The same OpenAI account/workspace layout
- Google Drive and Sheets access
- Notion access
- Chrome session access if browser-based work is needed
- The same enabled plugins and connectors
- Trusted project/workspace paths where the work happens
- Local setup files and workspace notes

## What cannot be copied literally
- Live browser login sessions
- OAuth tokens inside the browser or connector state
- Workspace-only permissions and seat assignments
- Any secrets that were never exported

## Recommended restore order
1. Create the Personal Pro/Codex account and confirm the workspace type.
2. Re-enable the same plugins/connectors.
3. Reconnect Google, Notion, and Chrome-based workflows.
4. Restore the GitHub backup repo and the migration docs.
5. Recreate any workspace-specific prompts or project notes.
6. Rebuild and test one real workflow end-to-end before canceling Business.

## Practical rule
Do not assume the environment is complete until a real task works in the Personal setup.
