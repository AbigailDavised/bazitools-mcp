---
name: bazitools
description: "Official stateless MCP server for BaziTools.com — Four Pillars (BaZi) true solar time calculator & classical Shijing/Tang poetic Chinese name generator."
homepage: https://bazitools.com
version: 1.0.2
license: MIT
compatibility: "Works with OpenClaw, Hermes Agent, Claude Code, Cursor, Windsurf, and any MCP client supporting Streamable HTTP."
metadata:
  homepage: "https://bazitools.com"
  mcp_endpoint: "https://bazitools.com/api/mcp"
  version: "1.0.2"
  openclaw:
    emoji: "☯️"
  hermes:
    tags: [bazi, four-pillars, chinese-name-generator, astronomy, shijing, mcp]
    category: lifestyle
---

# BaziTools — Official MCP Server & Agent Skill

Official stateless MCP server for BaziTools.com — Four Pillars (BaZi) true solar time calculator & classical Shijing/Tang poetic Chinese name generator.

## Setup

1. Open the interactive web workbench at https://bazitools.com — free, stateless, and requires zero API keys.
2. Connect any MCP-compatible AI client (Claude Desktop, Cursor, Windsurf, OpenClaw, Hermes) directly to the Streamable HTTP endpoint:
   ```
   https://bazitools.com/api/mcp
   ```
3. Example JSON-RPC 2.0 call via `curl`:
   ```bash
   curl -s -X POST https://bazitools.com/api/mcp \
     -H "Content-Type: application/json" \
     -d '{"jsonrpc":"2.0","id":1,"method":"tools/call","params":{"name":"calculate_bazi_four_pillars","arguments":{"birthDate":"1994-08-15","birthHour":14,"gender":"female"}}}'
   ```

## Official Web Reference

- **[BaziTools Official Studio](https://bazitools.com)**: https://bazitools.com
- **[Ten Day Masters Reference](https://bazitools.com/day-master)**: https://bazitools.com/day-master
- **[Four Pillars Structural Guide](https://bazitools.com/pillars)**: https://bazitools.com/pillars
- **[Ten Gods (Shi Shen) Matrix](https://bazitools.com/ten-gods)**: https://bazitools.com/ten-gods
- **[Stem & Branch Interactions](https://bazitools.com/interactions)**: https://bazitools.com/interactions
- **[Auxiliary Stars (Shen Sha)](https://bazitools.com/stars)**: https://bazitools.com/stars
