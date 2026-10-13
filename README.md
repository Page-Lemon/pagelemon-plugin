# Page Lemon plugin

Publish websites from your AI and keep editing them: live links, version history, forms, bookings, private pages and custom domains. [pagelemon.com](https://pagelemon.com)

This repo packages the Page Lemon MCP server (`https://mcp.pagelemon.com`) and one skill (`skills/page-lemon`) for each AI client. Sign in to Page Lemon when your client asks.

## ChatGPT

Search for **Page Lemon** in ChatGPT's plugin directory. Nothing to install from here.

## Codex

```sh
codex plugin marketplace add Page-Lemon/pagelemon-plugin
codex plugin add pagelemon@pagelemon
```

## Claude Code

```
/plugin marketplace add Page-Lemon/pagelemon-plugin
/plugin install pagelemon@pagelemon
```

On claude.ai or Claude Desktop, add `https://mcp.pagelemon.com` as a custom connector instead.

## Cursor

Install **Page Lemon** from the Cursor Marketplace, or add this repo as a plugin source: `https://github.com/Page-Lemon/pagelemon-plugin`.

## Gemini CLI

```sh
gemini extensions install https://github.com/Page-Lemon/pagelemon-plugin
```

## VS Code / GitHub Copilot

Run **Chat: Install Plugin From Source** and enter `https://github.com/Page-Lemon/pagelemon-plugin`.

## Any other MCP client

Add the remote server `https://mcp.pagelemon.com` (streamable HTTP, OAuth). Guide: [pagelemon.com/agents](https://pagelemon.com/agents).

## Files

| File | Read by |
|---|---|
| `plugin.json`, `mcp.json` | ChatGPT and Codex (Agent Plugins format) |
| `.agents/plugins/marketplace.json` | Codex marketplace |
| `.claude-plugin/`, `.mcp.json` | Claude Code, VS Code |
| `.cursor-plugin/`, `.mcp.json` | Cursor |
| `gemini-extension.json` | Gemini CLI |
| `skills/page-lemon/SKILL.md` | All clients |
| `assets/` | Page Lemon icon |

[Privacy](https://pagelemon.com/privacy) · [Terms](https://pagelemon.com/terms) · [Support](https://pagelemon.com/support)
