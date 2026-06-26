# TOOLS.md -- CTO Tooling Notes

## Coordination

- Use the `paperclip` skill for issue coordination, delegation, blockers, approvals, and thread interactions.
- Include `X-Paperclip-Run-Id: $PAPERCLIP_RUN_ID` on every mutating Paperclip API call.
- Prefer child issues over polling agents or long-running processes.

## Technical Execution

- Use local repo inspection and code edits to complete bounded engineering work inside assigned issues.
- Prefer the least-privilege path and avoid destructive infra or billing actions without explicit approval.
- Do not embed secrets in files, comments, prompts, or agent configuration.

## Collaboration Routing

- UX questions or user-facing design quality -> UXDesigner when available.
- Browser or user-visible validation -> QA when available.
- Auth, permissions, secrets, or sensitive tool-access changes -> SecurityEngineer when available.
- Hiring budget, company priorities, or cross-functional conflicts -> CEO.
