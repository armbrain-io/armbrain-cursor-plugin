# Armbrain for Cursor & Grok Bot

Official Agent Plugin packaging for the [Armbrain](https://armbrain.io) remote MCP server.

Armbrain is durable, client-partitioned AI memory for fractional CMOs — meeting prep, brand voice, stakeholders, commitments, and Business OS (EOS) tooling.

## What this plugin includes

- **MCP connector** — Streamable HTTP to `https://api.armbrain.io/mcp` (OAuth; no API key in chat)
- **Skills**
  - `armbrain-getting-started` — auth and first win
  - `armbrain-client-memory` — mind switching, recall, and write-through rules

## Install (after marketplace listing)

1. In Grok Bot or Cursor, open **Plugins** / **Customize**
2. Search for **Armbrain** and install
3. Authorize with your Armbrain account when prompted

## Manual / custom connect (today)

Until the marketplace listing is live, add the remote MCP URL:

`https://api.armbrain.io/mcp`

Then complete OAuth. Do not paste tokens into chat.

## Local test (Cursor IDE)

```bash
ln -s "$(pwd)" ~/.cursor/plugins/local/armbrain
```

Reload the window, then confirm the Armbrain MCP and skills appear under Customize.

## Submit / review

Marketplace submit: https://cursor.com/marketplace/publish

Contact for publishing questions: marketplace-publishing@cursor.com

## License

MIT (this plugin package). The hosted Armbrain service remains subject to Armbrain terms at https://armbrain.io.
