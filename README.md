# Deacon Cursor plugins

Cursor marketplace for Deacon Construction's hosted MCP servers, each packaged with the Deacon D icon.

| Plugin | Server |
| --- | --- |
| `deacon-procore-mcp` | `https://procore-mcp.deacon.build/mcp` |
| `deacon-buildingconnected-mcp` | `https://bc-mcp.deacon.build/mcp` |

This repo is public so Cursor, including cloud agents, can fetch it without GitHub credentials. It holds only plugin names, server URLs and the logo: no credentials, no server code. Each user signs in to the servers with their own Deacon account.

## Install

Import `https://github.com/curmorpheus/deacon-cursor-plugins` into the Cursor team marketplace, then remove the old per-repo imports so no client has duplicate connections.

## Add a plugin

Add `plugins/<name>/` with `.cursor-plugin/plugin.json`, `mcp.json` and `assets/deacon-mark-navy.svg`, then list it in `.cursor-plugin/marketplace.json`.
