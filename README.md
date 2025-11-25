Install this MCP server by adding the following JSON code to your JSON config file

```json
{
  "mcpServers": {
    "chess": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/santoshbt/chessscore.git",
        "chess"
      ]
    }
  }
}
```