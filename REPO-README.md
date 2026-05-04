# 🇮🇳 India Jobs MCP — by Ateshh

> The first MCP server built specifically for the Indian job market.
> Real-time job listings, salary benchmarks, and market insights — all in one place.

![License](https://img.shields.io/badge/license-MIT-blue)
![Node](https://img.shields.io/badge/node-%3E%3D18-green)
![MCP](https://img.shields.io/badge/MCP-compatible-orange)

---

## What is this?

**India Jobs MCP** is a Model Context Protocol server that lets AI assistants (like Claude) search and analyze Indian job market data in real time.

Built by **Ateshh** — domain trader turned AI builder 🚀

---

## Features

- 🔍 **Real-time job search** across India via JSearch API
- 💰 **Salary benchmarks** for 8+ popular roles in LPA
- 🏙️ **City intelligence** — which cities hire most for your role
- 📊 **Market insights** — India 2026 job trends
- 🖥️ **Web dashboard** — beautiful UI, no install needed

---

## MCP Tools

| Tool | Description |
|------|-------------|
| `search_india_jobs` | Search jobs by role + city |
| `get_salary_benchmark` | Salary ranges in LPA |
| `get_top_cities_for_role` | Best cities for a role |
| `browse_job_categories` | Tech / Finance / Media / Sales |
| `get_market_insights` | India 2026 job market trends |

---

## Quick Start

### 1. Get Free API Key
Sign up at [RapidAPI JSearch](https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch) — 500 free requests/month

### 2. Install & Run
```bash
cd mcp
npm install
JSEARCH_API_KEY=your_key node server.js
```

### 3. Connect to Claude Desktop
Add to your Claude Desktop config:

**Mac:** `~/Library/Application Support/Claude/claude_desktop_config.json`
**Windows:** `%APPDATA%\Claude\claude_desktop_config.json`

```json
{
  "mcpServers": {
    "india-jobs": {
      "command": "node",
      "args": ["/path/to/india-jobs-mcp/mcp/server.js"],
      "env": {
        "JSEARCH_API_KEY": "your_rapidapi_key"
      }
    }
  }
}
```

Restart Claude Desktop — your 5 tools appear automatically!

### 4. Open Dashboard
Just open `dashboard/index.html` in any browser. No server needed.

---

## Deploy Dashboard Free

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start)

Drag `dashboard/index.html` to [netlify.com/drop](https://app.netlify.com/drop) — live in 30 seconds.

---

## Deploy MCP Server

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app)

1. Push this repo to GitHub
2. Connect Railway to your repo
3. Set `JSEARCH_API_KEY` as environment variable
4. Deploy ✅

---

## Roadmap

- [ ] Naukri.com integration
- [ ] LinkedIn Jobs India filter
- [ ] Hindi language support
- [ ] WhatsApp bot integration
- [ ] Rural India jobs focus (KST partnership)
- [ ] Salary negotiation AI tool

---

## Pricing / API Access

Want hosted API access without running it yourself?

📧 Email: ateshh.s@gmail.com  
💬 WhatsApp: +91 9699711712

---

## Built by Ateshh

From domain trading (2009) → MCP servers (2026) 🎯

If this helped you, give it a ⭐ on GitHub!

---

## License

MIT — free to use, modify, and distribute.
