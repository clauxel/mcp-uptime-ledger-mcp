# MCP Uptime Ledger

Monitor MCP server uptime, auth failures, schema drift, and SLA evidence.

Paid remote MCP for server uptime checks, schema validation, auth failure detection, SLA receipts, and status report exports.

## Public Endpoints

- Website: https://mcpuptimeledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://mcpuptimeledger.clauxel.com/mcp
- Server card: https://mcpuptimeledger.clauxel.com/server-card.json
- Registry name: `com.clauxel.mcpuptimeledger/mcpuptimeledger-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_mcp_server_uptime`
- `validate_tool_schema`
- `detect_auth_failure`
- `issue_sla_receipt`
- `export_status_report`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://mcpuptimeledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://mcpuptimeledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://mcpuptimeledger.clauxel.com/server-card.json
- MCP endpoint: https://mcpuptimeledger.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
