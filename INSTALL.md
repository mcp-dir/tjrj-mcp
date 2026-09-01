# Instalação rápida

Jurisprudência TJRJ é um servidor MCP remoto hospedado em `https://api.mcp.ai/p_tjrj`. Você não baixa nem roda nada localmente — só aponta seu cliente pra essa URL.

Este MCP é **grátis e sem login** pra uso básico — funciona assim que você instala. (Login opcional via `app.mcp.ai` só dá limites maiores / histórico.)

---

## Claude (Web e Desktop)

[➕ Abrir no Claude e conectar](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

Manual: [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Adicionar conector personalizado** → `Jurisprudência TJRJ` / `https://api.mcp.ai/p_tjrj`.

Config file (legado): `~/Library/Application Support/Claude/claude_desktop_config.json` (macOS) ou `%APPDATA%\Claude\claude_desktop_config.json` (Windows):

```json
{ "mcpServers": { "tjrj": { "type": "http", "url": "https://api.mcp.ai/p_tjrj" } } }
```

## Cursor

[➕ Instalar no Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=tjrj&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF90anJqIn0=)

`.cursor/mcp.json`:
```json
{ "mcpServers": { "tjrj": { "url": "https://api.mcp.ai/p_tjrj" } } }
```

## VS Code (Copilot Chat)

[➕ Instalar no VS Code](vscode:mcp/install?name=tjrj&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_tjrj%22%7D)

`.vscode/mcp.json`:
```json
{ "servers": { "tjrj": { "type": "http", "url": "https://api.mcp.ai/p_tjrj" } } }
```

## Outros clientes MCP

Qualquer cliente com **MCP over HTTP**. URL fixa:

```
https://api.mcp.ai/p_tjrj
```

Dúvidas? [tjrj@mcp.ai](mailto:tjrj@mcp.ai)
