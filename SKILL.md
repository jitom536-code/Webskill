---
name: Web Search
description: Search the web to get real-time or current information using Tavily API.
---
# Web Search

## Instructions
If the user asks for real-time information, current events, or facts you do not know, use the `run_js` tool.
Parameters:
- **script name**: `index.html`
- **data**: A JSON string containing the search query: `{"query": "<search query>"}`

**Factual Accuracy Guidelines:**
- Strictly copy all names, years, dates, and numbers exactly as they appear in the search results.
- Do not modify, guess, or drop any digits (e.g., do not write '8th' if the source says '98th').
- If the search results are empty or unclear, state that you do not know instead of hallucinating.
