# Instalação detalhada

Jurisprudência TJRJ é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tjrj`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tjrj` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tjrj` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tjrj` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tjrj` (ou `servers.tjrj` no VS Code) do config do cliente e reinicie.
