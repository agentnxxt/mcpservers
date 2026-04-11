# Notion MCP Server (Cloud)

Cloud-hosted MCP server for Notion — workspaces, pages, databases, search, and comments.

**Type:** Remote (SSE / Streamable HTTP)
**Service Provider:** [Notion](https://notion.so)
**Integration Author:** [AgentNxt](https://github.com/agentnxt)

## Endpoint

| Transport | URL |
|-----------|-----|
| SSE | `https://mcp.notion.com/sse` |
| Streamable HTTP | `https://mcp.notion.com/mcp` |

## Authentication

| Method | Details |
|--------|---------|
| OAuth 2.1 | Connect via Notion integration |

## Tools

- Search pages and databases
- Read/create/update pages
- Query databases
- Manage comments
- Access workspace metadata

## Gateway Registration

```json
{
  "cloud-notion": {
    "type": "SSE",
    "url": "https://mcp.notion.com/sse",
    "description": "Notion — workspaces, pages, databases, search, comments"
  }
}
```

## License

Integration authored by AgentNxt. Notion is a trademark of Notion Labs, Inc.
