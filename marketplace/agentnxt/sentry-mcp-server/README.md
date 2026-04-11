# Sentry MCP Server (Cloud)

Cloud-hosted MCP server for Sentry — error tracking, issues, events, releases, and performance.

**Type:** Remote (SSE / Streamable HTTP)
**Service Provider:** [Sentry](https://sentry.io)
**Integration Author:** [AgentNxt](https://github.com/agentnxt)

## Endpoint

| Transport | URL |
|-----------|-----|
| SSE | `https://mcp.sentry.dev/sse` |
| Streamable HTTP | `https://mcp.sentry.dev/mcp` |

## Authentication

| Method | Details |
|--------|---------|
| OAuth | Connect via Sentry account |

## Tools

- List and search issues
- Get issue events and stacktraces
- Manage releases
- Query performance data
- Resolve/ignore issues

## Gateway Registration

```json
{
  "cloud-sentry": {
    "type": "SSE",
    "url": "https://mcp.sentry.dev/sse",
    "description": "Sentry — error tracking, issues, events, releases, performance"
  }
}
```

## License

Integration authored by AgentNxt. Sentry is a trademark of Functional Software, Inc.
