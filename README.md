Install this MCP server by adding the following JSON code to your JSON config file

```json
{
  "mcpServers": {
    "server": {
      "command": "uv",
      "args": [
        "--from",
        "git+https://github.com/santoshbt/chessscore.git",
        "chess"
      ]
    }
  }
}
```