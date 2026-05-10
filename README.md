# Avalux — Open Source

> Hub for the open-source automation toolkits we maintain at [Avalux](https://avalux.io).
>
> Avalux is a full-stack AI automation agency working with SMBs in **freight, e-commerce, and home services**. We build the unsexy operational middleware that quietly removes hours of manual work per week — real APIs only, no fragile portal scraping, no AI-receptionist slop.

## The toolkits

### 🚛 [freight-eta-toolkit](https://github.com/elikem2021/freight-eta-toolkit)
Open-source utilities for SMB freight brokers and 3PLs to build their own driver-tracking and shipper-ETA dashboards on Geotab, Samsara, and Motive APIs. The Project44 / FourKites alternative for shops too small for enterprise pricing. Stop the phone-tag.

**Tech:** Python, Geotab MyGeotab API, Samsara API, Motive API, Twilio, geofencing.
**For:** freight brokers running 10–200 loads/day, 3PLs, owner-operators.

### 🛍 [shopify-quickbooks-sync](https://github.com/elikem2021/shopify-quickbooks-sync)
Self-hosted Shopify ↔ QuickBooks Online sync middleware with line-item accuracy, idempotent replay, and multi-currency support. The A2X / Bookkeep alternative for merchants who want to own their data and account mappings.

**Tech:** Node.js, Express, Shopify webhooks, QuickBooks Online API, Postgres.
**For:** Shopify merchants doing $500k–$30M/year, e-commerce bookkeepers, multi-store operators.

### 🔁 [n8n-self-hosted-toolkit](https://github.com/elikem2021/n8n-self-hosted-toolkit)
Production-ready Docker setup for self-hosted [n8n](https://n8n.io), the open-source Zapier / Make.com alternative. Hardened defaults (Caddy reverse proxy, queue mode, Postgres, Redis), automated backups, and a starter library of SMB ops workflow templates.

**Tech:** Docker Compose, n8n, Caddy, Postgres, Redis.
**For:** SMB ops leaders, agencies, founders who want owned infrastructure instead of a SaaS subscription.

## Why open source?

Three reasons:

1. **Trust before the contract.** Every line of our integration logic is public. If you want to inspect, fork, or self-host before talking to us, you can.
2. **Honest scope.** When you can read the code that does the work, no one can sell you AI snake oil. The toolkits make plain what's actually being built.
3. **Inbound.** Builders who find these repos via GitHub or Google search are the buyers we want — they've already decided automation is real, they just need someone to ship it.

## Working with Avalux

If you'd rather have these built, deployed, and operated for you instead of self-hosting them, that's the day job. Fixed-scope contracts, real APIs only, monthly retainers for ongoing operations. See [avalux.io](https://avalux.io) or email [eli@avalux.io](mailto:eli@avalux.io).

## What we don't do

- AI receptionists, AI booking agents, AI lead-takers — saturated, every agency sells them
- Fragile browser-portal scraping for "warranty registration" or "rebate paperwork" — breaks every quarter, terrible for clients
- Generic "AI for [vertical]" packaged offers
- Anything that smells like LinkedIn AI-agency boilerplate

## What we do

- Real-API integrations on stable platforms (Geotab, Samsara, Twilio, Stripe, QuickBooks, Shopify, ServiceTitan, etc.)
- Self-hosted workflow infrastructure clients can own forever
- Vertical-specific operational automation that needs domain knowledge to design well
- Honest scoping — if a job isn't a fit, we say so

## License

Each toolkit is MIT-licensed. Use, fork, ship, sell.

## Verticals we serve

Freight & logistics · E-commerce · Home & field services · Real estate · Healthcare (non-clinical ops) · SaaS startups · Professional services

## Service areas

GTA (Mississauga, Brampton, Toronto, Vaughan, Hamilton, Oakville, Burlington, Markham), and remote across Canada and the United States.
