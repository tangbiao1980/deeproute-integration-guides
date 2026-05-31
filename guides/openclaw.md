# OpenClaw Configuration

Add this to `~/.openclaw/openclaw.json`:

```json
{
  "models": {
    "providers": {
      "deeproute": {
        "baseUrl": "https://deeproute-api.duckdns.org/v1",
        "apiKey": "${DEEPROUTE_API_KEY}",
        "api": "openai-completions",
        "models": [
          {"id": "deepseek-v4-flash", "name": "DeepSeek V4 Flash", "cost": {"input": 0.00000016, "output": 0.00000032}},
          {"id": "deepseek-chat", "name": "DeepSeek Chat", "cost": {"input": 0.00000016, "output": 0.00000032}},
          {"id": "deepseek-reasoner", "name": "DeepSeek R1", "cost": {"input": 0.00000063, "output": 0.00000252}},
          {"id": "qwen3.6-flash", "name": "Qwen3.6 Flash", "cost": {"input": 0.00000030, "output": 0.00000179}}
        ]
      }
    }
  }
}
```

Get your free API key at [deeproute-api.duckdns.org/register](https://deeproute-api.duckdns.org/register)
