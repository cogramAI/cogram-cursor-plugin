# Cogram for Cursor

<img src="assets/logo.png" alt="Cogram" width="72" align="right">

Connect Cursor's agent to [Cogram](https://cogram.com), the AI platform for architects and engineers.

The Cogram MCP server gives the agent read-only access to your firm's project record: projects, meetings, email, documents, RFIs, submittals, transmittals, drawings and field reports.

## What it can do

- Search and read across your Cogram projects, meetings, email, documents, RFIs, submittals, transmittals, drawings and field reports
- **Read-only.** The agent can search, read and summarise. It cannot create, change or delete anything in Cogram.
- **Your permissions apply.** The agent sees exactly what your Cogram account can see, and nothing more.

## Setup

1. Install the plugin from the Cursor Marketplace.
2. The first time Cursor connects, sign in with your Cogram account. There are no API keys to configure.

A Cogram account is required.

## Details

| | |
|---|---|
| Endpoint | `https://mcp.cogram.com/mcp` |
| Transport | Streamable HTTP |
| Authentication | OAuth 2.1 with dynamic client registration |
| Access | Read-only |
| Rate limit | 50 requests per minute per connected application |

Full documentation: [docs.cogram.com/integrations/mcp-server](https://docs.cogram.com/integrations/mcp-server)

## About this repository

This repository holds only the plugin listing for the Cursor Marketplace. The Cogram MCP server is a hosted service, and its source code is not part of this repository.
