# Instalação detalhada

DETRAN RJ: Nada Consta - Veículo Apreendido é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_detran_rj_veiculo_apreendido`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_detran_rj_veiculo_apreendido` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_detran_rj_veiculo_apreendido` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_detran_rj_veiculo_apreendido` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.detran_rj_veiculo_apreendido` (ou `servers.detran_rj_veiculo_apreendido` no VS Code) do config do cliente e reinicie.
