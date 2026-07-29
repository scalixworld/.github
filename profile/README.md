# Scalix Cloud

One system. Runs on any data centre's infrastructure.

Scalix Cloud is a managed cloud platform built in Rust. It gives teams a complete backend without assembling separate services: a Postgres-wire-compatible storage engine, microVM compute with sub-second cold starts, object storage, project-scoped auth, and an AI inference gateway. One API key. One billing meter.

**Platform components**

- Storage: Postgres-wire protocol, per-tenant isolation, point-in-time recovery (RPO under 5 minutes)
- Compute: ScalixNova microVM runtime with enclave support and per-second billing
- Auth: project-scoped tokens, RBAC, and audit logs
- AI: bring-your-own-key inference gateway with usage metering
- 46 MCP tools so agents and LLMs can operate the full platform programmatically

**Links**

| | |
|---|---|
| Website | [scalix.world](https://scalix.world) |
| Docs | [docs.scalix.world](https://docs.scalix.world) |
| Console | [console.scalix.world](https://console.scalix.world) |
| MCP server | `api.scalix.world/v1/mcp` |
| Discord | [discord.gg/Ktq9qvpzBM](https://discord.gg/Ktq9qvpzBM) |
| X | [@scalix\_world](https://x.com/scalix_world) |
