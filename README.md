# Estii

Estii helps technology services businesses make better commercial decisions before committing to delivery. Estii gives technology services teams one commercial model for every deal, aligning sales, delivery and finance around scope, effort, pricing, margin, revenue and schedule before committing to delivery.

This plugin lets Claude work in your Estii account. Ask Claude to check a deal before it goes for approval, start a deal from your templates and library, or explain what changed since the version you sent the client and what that did to margin.

## What Claude can do

- Find a deal and summarise its price, cost, margin and schedule
- Compare versions and variants of a deal
- Add or change phases, tasks, effort and roles, previewing each change before it's saved
- Start a deal from your templates and reusable work items
- Forecast revenue and resource demand across your pipeline
- Export a deal to Excel, JSON or Markdown
- Request approval, or mark a deal won or lost

Try asking:

- "Review the Acme portal deal before I send it for approval. What should I be worried about?"
- "Create a deal for Acme's portal rebuild from our Website Build template, and add discovery and QA from our library."
- "What changed in the Acme deal since the version we sent the client, and why did the margin drop?"

## Before you start

You need an Estii account. The first time Claude uses Estii, you sign in and approve the connection; there's no API key to copy. Reading works on any plan. Making changes, and revenue and capacity forecasts, need a paid plan or an active trial.

## How it works

The plugin contains no code. It adds one remote MCP server, Estii's hosted server at `https://api.estii.com/mcp`, and nothing else. Claude sends your requests to that server over HTTPS and signs in with OAuth. Every action runs with your own Estii permissions and space rules. Changes can be previewed before they're applied, and approvals follow the same process as the app.

Documentation: [estii.com/dev/mcp](https://www.estii.com/dev/mcp)

## Privacy

The plugin sends data only to Estii. How Estii collects, uses, stores and retains data is described in the [privacy policy](https://www.estii.com/privacy). Use of Estii is covered by the [terms](https://www.estii.com/terms).

## Support

Email [support@estii.com](mailto:support@estii.com) or visit [estii.com/contact](https://www.estii.com/contact).
