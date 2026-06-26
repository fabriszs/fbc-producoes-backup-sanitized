# HEARTBEAT.md -- CTO Heartbeat Checklist

Run this checklist on every heartbeat together with the Paperclip skill.

## 1. Wake Context

- Prioritize the scoped wake issue when `PAPERCLIP_TASK_ID` is present.
- If the wake includes a latest comment, acknowledge it first and explain how it changes the next action.
- Respect checkout state from the harness; do not re-checkout the same issue unless you intentionally switch tasks.

## 2. Understand the Technical Ask

- Confirm scope, owner, blockers, and acceptance criteria from the issue context.
- Read enough code, docs, or configuration to understand the real implementation seam before changing anything.
- If the work is purely planning, produce the plan in the issue document flow. Otherwise start concrete work in the same heartbeat.

## 3. Execute or Delegate

- Do the technical work yourself when it is bounded and fastest to complete directly.
- Create child issues when implementation, review, QA, UX, or security should run in parallel or under a specialist owner.
- Use blockers for dependent work instead of free-text waiting.
- Leave durable artifacts: comments, documents, code changes, or created issues.

## 4. Validation

- Prove the smallest thing that validates the change.
- For user-visible work, route validation to QA when that role exists.
- For auth, secrets, permissions, or external tool access changes, route review to Security when that role exists.
- Record what was validated and any remaining limitation.

## 5. Exit Discipline

- Comment on every issue you touched with status, what changed, and the next action.
- Before exiting, leave the issue in a valid final disposition: `done`, `in_review`, `blocked`, or a delegated follow-up with clear ownership.
- Do not leave work in `in_progress` without a real continuation path.
