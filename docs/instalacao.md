# Instalação detalhada

Tribunal TJPA: Certidão Criminal é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tribunal_tjpa_cert_criminal`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tribunal_tjpa_cert_criminal` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tribunal_tjpa_cert_criminal` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tribunal_tjpa_cert_criminal` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tribunal_tjpa_cert_criminal` (ou `servers.tribunal_tjpa_cert_criminal` no VS Code) do config do cliente e reinicie.
