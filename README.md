# BusinessKit Social — Agent-First Social Media Management

BusinessKit Social is the social media management layer of the BusinessKit business operating system — connect your accounts, draft and schedule posts, and publish across platforms, with AI agents running the queue as a native operation instead of a separate scheduling tool bolted on the side.

**Full platform:** [businesskit.io](https://businesskit.io)
**Download BusinessKit:** [Releases](https://github.com/businesskitai/businesskit/releases)

---

## What makes it agent-first

- **Agents draft and queue posts directly** — an agent can write a post, queue it for a platform, or publish it immediately as part of a conversation, using the same tools the in-app agent uses
- **Agents work from business context** — because the agent has access to your CRM, inventory, and content data in the same database, a post about a new product or a customer win can be drafted from what actually happened in the business, not typed from scratch
- **Headless automation** — background agent runs can process a scheduled queue, repost evergreen content, or draft posts on a recurring cadence unattended
- **MCP-exposed toolbelt** — external agents and automations connect via BusinessKit's MCP server to draft, queue, and publish posts using the same tools as the in-app agent
- **Strict data isolation** — every agent action is scoped to the active business's own database; no cross-tenant access

## Core capabilities

- Connect and manage multiple social accounts per business profile
- Draft, queue, and schedule posts across platforms
- Publish immediately or hold in queue for later
- Delete or edit queued posts before they go out
- Post-level and account-level analytics

## Content, one level up

Posts don't have to be written from nothing — content drafted in [BusinessKit CMS](https://github.com/businesskitai/cms) (a blog post, a newsletter) can be repurposed into a social post by the same agent, in the same conversation, without exporting or copy-pasting between tools.

## Get started

Social is a module inside the full BusinessKit application — there is no standalone installer. Download the platform and connect your accounts from the Social workspace:

👉 [github.com/businesskitai/businesskit/releases](https://github.com/businesskitai/businesskit/releases)

## Related BusinessKit modules

- [CMS](https://github.com/businesskitai/cms) — blogs, newsletters, community feed, and directory sites
- [CRM](https://github.com/businesskitai/crm) — agent-first pipeline and deal management
- [Billing](https://github.com/businesskitai/billing) — agent-first invoicing with GST/VAT/Sales Tax handling
- [GST ERP](https://github.com/businesskitai/gst-erp) — billing, inventory & GST compliance for India
- [B2B Commerce](https://github.com/businesskitai/b2b-commerce) — global B2B ordering, multi-currency & multi-tax

## Learn more

- Platform overview: [businesskit.io](https://businesskit.io)
- Issues and feedback: [GitHub Issues](https://github.com/businesskitai/businesskit/issues)

## License

© BusinessKit. All rights reserved.
