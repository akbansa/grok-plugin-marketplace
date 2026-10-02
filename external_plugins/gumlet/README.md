# Gumlet plugin for Grok Build

Connect Grok Build to Gumlet's video workspaces, assets, live streams, and
insights through Gumlet's hosted MCP server.

## Installation

In Grok Build, open `/plugin`, search for **Gumlet**, and install.

## Authentication

The plugin connects to `https://mcp.gumlet.com/mcp/v1` over HTTP and uses
OAuth with the `gumlet.mcp` scope. Authorize with your Gumlet account when
prompted; no API key or client secret is stored in this plugin.

For setup details, see [Gumlet's MCP documentation](https://docs.gumlet.com/resources/mcp).
