# Awesome Grok Bot [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of high-quality Grok Bot templates, skills, plugins, and tools.

[Grok Bot](https://docs.x.ai/grok-bot/overview) is xAI's always-on teammate with its own persistent cloud computer. This list is unofficial and not affiliated with xAI.

**Curation, not a dump.** Listed only with a primary source (official docs, repo, or `x.ai/bot` share link) and a clear one-job scope.

## Contents

- [Official](#official)
- [Templates](#templates)
- [Skills](#skills)
- [Plugins and MCP](#plugins-and-mcp)
- [Engineering](#engineering)
- [Tools](#tools)
- [Runtimes](#runtimes)
- [Guides](#guides)

## Official

- [Grok Bot](https://x.ai/bot) - Create, share, and run Grok Bot teammates.
- [Overview](https://docs.x.ai/grok-bot/overview) - Official product model: persistent VM, shared computer, routines, approval gates.
- [Guides](https://x.ai/bot/guides) - Official setup and use-case walkthroughs.
- [plugin-marketplace](https://github.com/xai-org/plugin-marketplace) - Official plugin index and `.grok-plugin` manifest format.
- [X plugin](https://x.ai/bot/plugin/49086599) - Official X connector for search, timelines, and mentions.

## Templates

One job. Draft or wait for approval.

- [Loops](https://x.ai/bot/Ub3T7usX-c6yRQibQq83P) - Engineering outer loop: gather, prompt, review, merge with testable proof.
- [Chief of Staff](https://x.ai/bot/d8OshqLZvtcKDcNluPuyo) - Daily ops desk that routes work and waits for approval.
- [Growth Desk](https://x.ai/bot/YYCOE-YeGxnGLb4Mbv7dO) - Growth research and draft campaigns; does not publish.
- [Forge](https://x.ai/bot/uF_uodOFUz9mdv6XDWE70) - Turns one keyword or task into a shareable bot recipe.
- [Watchdog](https://x.ai/bot/PuAEE57P58Df5zskFY3pg) - Weekly Gmail scan for receipts, renewals, and trials. Lists charges; never cancels or spends.
- [Thoth](https://x.ai/bot/W4Z5pvEm6UgCml48Ig4dT) - Deep research that files briefs so you can find them later.
- [Carmack](https://x.ai/bot/B5UMQzelNds6Iy2nuFrka) - First-principles desk for small hobby game engines.

## Skills

- [grok-bot-super](https://github.com/AgentMindCloud/grok-bot-super) - Standup, triage, research brief, weekly review, and X-thread builder.
- [grokbot-imessage-skill](https://github.com/jeffhuber/grokbot-imessage-skill) - Local macOS iMessage read, triage, and send. No cloud sync.
- [superpowers](https://github.com/obra/superpowers) - Planning, debugging, and writing workflows used across agents.

## Plugins and MCP

- [X plugin](https://x.ai/bot/plugin/49086599) - Search posts, read timelines, and check mentions from the bot.
- [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Drive and inspect a live Chrome session.
- [Cloudflare skills](https://github.com/cloudflare/skills) - Workers, KV, R2, and DNS from the agent.
- [Figma](https://github.com/figma/mcp-server-guide) - Read designs, variables, and components from Figma files.
- [MongoDB](https://github.com/mongodb/agent-skills) - Query collections, inspect schemas, and manage Atlas.
- [Railway](https://github.com/railwayapp/railway-skills) - Deploy services, read build logs, and manage env vars.
- [Stripe AI](https://github.com/stripe/ai) - Payments and billing objects, including test mode.
- [Vercel plugin](https://github.com/vercel/vercel-plugin) - Deployments, logs, and domains.
- [orgx-grokbot-plugin](https://github.com/useorgx/orgx-grokbot-plugin) - OrgX MCP wiring and specialist agent packs in `.grok-plugin` format.
- [Unbrowse](https://github.com/unbrowse-ai/unbrowse) - Hosted MCP and Cursor plugin that reads pages as markdown and runs site tasks through learned APIs, so the bot skips clicking through its browser.

## Engineering

- [pstack](https://github.com/cursor/plugins/tree/main/pstack) - Lauren Tan's verify-first engineering plugin (`/poteto-mode`, `/goal`, `/loop`).
- [pstack-grok](https://github.com/praveen221/pstack-grok) - Same pstack playbooks wired for Grok Build.

## Tools

- [grok-bot-cli](https://www.npmjs.com/package/grok-bot-cli) - Create bots and groups, send prompts, and inspect threads from the terminal.
- [sand](https://github.com/alokwhitewolf/sand) - Unofficial CLI bridge to message Grok Bots.
- [Grok Chrome Bridge](https://github.com/davidsolheim/grok-chrome-bridge) - Attach Grok Build to your real Chrome profile instead of an empty one.

## Runtimes

- [OpenGrokBot](https://github.com/wolfqing/OpenGrokBot) - Self-hosted alternative on OpenClaw plus any model you bring.
- [grokbot-shim](https://github.com/luckeyfaraday/grokbot-shim) - Run the desktop agent locally with a swap-in model backend and noVNC computer.
- [grok-bot-setup](https://github.com/BlockedPath/grok-bot-setup) - Adapter CLI and custom model-provider bridges.

## Guides

- [grok-bot-info](https://github.com/Uncle-Gizmo/grok-bot-info) - Notes on safe workflows and how Grok Bot fits next to Grok Build.
- [grok-bot-intro-v2](https://github.com/520xiaomumu/grok-bot-intro-v2) - Twelve-chapter Chinese-language intro deck.

## Contributing

See [contributing.md](contributing.md). New entries go at the bottom of the matching section. One pull request per item. Link the official share page or the project repo only.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
