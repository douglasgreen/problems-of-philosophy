## Web Search with TinyFish

When searching the web using TinyFish in OpenCode, adhere strictly to the invocation formats below. Do not guess parameter names.

---

### 1. Via MCP Tool (`search` or `tinyfish__search`)

When invoking the TinyFish MCP tool, always pass a single JSON object.

#### Parameter Schema
* **`query`** (`string`, **required**): The search keywords. 
* **`purpose`** (`string`, *optional*): A short description of what task the results will be used for (helps result ranking).
* **`location`** (`string`, *optional*): 2-letter ISO country code (e.g., `"US"`).
* **`language`** (`string`, *optional*): 2-letter ISO code (e.g., `"en"`).
* **`recency_minutes`** (`integer`, *optional*): E.g., `1440` for past 24 hours. (Do **not** combine with `after_date`).

#### Correct Example
```json
{
  "query": "OpenCode MCP configuration guide",
  "purpose": "Find official setup steps for remote MCP tools"
}
