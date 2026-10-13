# Organizing an agent workflow

By Major · Unofficial

Derived from [AI agent operations](../../skills/whop-quick-scaler-launcher/references/ai-agent-operations.md). Reference date: 2026-09-29. These are general operating recommendations, not an agent-team feature installed by Whop. This assistant can draft the workflow; it cannot operate the team or its accounts.

## Roles and permission boundaries

The human owner approves scope, commercial terms and consequential actions. A coordinator assigns bounded work. Researchers provide dated evidence, producers create drafts, an independent reviewer checks them, and a separately authorized operator performs an approved action. A review pass does not authorize publication or sending.

Use the permission sequence read, local draft, then specifically approved action. A remote draft is still an external write and may notify people or expose an uploaded asset. Every outbound message needs approval of the actual text, recipient, attachments and timing. No permission level changes the conversational bot's advisory-only role.

## Copyable task brief

```text
Outcome:
Inputs and source version:
Owner and independent checker:
Allowed operations:
Forbidden operations:
Exact deliverable:
Acceptance checks:
Fields or behavior to preserve:
Dependencies:
Approval needed for any external action:
Stop condition and first unfinished stage:
```

Give each worker the decisions it needs. Keep one editor for shared files or account objects. Store completed stages durably so interruption does not force a restart.

After a timeout, reconcile the target before retrying. Pause on lost authentication and ask the owner to restore secure access. Do not consume editorial retries or create a duplicate to work around an access problem. Use bounded retries for temporary failures and escalate repeated faults.

A completion claim requires evidence for the exact result: saved draft, rendered page, buyer access or payment state. A worker's success message proves none of those by itself. Preserve the difference between configured, user-reported, publicly checked and privately unverified.

Official sources checked 2026-09-29: [Agent Mode](https://docs.whop.com/cli/agent-mode.md), [Idempotent Requests](https://docs.whop.com/developer/api/idempotency.md). The board and role design is an operating recommendation.
