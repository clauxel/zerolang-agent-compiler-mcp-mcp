# ZeroLang Agent Compiler MCP

ZeroLang Agent Compiler MCP remote MCP for ZeroLang.

Paid remote MCP for ZeroLang, structured receipts, usage logs, and audit-ready JSON evidence.

## Public Endpoints

- Website: https://zerolangcompiler.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r26_224703
- MCP endpoint: https://zerolangcompiler.clauxel.com/mcp
- Server card: https://zerolangcompiler.clauxel.com/server-card.json
- Registry name: `com.clauxel.zerolangcompiler/zerolangcompiler-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `compile_zerolang_program`
- `run_zerolang_fixtures`
- `explain_compile_error`
- `export_agent_plan_json`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://zerolangcompiler.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r26_224703
- Pricing: https://zerolangcompiler.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r26_224703#pricing
- Server card: https://zerolangcompiler.clauxel.com/server-card.json
- MCP endpoint: https://zerolangcompiler.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
