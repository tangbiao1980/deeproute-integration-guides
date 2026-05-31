## OpenAI Python SDK

```python
from openai import OpenAI
client = OpenAI(base_url="https://deeproute-api.duckdns.org/v1", api_key="sk-your-key")
response = client.chat.completions.create(model="deepseek-v4-flash", messages=[{"role": "user", "content": "Hello!"}])
print(response.choices[0].message.content)
```
