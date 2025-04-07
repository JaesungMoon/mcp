# MCP

from

[話題のClaude新機能！Model Context Protocolについて解説してみた](https://youtu.be/47EtOViVJ1c?si=V-g-Xw84XAFsFWuw)

<https://modelcontextprotocol.io/introduction>

## claude

with desktop
`/Users/{{user_name}}/Library/Application Support/Claude/claude_desktop_config.json`

<https://modelcontextprotocol.io/introduction> url was updated. then, using below site.
<https://www.claudemcp.com/docs/quickstart>

```marmaid
graph LR subgraph Your Computer A[Claude Desktop] <-->|MCP Protocol (Query and Result)| B(SQLite MCP Server) B <-->|Local Access (SQL Operation)| C[(SQLite Database ~/test.db)] end
```
