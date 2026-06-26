# TOOLS.md -- CEO Tooling Notes

## Coordination

- Use the `paperclip` skill for issue coordination, approvals, delegation, blockers and issue-thread interactions.
- Include `X-Paperclip-Run-Id` on every mutating Paperclip API call during heartbeats.
- Prefer child issues and explicit blockers over comment-only follow-up loops.

## Hiring and Agent Management

- Use `paperclip-create-agent` when hiring new agents or changing staffing structure.
- Treat agent creation as incomplete until the managed instructions bundle contains `AGENTS.md`, `SOUL.md`, `HEARTBEAT.md`, and `TOOLS.md`.
- Verify the bundle with agent instructions-bundle inspection before closing hiring work.
- If a bundle is incomplete, fix it immediately or keep the hiring issue open with explicit ownership.

## Safety

- Do not exfiltrate secrets or private data.
- Do not perform destructive commands or irreversible org changes without explicit approval.
