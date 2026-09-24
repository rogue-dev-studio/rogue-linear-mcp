# rogue-linear-mcp

**Rogue Development** MCP package for agents.

Rogue Linear MCP - remote issue tracking tools for agents

- Asset Store: https://rogue-dev-studio.github.io/rogue-asset-store/

## Requirements

- MCP host with remote HTTP MCP support
- Linear workspace access

## Install (Cursor)

Copy `cursor.mcp.fragment.json` into your Cursor MCP config, or merge:

```json
{
  "mcpServers": {
    "linear": {
      "url": "https://mcp.linear.app/mcp"
    }
  }
}
```

Then restart Cursor.

## License

MIT - Rogue Development. See `LICENSE` and `NOTICE`.
