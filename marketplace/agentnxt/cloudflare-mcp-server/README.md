# Cloudflare MCP Server (Cloud)

Cloud-hosted MCP server for Cloudflare — Workers, KV, R2, D1, DNS, analytics, and observability.

**Type:** Remote (SSE / Streamable HTTP)
**Service Provider:** [Cloudflare](https://cloudflare.com)
**Integration Author:** [AgentNxt](https://github.com/agentnxt)

## Endpoint

| Transport | URL |
|-----------|-----|
| SSE | `https://mcp.cloudflare.com/sse` |
| Streamable HTTP | `https://mcp.cloudflare.com/mcp` |

### Product-Specific Endpoints

| Product | URL |
|---------|-----|
| Observability | `https://observability.mcp.cloudflare.com/sse` |
| Bindings | `https://bindings.mcp.cloudflare.com/sse` |

## Authentication

| Method | Details |
|--------|---------|
| OAuth | Connect via Cloudflare account |

## Tools

- Manage Workers (deploy, update, delete)
- KV namespace operations
- R2 bucket and object management
- D1 database queries
- DNS record management
- Analytics and observability

## Gateway Registration

```json
{
  "cloud-cloudflare": {
    "type": "SSE",
    "url": "https://mcp.cloudflare.com/sse",
    "description": "Cloudflare — Workers, KV, R2, D1, DNS, analytics"
  }
}
```

## License

Integration authored by AgentNxt. Cloudflare is a trademark of Cloudflare, Inc.
