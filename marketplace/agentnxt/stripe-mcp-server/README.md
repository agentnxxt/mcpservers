# Stripe MCP Server (Cloud)

Cloud-hosted MCP server for Stripe — payments, customers, subscriptions, invoices, and products.

**Type:** Remote (SSE / Streamable HTTP)
**Service Provider:** [Stripe](https://stripe.com)
**Integration Author:** [AgentNxt](https://github.com/agentnxt)

## Endpoint

| Transport | URL |
|-----------|-----|
| SSE | `https://mcp.stripe.com/sse` |
| Streamable HTTP | `https://mcp.stripe.com/mcp` |

## Authentication

| Method | Details |
|--------|---------|
| OAuth | Connect via Stripe account |

## Tools

- List and manage payments
- Customer CRUD operations
- Subscription management
- Invoice creation and retrieval
- Product and price management

## Gateway Registration

```json
{
  "cloud-stripe": {
    "type": "SSE",
    "url": "https://mcp.stripe.com/sse",
    "description": "Stripe — payments, customers, subscriptions, invoices, products"
  }
}
```

## License

Integration authored by AgentNxt. Stripe is a trademark of Stripe, Inc.
