# Scalix Cloud

**Full-stack managed cloud platform built in Rust. One API key. One billing meter.**

> **Proprietary Platform · Public Developer Ecosystem**
> **Scalix Cloud is a proprietary, closed-source managed cloud platform** built and owned by **Scalix World Pvt Ltd** (India) with international licensing via **Energy FW Ltd** (UK). Core platform infrastructure source code is closed-source. This GitHub organization hosts official public developer tooling — SDKs, CLI binary distributions, MCP integrations, and the Scalix Marketplace catalog — selectively open-sourced under MIT where helpful for developers.

---

## Platform Services

- **ScalixNova (Database):** Serverless PostgreSQL (16 / 17 / 18) with per-tenant isolation, point-in-time recovery, and `pgvector`.
- **Scalix Run (Containers):** Managed container workloads with automated HTTPS and scale-to-zero.
- **Scalix Functions:** Serverless Node.js and Python functions.
- **Scalix Computers:** Persistent Linux machines and isolated sandboxes.
- **Scalix AI:** Managed multi-vendor AI model catalog served through an OpenAI-compatible API (chat, streaming, embeddings, speech, RAG) with unified metering.
- **Storage, KV & Auth:** S3-compatible object storage, key-value store, project-scoped IAM / OAuth / RBAC, and audit logs.
- **Agent-Native MCP (53 tools):** Single remote Streamable HTTP MCP endpoint (`https://api.scalix.world/v1/mcp`) so AI agents and coding assistants operate the full platform programmatically.
- **Developer Suite:** Scalix Coder, Scalix IDE, and the [Scalix Marketplace](https://github.com/scalixworld/scalix-marketplace) ([catalog API](https://scalix.world/agent-catalog/listings)).

---

## Public Developer Repositories

| Repository | Purpose | License / Scope |
|---|---|---|
| [`scalix-world-sdk`](https://github.com/scalixworld/scalix-world-sdk) | Official TypeScript, Python & Auth SDK source mirrors (`@scalix-world/sdk`, `scalix-sdk`, `@scalix-world/auth`) | MIT |
| [`scalix-cloud-cli`](https://github.com/scalixworld/scalix-cloud-cli) | Prebuilt binary distribution for the `scalix-cloud` CLI | BUSL-1.1 / Proprietary binary distribution (core source is private) |
| [`scalix-cloud-mcp`](https://github.com/scalixworld/scalix-cloud-mcp) | Official MCP plugin manifests & agent skills for `https://api.scalix.world/v1/mcp` | MIT (manifests & skills) |
| [`scalix-marketplace`](https://github.com/scalixworld/scalix-marketplace) | Static Git-backed catalog of MCP servers, skills, rules, and subagents | MIT |
| [`homebrew-tap`](https://github.com/scalixworld/homebrew-tap) | Homebrew formula for `scalix-cloud` CLI (`brew install scalixworld/tap/scalix-cloud`) | Packaging formula |
| [`scoop-bucket`](https://github.com/scalixworld/scoop-bucket) | Scoop manifest for `scalix-cloud` CLI on Windows (`scoop install scalix/scalix-cloud`) | Packaging manifest |

---

## Links & Trust

| Resource | URL / Contact |
|---|---|
| Website | [scalix.world](https://scalix.world) |
| Console | [console.scalix.world](https://console.scalix.world) |
| Docs | [docs.scalix.world](https://docs.scalix.world) |
| Marketplace | [scalix-marketplace](https://github.com/scalixworld/scalix-marketplace) · [Catalog API](https://scalix.world/agent-catalog/listings) |
| MCP Endpoint | [`https://api.scalix.world/v1/mcp`](https://api.scalix.world/v1/mcp) |
| Legal & Policies | [Terms](https://scalix.world/terms) · [Privacy](https://scalix.world/privacy) · [Security](https://scalix.world/security) |
| Subprocessors | [scalix.world/subprocessors](https://scalix.world/subprocessors) |
| Security | [`security@scalix.world`](mailto:security@scalix.world) · [security.txt](https://scalix.world/.well-known/security.txt) |
| Discord | [discord.gg/Ktq9qvpzBM](https://discord.gg/Ktq9qvpzBM) |
| X | [@Scalix_World](https://x.com/Scalix_World) |
| LinkedIn | [linkedin.com/company/scalix-world](https://www.linkedin.com/company/scalix-world) |

---

<sub>© 2026 Scalix World Pvt Ltd. Scalix Cloud and ScalixNova are brands of Scalix World Pvt Ltd (India), licensed internationally via Energy FW Ltd (UK).</sub>
