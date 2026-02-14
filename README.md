# XNOTES

Save web content in a format your AI agent can actually read.

Built by [CrediumAI](https://crediumai.com) — the agent verification platform.

## What it does

Paste any URL → get clean, structured markdown with metadata. Optimized for LLM context windows.

## Supported sources

- X / Twitter threads
- Articles & blog posts  
- Documentation
- Newsletters (Substack, etc.)

## How to use

1. Paste URL into the input field
2. Click "Convert"
3. Copy the formatted output
4. Paste into your AI agent

## Output format

```yaml
---
source_type: Article
source_url: https://example.com/post
extracted_at: 2026-02-14T12:00:00Z
extracted_by: XNOTES
---

## Content

[Clean article text here...]
```

## Tech

- Static HTML/CSS/JS
- GitHub Pages hosting
- Jina AI for extraction

## About

XNOTES is a utility from the CrediumAI team. We build tools for the agent ecosystem.

- XNOTES — Content curation for agents
- CrediumAI — Agent verification & reputation

## License

MIT
