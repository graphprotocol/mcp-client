# MCP Client: `@graphprotocol/mcp`

[![.github/workflows/bun-test.yml](https://github.com/graphprotocol/mcp-client/actions/workflows/bun-test.yml/badge.svg)](https://github.com/graphprotocol/mcp-client/actions/workflows/bun-test.yml)
![license](https://img.shields.io/github/license/graphprotocol/mcp-client)

> An MCP Client for connecting to MCP Server‐compatible services at https://thegraph.market.

```console
Usage: @graphprotocol/mcp [options]

An MCP Client for connecting to MCP Server‐compatible services at https://thegraph.market.

Options:
  -V, --version            output the version number
  --sse-url <string>       Server-Sent Events (SSE) url (env: SSE_URL)
  --access-token <string>  JWT Access Token from https://thegraph.market (env: ACCESS_TOKEN)
  -v, --verbose <boolean>  Enable verbose logging (choices: "true", "false", default: false, env: VERBOSE)
  -h, --help               display help for command
```

## Authentication

1. Create a free account at https://thegraph.market using your GitHub credentials as login.
2. Go to **Dashboard**
3. **Create New Key**
4. **Generate Access Token**

## `.env`

```env
ACCESS_TOKEN=<https://thegraph.market JWT Access Token>
SSE_URL=https://token-api.mcp.thegraph.com/sse
```

<img width="896" alt="Image" src="https://github.com/user-attachments/assets/43c0e662-5e30-4b7d-87a0-884d6105b6a3" />

## Supported by AI Agents

- [Claude Desktop](https://thegraph.com/docs/en/token-api/mcp/claude/)
- [Cline](https://thegraph.com/docs/en/token-api/mcp/cline/)
- [Cursor](https://thegraph.com/docs/en/token-api/mcp/cursor/)
