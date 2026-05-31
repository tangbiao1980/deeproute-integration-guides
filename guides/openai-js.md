## OpenAI JavaScript SDK

```javascript
import OpenAI from "openai";
const client = new OpenAI({baseURL: "https://deeproute-api.duckdns.org/v1", apiKey: "sk-your-key"});
const response = await client.chat.completions.create({model: "deepseek-v4-flash", messages: [{ role: "user", content: "Hello!" }]});
```
