# Atoll (Cursor / Grok Bot plugin)

Official-intent marketplace pack for [Atoll](https://atollhq.com). Same hosted MCP as the ChatGPT plugin under review.

- MCP: `https://atollhq.com/mcp` (Streamable HTTP)
- OAuth PRM: `https://atollhq.com/.well-known/oauth-protected-resource`
- Docs: https://docs.atollhq.com/integrations/mcp-server
- Privacy: https://atollhq.com/legal/privacy
- Terms: https://atollhq.com/legal/terms
- Support: https://atollhq.com/support

This repository is source-only (no binaries). The MCP server runs on Atoll's host; this pack is the client plugin (manifest, MCP URL, skill).

## Install (local, unpublished)

Copy this folder to `~/.cursor/plugins/local/atoll` and reload Cursor. Complete OAuth when the connector prompts.

Grok Bot uses the same Cursor plugin/MCP policy. Do not use localhost MCP with Grok Bot.

## What it does

Heartbeat, projects, issues, comments, goals, KPIs, initiatives, milestones, and a narrow write surface. Actor-dependent tools run as an Atoll agent profile selected at consent.

## Configuration

No API key in this package. OAuth only for the public plugin profile.
