# Netlify MCP Server (Cloud)

Cloud-hosted MCP server for Netlify — sites, deploys, builds, DNS, forms, and serverless functions.

**Type:** Remote (Streamable HTTP)
**Service Provider:** [Netlify](https://netlify.com)
**Integration Author:** [AgentNxt](https://github.com/agentnxt)

## Endpoint

| Transport | URL |
|-----------|-----|
| Streamable HTTP | `https://netlify-mcp.netlify.app/mcp` |
| SSE | `https://netlify-mcp.netlify.app/sse` |

## Authentication

| Method | Details |
|--------|---------|
| OAuth 2.1 | Connect via Netlify account |

## Tools

- List and manage sites
- Trigger and monitor deploys
- View build logs
- Manage DNS records
- Access form submissions
- Configure serverless functions

## Gateway Registration

```json
{
  "cloud-netlify": {
    "type": "SSE",
    "url": "https://netlify-mcp.netlify.app/sse",
    "description": "Netlify — sites, deploys, builds, DNS, forms, serverless functions"
  }
}
```

## License

Integration authored by AgentNxt. Netlify is a trademark of Netlify, Inc.
