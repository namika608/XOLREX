# XOLREX

**AI-powered global financial market intelligence.**

XOLREX is being built to connect fragmented financial-market data, analyze market behaviour across asset classes, and turn complex information into clear, evidence-backed intelligence for traders, investors, analysts, and financial institutions.

> **Project status:** Foundation stage. This repository is the starting point for product planning and implementation. No live market-data integrations or production AI capabilities are claimed yet.

## Product vision

Build a global financial intelligence platform—not a chatbot with market widgets. The main experience will be a live-feeling, evidence-led market dashboard, with AI as the intelligence layer across every market.

## Core product areas

- **Global dashboard:** Cross-market overview, movers, unusual activity, news, watchlists, and explainable AI insights.
- **Crypto:** Spot markets, volatility, volume, asset performance, and market structure.
- **DEX & on-chain:** Decentralized exchange activity, liquidity, token activity, wallet flows, and large transactions.
- **Perpetuals & derivatives:** Open interest, funding rates, liquidations, leverage, and positioning.
- **Stocks & real-world assets:** Equities, sectors, company activity, and tokenized real-world assets.
- **Forex:** Currency pairs, relative strength, volatility, and macroeconomic drivers.
- **AI intelligence:** Research and analysis grounded in sourced data, with timestamps, evidence, uncertainty, and clear separation of live, delayed, historical, and demo data.

## Product principles

1. **Evidence before claims.** Every market insight should be traceable to data or a source.
2. **Honest data states.** Clearly label live, delayed, historical, simulated, and unavailable data.
3. **AI across the product.** AI interprets and connects data; it is not the entire product.
4. **Useful functionality over mockups.** Prioritize working flows and real integrations over decorative dashboards.
5. **Modular foundations.** Keep market domains, data providers, analysis, and presentation independently maintainable.
6. **Security by default.** Never commit API keys, credentials, private user data, or production secrets.

## Initial implementation direction

The first milestone is a responsive, navigable product foundation with a global intelligence dashboard and dedicated routes for each product area. Use clearly identified sample data only until verified data providers are connected. Do not present sample values or simulated AI output as live market intelligence.

See [Product vision](docs/PRODUCT_VISION.md) for scope and first milestones.

## Development

The application stack and deployment target will be selected before implementation begins. Keep this repository as the source of truth for product requirements, architecture decisions, and code.

## Security

- Keep this repository private before adding proprietary code, credentials, or sensitive business information.
- Use environment variables for secrets and commit only a safe `.env.example`.
- Report security issues privately to the repository owner; do not publish secrets in issues.

---

XOLREX — Global Financial Market Intelligence.
