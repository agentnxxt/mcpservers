# Slack MCP Server (Cloud)

Cloud-hosted MCP server for Slack — channels, messages, users, reactions, and files.

**Type:** Remote (Streamable HTTP only)
**Service Provider:** [Slack](https://slack.com)
**Integration Author:** [AgentNxt](https://github.com/agentnxt)

## Endpoint

| Transport | URL |
|-----------|-----|
| Streamable HTTP | `https://mcp.slack.com/mcp` |
| SSE | `https://mcp.slack.com/sse` |

> **Note:** Slack uses Streamable HTTP only — no SSE support, no Dynamic Client Registration.

## Authentication

| Method | Details |
|--------|---------|
| OAuth | Requires a registered Slack app with client ID |

## Tools

- List channels and members
- Read and send messages
- Manage reactions
- Upload and list files
- Search messages

## Gateway Registration

```json
{
  "cloud-slack": {
    "type": "SSE",
    "url": "https://mcp.slack.com/sse",
    "description": "Slack — channels, messages, users, reactions, files"
  }
}
```

## License

Integration authored by AgentNxt. Slack is a trademark of Slack Technologies, LLC.
