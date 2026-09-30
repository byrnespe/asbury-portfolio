# Dealership MCP

**What it is.** A Model Context Protocol (MCP) server that exposes dealership tools and
data to AI agents, so a model can query inventory, leads, and dealer operations through
a standard protocol. Ships as a Python package with a systemd service unit.

**Stack.** Python, MCP SDK, systemd service, pyproject packaging.

**What it demonstrates.**
- MCP server engineering (tool/context exposure for AI agents).
- Agent-tool integration with a documented architecture.

**Status.** Built; internal tooling.

**Source.** `~/projects/dealership-mcp/` (`dealership_mcp/`, `server.py`, `dealership-mcp.service`).
