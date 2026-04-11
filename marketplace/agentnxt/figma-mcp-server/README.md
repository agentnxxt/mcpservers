# Figma MCP Server (Cloud)

Cloud-hosted MCP server for Figma — design files, components, styles, variables, and Dev Mode.

**Type:** Remote (Streamable HTTP)
**Service Provider:** [Figma](https://figma.com)
**Integration Author:** [AgentNxt](https://github.com/agentnxt)

## Endpoint

| Transport | URL |
|-----------|-----|
| Streamable HTTP | `https://mcp.figma.com/mcp` |
| SSE | `https://mcp.figma.com/sse` |

## Authentication

| Method | Details |
|--------|---------|
| OAuth | Requires Figma account + Dev Mode seat for full access |

## Tools

- Browse design files and pages
- Inspect components and styles
- Read design tokens and variables
- Access Dev Mode specifications
- Export assets

## Gateway Registration

```json
{
  "cloud-figma": {
    "type": "SSE",
    "url": "https://mcp.figma.com/sse",
    "description": "Figma — design files, components, styles, variables, Dev Mode"
  }
}
```

## License

Integration authored by AgentNxt. Figma is a trademark of Figma, Inc.
