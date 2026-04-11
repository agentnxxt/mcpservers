# Linear MCP Server (Cloud)

Cloud-hosted MCP server for Linear — issues, projects, cycles, teams, and labels.

**Type:** Remote (Streamable HTTP)
**Service Provider:** [Linear](https://linear.app)
**Integration Author:** [AgentNxt](https://github.com/agentnxt)

## Endpoint

| Transport | URL |
|-----------|-----|
| Streamable HTTP | `https://mcp.linear.app/mcp` |
| SSE | `https://mcp.linear.app/sse` |

## Authentication

| Method | Details |
|--------|---------|
| OAuth | Connect via Linear account |
| API Key | `Authorization: Bearer {api-key}` (also supported) |

## Tools

- Create, update, and search issues
- Manage projects and cycles
- List teams and members
- Apply and manage labels
- Track issue status

## Gateway Registration

```json
{
  "cloud-linear": {
    "type": "SSE",
    "url": "https://mcp.linear.app/sse",
    "description": "Linear — issues, projects, cycles, teams, labels"
  }
}
```

## License

Integration authored by AgentNxt. Linear is a trademark of Linear Orbit, Inc.
