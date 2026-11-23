# XOLREX — Product Vision & Initial Milestones

## 1. Company and product

XOLREX is an AI-powered global financial market intelligence platform. It connects fragmented market information, analyzes behaviour across asset classes, and delivers clear, actionable, evidence-backed intelligence.

The product serves traders, investors, analysts, and—over time—financial institutions. It is not crypto-only, not a DEX, and not a chatbot-first product.

## 2. Experience principles

- The home screen opens on a useful global market intelligence dashboard.
- Market data, news, and AI analysis are connected throughout the product.
- AI research/chat is a dedicated workspace and an entry point available from the wider application, not a replacement for the dashboard.
- Every insight should show its supporting evidence, source, and timestamp where available.
- The interface must distinguish live, delayed, historical, demo, and unavailable data.
- Mobile navigation should make the core market areas easy to reach; desktop should provide an efficient persistent navigation structure.

## 3. Product areas

### Global intelligence dashboard
Cross-market snapshot, major movers, unusual activity, key derivatives signals, on-chain activity, latest financial news, watchlists, and evidence-backed AI briefings.

### Crypto
Spot-market overview, asset pages, volume, volatility, price performance, and market structure.

### DEX & on-chain intelligence
DEX activity, liquidity, token discovery, wallet flows, large transactions, and smart-money research where reliable data is available.

### Perpetuals & derivatives
Open interest, funding rates, liquidations, leverage, long/short positioning, and derivatives-market changes.

### Stocks & real-world assets
Equities, company and sector analysis, market activity, and intelligence on tokenized real-world assets.

### Forex
Major and minor currency pairs, currency strength, volatility, central-bank decisions, and macroeconomic events.

### AI intelligence workspace
Natural-language research across all product areas; market explanations; cross-asset analysis; sourced summaries; alerts and reports. AI output must be grounded in retrieved data and clearly communicate uncertainty.

## 4. First milestone: credible product foundation

1. Establish the application architecture, coding conventions, and environment configuration.
2. Build responsive navigation and routes for the dashboard and all six market/intelligence areas.
3. Implement the dashboard layout with clearly labelled sample data where live feeds are not yet integrated.
4. Build reusable market cards, data tables, charts, news items, source/timestamp labels, and empty/error/loading states.
5. Establish typed data-provider interfaces so verified providers can be connected without rewriting the UI.
6. Add an AI intelligence interface only when it can clearly distinguish sourced results from unsupported responses.
7. Add basic tests, linting, documentation, and a deployment-ready build.

## 5. Data integrity requirements

- Never fabricate current prices, market movements, news, liquidations, wallet activity, or AI findings.
- Sample data must be explicitly marked as demo/sample.
- Preserve provider, retrieval time, market timestamp, currency, and delay information where supplied.
- Handle missing, stale, conflicting, and unavailable data explicitly.
- Do not provide personalized financial advice or imply certainty about market outcomes.

## 6. Non-goals for the first milestone

- No fake live integrations or hard-coded claims presented as real-time data.
- No unsupported automated trading or custody functionality.
- No attempt to build every advanced analytics feature before the core data foundation works.
- No chatbot-only homepage.

## 7. Architecture decision checklist

Before substantial implementation, document:
- Frontend framework and routing.
- Backend/API approach.
- Database and cache requirements.
- Authentication and authorization.
- Market-data/news provider choices, coverage, licensing, rate limits, and costs.
- AI model and retrieval/evidence strategy.
- Hosting, observability, testing, and security controls.

## 8. Definition of a successful first milestone

A user can open XOLREX, understand the broad market picture, navigate each product area, inspect clearly labelled sample or verified data, and open the AI intelligence workspace. The application behaves reliably on mobile and desktop, and no demo information is misrepresented as live.
