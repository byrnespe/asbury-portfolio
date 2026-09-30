# Agentic OS

**What it is.** A self-hosted multi-agent operating system. A Flask kernel with a
scheduler, memory API, MCP server, and a fleet of systemd user units orchestrates a
roster of specialist AI agents ("seats") over a message bus, with live dashboards and
an SSE feed served over Tailscale.

**Stack.** Python, Flask, SQLite, systemd user units, MCP, Tailscale, server-sent-events
live feed, external watchdog.

**What it demonstrates.**
- Distributed control-plane engineering: kernel + scheduler + memory + health/deep probes.
- Multi-agent orchestration: schedules and dispatches 18 specialist seats (roster in `~/projects/AGENTS.md`).
- Production ops discipline: watchdogs, systemd units, memory API, MCP server.
- A long-lived, actively maintained system (commit history back to 2026-06).

**Status.** Live — kernel HTTP health endpoint returns 200 on this host (last commit 2026-09-29).

**Source.** `~/projects/agentic-os/` (kernel `app.py`, `mcp_server.py`, `db.py`, plus fleet units).
