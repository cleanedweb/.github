<p align="center"><img src="https://cleanedweb.com/assets/logo.png" width="72" alt="CleanedWeb"></p>

<h3 align="center">Public websites as maintained REST APIs</h3>

<p align="center">
CleanedWeb turns website collections (listings, products, jobs, articles, profiles) into versioned APIs that return structured records, and keeps them working when the site changes.
</p>

<p align="center">
<a href="https://cleanedweb.com/?utm_source=github&utm_medium=org-profile">Website</a> ·
<a href="https://cleanedweb.com/catalog/?utm_source=github&utm_medium=org-profile">API catalog</a> ·
<a href="https://cleanedweb.com/docs/?utm_source=github&utm_medium=org-profile">Docs</a> ·
<a href="https://cleanedweb.com/pricing/?utm_source=github&utm_medium=org-profile">Pricing</a>
</p>

---

**Use it from**

| | |
| --- | --- |
| AI agents (Claude, ChatGPT, Cursor, VS Code, Codex, Gemini CLI) | [cleanedweb-mcp](https://github.com/cleanedweb/cleanedweb-mcp): hosted MCP server |
| Python | [cleanedweb-python](https://github.com/cleanedweb/cleanedweb-python): `pip install git+https://github.com/cleanedweb/cleanedweb-python` (PyPI soon) |
| JavaScript / TypeScript | [cleanedweb-js](https://github.com/cleanedweb/cleanedweb-js) (npm soon) |
| LangChain · LlamaIndex | [langchain-cleanedweb](https://github.com/cleanedweb/langchain-cleanedweb) · [llama-index-tools-cleanedweb](https://github.com/cleanedweb/llama-index-tools-cleanedweb) |
| n8n workflows | [n8n-nodes-cleanedweb](https://github.com/cleanedweb/n8n-nodes-cleanedweb) |
| GitHub Actions | [run-api-action](https://github.com/cleanedweb/run-api-action): run an API on a schedule and commit the records |
| Examples | [cleanedweb-examples](https://github.com/cleanedweb/cleanedweb-examples): price monitor, job aggregator, deal finder, agent demo |

**Quick start**

```bash
curl -s https://app.cleanedweb.com/api/catalog/apis | head -c 600   # browse the catalog, no key needed
```

Add `https://api.cleanedweb.com/mcp?profile=catalog` to your AI client as a remote MCP server, or create an API key in the [console](https://app.cleanedweb.com/?utm_source=github&utm_medium=org-profile) and call the REST API.

5,000 records free once, then prepaid from $1 per 1,000 records. No subscription.
