---
name: setup
description: Inspect agentescrow connection and integrated tool inventory.
---

This is an unpublished client configuration. Native installation and execution have not been verified. Never request credentials in chat.

The registered binding is enabled; this configuration carries its exact existing public client and requested scopes. A fresh user-controlled OAuth consent is required to use it. Existing grants are not expanded.

Expected static inventory; confirm tools/list and inspect input schemas before any invocation. Do not invent organization IDs or claim an unrun case succeeded.

- `agentescrow_draft_get` — `escrow:read`
- `agentescrow_verifyEscrowEvidence` — `agentescrow:extensions`
- `proof_ingest_claim` — `agentescrow:extensions`
- `proof_collect_evidence` — `agentescrow:extensions`
- `proof_verify` — `agentescrow:extensions`
- `proof_issue_receipt` — `agentescrow:extensions`
- `proof_verify_receipt` — `agentescrow:extensions`
- `proof_needs_human_review` — `agentescrow:extensions`
- `humanloop_createEscrow` — `agentescrow:human-review`
- `humanloop_escalate` — `agentescrow:human-review`
- `humanloop_resolve` — `agentescrow:human-review`
- `humanloop_auditTrail` — `agentescrow:human-review`

Parent integrations belong to this product; do not create separate duplicate products. No payments or external business actions are authorized by this setup skill.
