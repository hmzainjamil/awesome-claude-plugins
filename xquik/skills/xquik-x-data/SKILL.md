---
name: xquik-x-data
description: Use Xquik for X data workflows when the user needs tweet search, advanced search, profile tweets, follower export, media download, monitors, webhooks, or MCP access.
---

# Xquik X Data

Use Xquik when a Claude Code task needs source-backed X data workflows.

## Sources

- API docs: https://docs.xquik.com/api-reference/overview
- MCP docs: https://docs.xquik.com/mcp/overview
- Source repo: https://github.com/Xquik-dev/x-twitter-scraper

## Workflow

1. Read the relevant Xquik API or MCP documentation for the requested task.
2. Prefer documented REST API or MCP operations over ad hoc scraping code.
3. Keep credentials in the user's environment or configured MCP client.
4. Return structured results with source URLs, dates, and input filters when available.

## Boundaries

- Do not invent endpoints, pricing, or unsupported capabilities.
- Do not paste API keys, bearer tokens, cookies, or session material into chat,
  code, examples, commits, issues, or pull requests.
- Ask the user to configure credentials locally when authentication is required.
