# Claude Code adds support for remote MCP servers

- **Date:** 2025-06-18
- **Who:** Anthropic
- **Type:** software

Anthropic added support for remote Model Context Protocol servers to Claude Code, using SSE and HTTP transports. OAuth 2.0 sign-in for remote servers works through the /mcp command, and MCP resources can be referenced in prompts with @-mentions. This lets coding agents reach hosted tools and data without a local server.

## Sources
- https://docs.anthropic.com/en/release-notes/claude-code
- https://www.anthropic.com/news/claude-code-remote-mcp
