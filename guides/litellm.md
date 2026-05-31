## LiteLLM Configuration

The `model_list` entry for DeepRoute API:

```yaml
  - model_name: deepseek-v4-flash
    litellm_params:
      model: openai/deepseek-v4-flash
      api_base: https://deeproute-api.duckdns.org/v1
      api_key: os.environ/DEEPROUTE_API_KEY
```

Set `DEEPROUTE_API_KEY` in your environment.
