# Automation layer (n8n + Cloudflare Workers)

**What it is.** A no/low-code automation stack: exported n8n workflows (lead-engine
daily, store fulfillment, research event bridge, Hermes bridge) plus a Cloudflare
Workers/Agents suite (a React app running on the Workers + Agents SDK).

**Stack.** n8n (JSON workflow exports), Cloudflare Workers + Agents SDK, React,
Wrangler, TypeScript.

**What it demonstrates.**
- No/low-code workflow automation (n8n) wired into real business processes.
- Serverless edge deployment (Cloudflare Workers) with the Agents SDK.
- Event-bridge and webhook-consumer patterns.

**Status.** Workflows built and exported; Workers built. (n8n service was not running
on this host at probe time — see note.)

**Source.** `~/projects/asbury-ai-solutions/Operations/Workflows/n8n-cloudflare/` (workflows),
`~/projects/org-arch-migration/n8n/workflow-exports/`, `~/projects/asbury-ai-solutions/workers/asbury-agents/`.
