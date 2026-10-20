# Model Context Protocol specification 2025-06-18 released

- **Date:** 2025-06-18
- **Who:** Model Context Protocol maintainers (Anthropic-led open standard)
- **Type:** software

The 2025-06-18 revision of the MCP spec removed JSON-RPC batching, added structured tool output and resource links in tool results, and added elicitation so servers can ask users for input. It treats MCP servers as OAuth Resource Servers and requires RFC 8707 resource indicators. It mattered because the auth and structured-output changes shaped how remote tool servers were built and secured.

## Sources
- https://modelcontextprotocol.io/specification/2025-06-18/changelog
- https://community.auth0.com/t/model-context-protocol-mcp-spec-updates-from-june-2025-one-small-step-for-a-spec-one-giant-leap-for-security/188468
