# ZeroLang Agent Compiler MCP

ZeroLang Agent Compiler MCP is a hosted remote MCP for ZeroLang.

This repository is a public documentation project for ZeroLang Agent Compiler MCP. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://zerolangcompiler.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=zerolangcompiler_public_docs&utm_content=readme_home
- Pricing: https://zerolangcompiler.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=zerolangcompiler_public_docs&utm_content=readme_pricing
- Checkout: https://zerolangcompiler.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=zerolangcompiler_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://zerolangcompiler.clauxel.com/mcp
- Server card: https://zerolangcompiler.clauxel.com/server-card.json
- Registry name: `com.clauxel.zerolangcompiler/zerolangcompiler-mcp`
- Tools: `compile_zerolang_program`, `run_zerolang_fixtures`, `explain_compile_error`, `export_agent_plan_json`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: compile_zerolang_program
- MCP tool: run_zerolang_fixtures
- MCP tool: explain_compile_error
- MCP tool: export_agent_plan_json

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
