# Hi, I'm Micah Yee(zus) 👋

I build **AI-integration tooling and internal dashboards** — production [Model Context Protocol (MCP)](https://modelcontextprotocol.io) servers that connect AI assistants to real business systems, plus the full-stack dashboards that turn operational data into something teams can actually use.

Most of this was built at **Gem**, a growth-stage HR-tech SaaS company, to automate not just IT and operations but also our GTM and FinOps and GA teams to enable teams to utilize LLMs and AI with the tools they depend on.

## 🔌 MCP servers

TypeScript MCP servers deployed on **Google Cloud Run** behind **domain-restricted Google OAuth** — exposing business APIs to AI assistants as safe, auditable tools.

| Server | What it does |
|--------|--------------|
| [gong-mcp](https://github.com/micahyee415/gong-mcp) | Gong sales-intelligence — calls, transcripts, trackers, scorecards (dual stdio / HTTP transport) |
| [salesforce-mcp-server](https://github.com/micahyee415/salesforce-mcp-server) | Read-only Salesforce — SOQL, SOSL, reports, schema, bulk fetch |
| [google-sheets-mcp](https://github.com/micahyee415/google-sheets-mcp) | Google Sheets read/write with a write allowlist + audit logging |
| [google-slides-mcp-server](https://github.com/micahyee415/google-slides-mcp-server) | Read, template-fill, and edit Slides |
| [vitally-mcp](https://github.com/micahyee415/vitally-mcp) | 40-tool Vitally customer-success integration |
| [upflow-mcp](https://github.com/micahyee415/upflow-mcp) | Upflow accounts-receivable — invoices, payments, finance |
| [dropbox-paper-mcp-server](https://github.com/micahyee415/dropbox-paper-mcp-server) | Dropbox Paper docs (read/write) |
| [github-mcp-oauth-proxy](https://github.com/micahyee415/github-mcp-oauth-proxy) | OAuth proxy fronting the official GitHub MCP server |

## 📊 Dashboards

Full-stack **Next.js** apps (App Router, Auth.js Google SSO, Postgres, Vercel).

| Dashboard | What it does |
|-----------|--------------|
| [ai-spend-tracker](https://github.com/micahyee415/ai-spend-tracker) | AI/software spend split into licenses vs token/API, daily Ramp sync, admin panel |
| [mcp-fleet-dashboard](https://github.com/micahyee415/mcp-fleet-dashboard) | Health, metrics, and audit logs for a fleet of MCP servers |
| [anthropic-usage-dashboard](https://github.com/micahyee415/anthropic-usage-dashboard) | Anthropic API usage & cost across multiple orgs |
| [twilio-spend-dashboard](https://github.com/micahyee415/twilio-spend-dashboard) | Twilio usage/spend with a compliance view |

## 🛠️ Automation

- [ramp-receipt-scanner](https://github.com/micahyee415/ramp-receipt-scanner) — Python: scans receipts/invoices, classifies them with Claude (Haiku), and uploads to Ramp with transaction matching

## 🧰 Tech

`TypeScript` · `Node` · `Next.js` · `React` · `Python` · `Google Cloud Run` · `Cloud Build` · `Postgres` · `Auth.js` · `Model Context Protocol` · `Docker`

---

Every repo ships with a README, an MIT license, and a security policy. Feel free to explore or reach out through GitHub.
