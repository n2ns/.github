# N2NS Lab

**N2NS Lab** is [Datafrog](https://datafrog.io)'s open-source division — local-first tools for AI coding agents and the developers who work with them: MCP servers, editor and browser extensions, Laravel packages, and small utilities.

## Projects

### MCP & AI agents

#### [n2n-memory](https://github.com/n2ns/n2n-memory) · [![npm](https://img.shields.io/npm/v/n2n-memory?label=npm)](https://www.npmjs.com/package/n2n-memory)

Project-local knowledge-graph MCP memory server. Stores durable context in `.mcp/memory.json` inside each repo — isolated per project, Git-friendly, no cloud required.

#### [n2n-nexus](https://github.com/n2ns/n2n-nexus) · [![npm](https://img.shields.io/npm/v/n2n-nexus?label=npm)](https://www.npmjs.com/package/n2n-nexus)

Local-first MCP coordination hub for multi-AI collaboration. One daemon serves multiple AI assistants across IDEs — shared meetings, tasks, messages, and project registry.

#### [n2n-post2site](https://github.com/n2ns/n2n-post2site) · [![npm](https://img.shields.io/npm/v/n2n-post2site?label=npm)](https://www.npmjs.com/package/n2n-post2site)

MCP bridge for AI-assisted content publishing. Draft, edit, and publish to your blog or CMS through a minimal API contract — no DB or shell access required.

#### [hyper-hand](https://github.com/n2ns/hyper-hand) · [![release](https://img.shields.io/github/v/release/n2ns/hyper-hand?label=release)](https://github.com/n2ns/hyper-hand/releases/latest)

Let AI agents (Claude Code, Codex, any MCP client) control Hyper-V Windows VMs — screenshots, mouse, keyboard, commands, files and checkpoints, with no guest network or password.

#### [MCPxHub](https://github.com/n2ns/MCPxHub) · [![npm](https://img.shields.io/npm/v/@bugstan/mcpxhub?label=npm)](https://www.npmjs.com/package/@bugstan/mcpxhub)

MCP bridge that auto-discovers VS Code-family and JetBrains IDE MCP servers and proxies Claude Desktop's tool calls to them, reconnecting as ports change.

#### [ggMCP4VSCode](https://github.com/n2ns/ggMCP4VSCode) · [![VS Code](https://vsmarketplacebadges.dev/version/bugstan.gg-mcp-for-vscode.svg)](https://marketplace.visualstudio.com/items?itemName=bugstan.gg-mcp-for-vscode)

VS Code extension that runs a local MCP server, exposing workspace files, editor, terminal, Git, debugging and code analysis tools to MCP clients. Works in VS Code, Cursor, Windsurf and Antigravity.

### Editor & developer tools

#### [antigravity-panel](https://github.com/n2ns/antigravity-panel) · [![Open VSX](https://img.shields.io/open-vsx/v/n2ns/antigravity-panel?label=open-vsx)](https://open-vsx.org/extension/n2ns/antigravity-panel)

Community toolkit for Google Antigravity IDE. Quota dashboard, usage analytics, cache manager, auto-accept mode, and AI commit generator. 15 languages.

#### [plan-swap](https://github.com/n2ns/plan-swap) · [![Open VSX](https://img.shields.io/open-vsx/v/n2ns/planswap?label=open-vsx)](https://open-vsx.org/extension/n2ns/planswap)

See what is left on each Claude Code and Codex subscription account, get a recommended account when the current one runs low, and switch from a VS Code sidebar without signing out.

#### [wsl-remote](https://github.com/n2ns/wsl-remote) · [![Open VSX](https://img.shields.io/open-vsx/v/n2ns/wsl-remote?label=open-vsx)](https://open-vsx.org/extension/n2ns/wsl-remote)

WSL 2 remote development for VSCodium and other VS Code builds — server environment hook, safe server install, no shell injection.

### Browser extensions

#### [chrome-slopster](https://github.com/n2ns/chrome-slopster) · [![Chrome Web Store](https://img.shields.io/chrome-web-store/v/mmgmeicjkmabnhjedpinlnpddagpoend?label=chrome%20web%20store)](https://chromewebstore.google.com/detail/slopster/mmgmeicjkmabnhjedpinlnpddagpoend)

Side panel for Reddit, X and Facebook: translates posts and comments in place, drafts replies and new posts with your own AI key, and can hide ads. You review and send everything.

#### [chrome-widemark](https://github.com/n2ns/chrome-widemark) · [![Chrome Web Store](https://img.shields.io/chrome-web-store/v/jmagjbdffihnegmhhpfdffceapdhlldh?label=chrome%20web%20store)](https://chromewebstore.google.com/detail/widemark-bookmark-side-pa/jmagjbdffihnegmhhpfdffceapdhlldh)

Compact bookmark side panel for browsing, search, organization, styling, and local duplicate checks.

### Laravel

#### [laravel-post2site](https://github.com/n2ns/laravel-post2site) · [![Packagist](https://img.shields.io/packagist/v/n2ns/laravel-post2site?label=packagist)](https://packagist.org/packages/n2ns/laravel-post2site)

Laravel backend package for the Post2Site content publishing API contract — the server side of n2n-post2site.

#### [laravel-site-stats](https://github.com/n2ns/laravel-site-stats) · [![Packagist](https://img.shields.io/packagist/v/n2ns/laravel-site-stats?label=packagist)](https://packagist.org/packages/n2ns/laravel-site-stats)

Cookieless web analytics for Laravel, for one site or many: daily aggregates only, built-in dashboard, Filament pages, read API.

#### [laravel-saas-kit](https://github.com/n2ns/laravel-saas-kit)

Installable Laravel 12 starter kit for SaaS and product websites.

### Utilities

#### [pairdock](https://github.com/n2ns/pairdock) · [![release](https://img.shields.io/github/v/release/n2ns/pairdock?label=release)](https://github.com/n2ns/pairdock/releases/latest)

Pair mice and keyboards to Logitech Bolt receivers and customize their buttons, without Logi Options+.

---

## Support

All tools are free and open-source. If they save you time, consider sponsoring:

[![GitHub Sponsors](https://img.shields.io/github/sponsors/n2ns?label=Sponsor&logo=githubsponsors)](https://github.com/sponsors/n2ns)

---

[datafrog.io](https://datafrog.io) · [n2ns.com](https://n2ns.com)

## License

Licensed under the [Apache License, Version 2.0](LICENSE).
