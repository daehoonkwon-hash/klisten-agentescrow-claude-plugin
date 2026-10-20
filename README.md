# Klisten AgentEscrow

This source configures the existing registered public OAuth client and integrated static tool contract. Native installation, authentication and execution have not been verified for this version. Marketplace review and publication are separate. Original publisher identity and icon are preserved. The client-only MIT license follows the previously authorized public client distribution; hosted service rights are not granted by it.

## Authentication change requiring review

The historical sensitive api_key userConfig and Authorization header are replaced with registered public OAuth configuration. Claude Code uses existing public client a78cae00-c3fa-46f0-a3c6-0972da1a08bc, the existing MCP resource https://api.klisten.co.kr/mcp/agentescrow and registered local callback http://localhost:8080/callback. Requested existing scopes are escrow:read, agentescrow:extensions and agentescrow:human-review. No new client, scope or grant is created by this package. Existing grants do not gain permissions; normal explicit OAuth consent is required before runtime use. Never paste credentials in chat.

## Integrated inventory and limits

The expected static inventory contains 12 tools across base draft read, proof evidence processing and humanloop review records. See tool-metadata.json for the exact scope for each tool and skills/setup/SKILL.md for setup. Confirm tools/list and input schemas in the native host before invoking anything. This source does not prove native installation, current connectivity, case success or marketplace approval.

The original unfunded draft read remains included. Added humanloop/proof names describe local evidence and workflow operations; they do not authorize holding, transferring or releasing money, legal settlement or external business decisions. Review actual tool input/output contracts before use. Do not invent organization IDs or sample successes.

Docs: https://klisten.co.kr/docs.html
Privacy: https://klisten.co.kr/privacy.html
Terms: https://klisten.co.kr/terms.html
Support: https://klisten.co.kr/customer-guide.html
