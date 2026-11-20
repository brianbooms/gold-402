<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
    <img src="assets/hero-light.svg" alt="gold-402 — a hand-checked directory of x402 services. Most of the x402 catalogue no longer answers; these are the ones that did. We check it, we date it, and we tell you what we found. By 24K Labs." width="680">
  </picture>
</p>

# gold-402

> The gold standard for x402 resources. **<!--COUNT:START-->553<!--COUNT:END--> curated entries** — paid endpoints probed for a live 402 before listing, libraries and repos checked for real activity, and the whole shelf re-knocked every night with the result dated. No filler. Entries that stop answering move to [DEPARTURES.md](DEPARTURES.md) and keep getting knocked; the night one answers again, it comes back.

[![GitHub stars](https://img.shields.io/github/stars/Haustorium12/gold-402?style=social)](https://github.com/Haustorium12/gold-402)
[![Last Commit](https://img.shields.io/github/last-commit/Haustorium12/gold-402)](https://github.com/Haustorium12/gold-402/commits/main)
[![Curated by 24K Labs](https://img.shields.io/badge/Curated_by-24K_Labs-gold)](https://24klabs.ai)

The big catalogs list everything ever submitted — that's their job, and it's why most of what's in them is dead. We measured it: **67–79% of the free-listing catalogs no longer answer.**

gold-402 is the other thing. Smaller on purpose. A person checked every entry, we publish what we checked and what we didn't, and in July 2026 we started **buying services and reporting what came back**. Automated monitors now do the machine half of that continuously and do it well; what they do not do — by their own published scope — is judge whether the thing that came back was any good. That judgement is what this list is.

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sections/directory-dark.svg">
  <img src="assets/sections/directory-light.svg" alt="Section: The Directory" width="680">
</picture>

## The Directory

The product. <!--COUNT:START-->553<!--COUNT:END--> entries across <!--SHELVES:START-->13<!--SHELVES:END--> shelves, in [`directory/`](directory/).

| Shelf | What's on it |
|---|---|
| [APIs & Services](directory/apis.md) | Paid endpoints an agent can call. Every one probed for a live 402 before listing. |
| [MCP Servers](directory/mcp-servers.md) | Model Context Protocol servers — utility, crypto, security, identity, escrow, discovery. |
| [SDKs & Libraries](directory/sdks.md) | Client and server libraries across languages. |
| [Facilitators](directory/facilitators.md) | Payment verification and settlement services. |
| [Frameworks](directory/frameworks.md) | Agent frameworks with x402 support. |
| [Tools](directory/tools.md) | CLIs, CI, monitoring, spend controls, testing, discovery. |
| [Security](directory/security.md) | Audit, risk scoring, pre-execution gates, compliance. |
| [Ecosystem](directory/ecosystem.md) | Protocol, infrastructure, wallets, orchestration, marketplaces. |
| [Aggregators & Proxies](directory/aggregators.md) | One integration, many upstreams — services that unify or resell access to other providers' APIs and data. |
| [**The Global Agent Economy**](directory/global.md) | **China, India, Korea — infrastructure no English-language directory indexes.** |
| [Learning](directory/learning.md) | Quickstarts, tutorials, reference docs, news. |
| [Community](directory/community.md) | Channels, newsletters, jobs, events. |
| [Market Data](directory/market-data.md) | On-chain analytics, dashboards, adoption. |

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sections/verified-dark.svg">
  <img src="assets/sections/verified-light.svg" alt="Section: What being on this list means" width="680">
</picture>

## What being on this list means

There is no stamp. There was one — "Gold402 Verified," one tier, a gold tick — and it was
retired on 2026-09-06 because it said the identical thing about a paid API we knocked last
Tuesday, a community wiki with no endpoint to knock at all, and an entry we hold no dated
receipt for. A mark that everything wears certifies nothing. We have made that criticism of
other people's badges and it was true of ours.

What every entry now carries instead is the finding, per entry:

- **A date** — *this endpoint answered an HTTP 402 when we knocked it, on this day.* An
  automated gate checks the submission, a maintainer confirms it before merge, and a sweep
  re-knocks and writes a dated result. A date is checkable. A tick is not.
- **Or "listed — no knock receipt"** — a human read it and it is on the list. We hold no
  dated knock, and we will not backfill a date we cannot show.
- **Or "listed — no endpoint to knock"** — libraries, guides, wallets, clients and
  community resources. Nothing here answers a 402 because that is not what these things
  do. We read them, and we checked they were publicly reachable.

**None of it is a delivery test.** We have not paid these services and graded what came
back. Read any of it as "we checked what is stated above," never as "this is worth the
money."

**Some entries carry more.** Where we have paid for a service and confirmed what came back,
we say so and keep the receipt — what we sent, what it cost, the transaction hash, what
arrived. That is a stronger claim and we only make it about services we actually bought.
Most of the list has not been through that, and we would rather say so than imply otherwise.

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sections/ecosystem-dark.svg">
  <img src="assets/sections/ecosystem-light.svg" alt="Section: Ecosystem Data" width="680">
</picture>

## Ecosystem Data

Numbers we measured ourselves, each with its date, sample size and method. Where measurements disagree, both are shown — they were taken on different days by different methods, and blending them into one tidy figure would be the kind of thing this directory exists to argue against.

### How much of the ecosystem is alive

| Measured | Population | Live | Dead | Method |
|---|---|---|---|---|
| 2026-07 | 22,545 CDP Bazaar services | 5,792 | **74%** | full probe crawl, valid 402 required |
| 2026-07-10 | 25,614 catalog services | 5,344 | **79%** | catalog snapshot, verify-state carried forward |
| 2026-07-29 | 24,583 catalog services | — | **~67%** | earlier full crawl, cited in the liveness study |

Three runs, three numbers, one direction: **the large free-listing catalogs are majority dead, and have been all month.** Anyone quoting a single decimal-point figure for this is quoting a moment, not a fact.

### Liveness is predicted by listing friction

Across four independent registries — 204,500 registered agents and services — the dead share tracks one variable: what it costs to get listed.

| Registry | Entry cost | Dead |
|---|---|---|
| CDP Bazaar | free | ~67–79% |
| ERC-8004 on-chain identity | gas only | 85–97% |
| Glama MCP registry | curation + scoring | 47% unhealthy _(their own published figure)_ |

**Free entry selects for abandonment.** Full method, limits, and an open invitation to refute it: [The Liveness Law →](articles/2026-07-the-liveness-law.md)

### Buying is harder than finding

In July 2026 we ran a paid delivery check across our own shelf — actually buying services and recording what came back.

- **16** of 126 listed services were purchasable by a machine at a discoverable address
- **8** delivered exactly what they advertised
- **0** took payment and returned nothing
- **$0.054** spent, every transaction reconciled on-chain

The friction in this economy sits **before** the payment, not after it. Most services are fine; most front doors are not. **We are not claiming that as a finding yet — the sample is 16 services and one day, 2026-07-30.** A wider census was designed the same week and has not run; the blocker is ours, not the ecosystem's. We would rather say that than let the sentence stand.

### Coverage beyond the West

x402 is a US-governed rail. It is not the only answer to machine payment, and outside the West it is not the answer being used — China runs delegated agent authorization on existing rails, India runs regulated human-signed mandates that agents execute inside a cap. Both were operating at scale before the x402 Foundation was a month old.

We index that world too, including surfaces no English-language directory carries: [The Global Agent Economy →](directory/global.md)

_All figures above are ours and reproducible. Where we could not reach something, we say so rather than leaving the gap invisible._

---

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sections/featured-dark.svg">
  <img src="assets/sections/featured-light.svg" alt="Section: Featured This Month" width="680">
</picture>

## Featured This Month

[![24K Featured](https://img.shields.io/badge/24K_Featured-2026--10-C0C0C0?style=plastic)](FEATURED.md)

**October 2026 — one pick per shelf.** Each shelf opens with its pick and the write-up. Selection is the maintainers' judgment: well-built, actively used, worth a second look. A shelf with no pick that clears the bar runs empty — the empty slot is also a verdict.

| Shelf | October pick |
|---|---|
| APIs & Services | [crosscheck accept](https://crosscheckapi.com/v1/accept) |
| MCP Servers | [Base toolbox](https://basetoolbox.cartonpliant.workers.dev/.well-known/mcp.json) |
| SDKs & Libraries | [x402-dotnet](https://github.com/michielpost/x402-dotnet) |
| Facilitators | [ArisPay](https://facilitator.arispay.app) |
| Frameworks | [x402-rails](https://github.com/quiknode-labs/x402-rails) |
| Tools | [ToolMeter](https://snappedai.com/toolmeter/) |
| Security | [ICME Labs](https://docs.icme.io) |
| Ecosystem | [Bermuda](https://www.bermudabay.xyz) |
| The Global Agent Economy | [Beckn Protocol](https://github.com/ONDC-Official) |
| Learning | [How x402 paid links work (Payfirst)](https://www.payfirst.app/guides/x402-paid-links) |
| Community | [Dev.to #x402](https://dev.to/t/x402) |
| Market Data | [Dune Analytics x402](https://dune.com/x402) |
| Aggregators & Proxies | [x402-list](https://x402-list.com) |

[Past features →](FEATURED.md)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sections/wire-dark.svg">
  <img src="assets/sections/wire-light.svg" alt="Section: This Week in x402" width="680">
</picture>

## This Week in x402

The wire lives at **[24klabs.ai/news](https://24klabs.ai/news)** — dated editions with permanent links, every claim cited. Four editions so far; the most recent is [2026-08-10](https://24klabs.ai/news/2026-08-10/). It is not on a schedule.

---

<!-- NEW-THIS-WEEK:START -->
## New This Week

**This week** (Nov 16—22)

- **[Toll Facilitator](https://x402.t0ll.xyz/supported)** — Free, keyless x402 facilitator for USDG on Robinhood Chain (eip155:4663), x402 v1 and v2, via EIP-3009 or Permit2: exact, upto, auth-capture escrow and batch-settlement. Open /verify and /settle with no API key, the facilitator pays gas, and each payTo is checked against the seller's ERC-8004 agent wallet before settling. [Docs](https://x402.t0ll.xyz/docs) · [Test 402 resource](https://t0ll.xyz/api/x402/pulse).
- **[ZERO Payment Guard](https://zero-payment-guard.worker.beacon.host/.well-known/x402)** — Hosted x402 API and remote MCP server on Base that preflights another x402 endpoint's payment terms ($0.005), verifies a USDC payment transaction ($0.002), checks token safety ($0.003) and reads wallet and transaction state ($0.001-$0.002), with an MIT-licensed Python preflight CLI on GitHub.
- **[Solana Token Safety](https://tokensafety.dedyn.io/.well-known/x402)** — Pay-per-call Solana token safety checks ($0.01) and a Pump.fun new-launch feed ($0.005) in USDC on Solana via x402, covering mint/freeze authority, Token-2022 extensions, top-10 holder concentration, bonding-curve state, token age, and a 0-100 risk score. ([OpenAPI](https://tokensafety.dedyn.io/openapi.json))
- **[UK Postcode Intel](https://uk-postcode-intel.mcpize.run/mcp)** — Hosted streamable-HTTP MCP server for UK postcode due diligence from official open data: location and admin areas, street crime, live flood warnings, FSA food hygiene ratings and HM Land Registry sold prices. `initialize` and `tools/list` are free; unpaid `tools/call` returns HTTP 402. Prices are $0.05 for `area_report`, $0.02 for `house_prices`, and $0.01 for `postcode_lookup`, `crime_summary`, `flood_warnings` and `food_hygiene_nearby`, in USDC on Base via x402. ([Listing](https://mcpize.com/mcp/uk-postcode-intel))
- **[BeliefState](https://beliefstate.ai/v1/research)** — Returns dated, source-linked investor theses, catalysts and risks for a covered stock ticker via x402 for 0.02 USDC per brief on Base. Example: `POST /v1/research/get_brief {"ticker":"NBIS","detail":"overview"}`.
- **[AA Signals](https://signals.brobotapp.com/v1/signal/BTC?tier=premium)** — Real-time crypto/Bittensor-subnet trading signals (action, confidence, composite score, regime) for 8 symbols, scored live against Kraken data with REAX (Bittensor Subnet 92) confidence-scaling, backed by a public unpaywalled backtest. $0.01-$0.10 USDC on Base mainnet depending on tier (standard tier has a 3-call/day free allowance; `?tier=premium` always requires payment). ([Backtest](https://signals.brobotapp.com/api/track_record)) ([Manifest](https://signals.brobotapp.com/.well-known/x402)) ([llms.txt](https://signals.brobotapp.com/llms.txt))
- **[NEXSUSA M2M API](https://api.nexsusa.com/.well-known/x402)** — 186 pay-per-call routes for agents: web-to-markdown extraction, crypto sentiment and funding rates, DEX arbitrage scanner, contract security scans, code audit, OSINT lookups, invoice OCR, RAG chunking, and AI image generation via local CPU diffusion (job-based, poll for result). $0.001–$0.10 USDC on Base and Arbitrum via x402 v1+v2. Example: `GET /api/sentiment?q=BTC`. ([OpenAPI](https://api.nexsusa.com/openapi.json)) ([llms.txt](https://api.nexsusa.com/llms.txt))
- **[x402 pre-trade token check](https://x402-token-check-production.loudtzu.workers.dev/check)** — Pre-trade risk verdict for a Base or Solana token: liquidity from DexScreener, with GeckoTerminal and onchain-reserve fallbacks marked estimated, pool age, honeypot and sell tax, mint and freeze authority, top-holder concentration, and labeled exchange-wallet flags, plus a 0–100 score and reasons. $0.01 USDC on Base via x402. Facts only, not a buy or sell recommendation. Example: `GET /check?chain=base&token=0x22aF33FE49fD1Fa80c7149773dDe5890D3c76F3b`. ([OpenAPI](https://x402-token-check-production.loudtzu.workers.dev/openapi.json)) ([Discovery](https://x402-token-check-production.loudtzu.workers.dev/.well-known/x402))
- **[Leviathan News Market Intelligence](https://api.leviathannews.xyz/api/v1/intel/report/)** — One market-intelligence report per call for agents, built on a human-curated crypto-news corpus: trending topics with velocity and hot scores, content performance, platform pulse, and a 0-1 posting signal. $0.25 USDC on Base. Example: `GET /api/v1/intel/report/?hours=24&top_n=10`. ([Agent docs](https://api.leviathannews.xyz/SKILL.md)) ([Site](https://leviathannews.xyz))
- **[MoneyTools x402-guard](https://www.npmjs.com/package/@moneytools-dev/x402-guard)** — Buyer-side TypeScript hook that attaches to an official x402Client's onBeforePaymentCreation hook to run Pay Precheck, local per-payment and daily caps, optional Approval Relay, and a payment log before anything is signed; it never loads a key or sends a payment.
- **[Carbonmark x402 Carbon Retirement API](https://x402.klimalabs.com/.well-known/x402.json)** — Retires tokenized carbon credits on Base from 0.001 tonnes and returns a public Carbonmark certificate; discover, quote and certificate calls are free, `GET /api/catalog` answers 402 for $0.001 USDC, and a retirement is paid with one signed USDC authorization (credit price plus fee and relay gas) sent to `POST /api/actions/retire`.
- **[Scrapling Data MCP](https://scraplingdata.xyz/mcp)** — Remote Streamable HTTP MCP server for pay-per-call crypto, DeFi, prediction-market, stock and GPU-price datasets and lookups via x402 (USDC on Base, Polygon, Arbitrum or Solana; USDC or USDT on BNB Chain). Official registry name io.github.bnth09productions-maker/scrapling-x402-store. ([Manifest](https://scraplingdata.xyz/.well-known/x402)) ([OpenAPI](https://scraplingdata.xyz/openapi.json)) ([Glama](https://glama.ai/mcp/connectors/io.github.bnth09productions-maker/scrapling-x402-store))
- **[YourAITools](https://api.youraitools.co/.well-known/x402)** — 25+ pay-per-call agent tools on api.youraitools.co, such as WebRead (web page to clean text), InjectScan (prompt-injection scan), PayGuard (payee address risk), TokenVerdict (token risk), FXRate and CryptoPrice. Each answers HTTP 402 and takes USDC on Base, with Polygon, Arbitrum and Solana on most routes, and has its own manifest, OpenAPI and remote MCP endpoint. ([OpenAPI](https://api.youraitools.co/openapi.json), [Status](https://youraitools.co/status/feed.json))
- **[rug-check-service](https://46-101-49-190.sslip.io/docs)** — Solana token rug-check API that returns factual mint, freeze, LP-lock, and holder checks as JSON; unpaid GET /check/{mint} is HTTP 402 with x402 v2 PAYMENT-REQUIRED, $0.25 per check or $5 for 100, paid in USDC or SOL on Solana mainnet to a receive-only address and self-verified on public RPC.
- **[IBANforge](https://ibanforge.com)** — Pre-payout IBAN screening: validation + issuing-bank identification against 6 national bank registers (CH/LI, DE, AT, BE, FI), Swiss clearing incl. QR-IID resolution, bank-level sanctions, SEPA + VoP reachability. 121k+ BICs, 89 IBAN countries. $0.002-$0.02 USDC on Base (CDP facilitator). MCP: `npx -y ibanforge-mcp`. ([OpenAPI](https://api.ibanforge.com/openapi.json), [x402 discovery](https://api.ibanforge.com/.well-known/x402))
- **[dropengine-agent-safety](https://github.com/Ahmet11159/dropengine-agent-safety)** — Zero-dependency TypeScript SDK for x402-paid agent safety checks (URL, prompt injection, npm package, combined action gate) that takes any x402-paying fetch and exports OpenAI and Vercel AI SDK tool definitions. ([npm](https://www.npmjs.com/package/dropengine-agent-safety))
- **[DropEngine](https://mcp.dropenginehq.com/.well-known/x402)** — Twenty-one pay-per-call x402 routes on Base USDC for agents: URL safety, prompt-injection scanning, npm package risk and a combined allow/warn/block action gate ($0.005–$0.02), plus wallet risk, transaction simulation, token audit, whale activity, web change monitoring and invoice checks, also served as an MCP server.
- **[dropengine-agentkit](https://github.com/Ahmet11159/dropengine-agentkit)** — Coinbase AgentKit action provider that pays per call in USDC on Base via x402 from the agent's own wallet, with a per-call spend cap, for whale activity, transaction simulation, token security audit, wallet risk and a pre-action allow/deny gate. ([npm](https://www.npmjs.com/package/dropengine-agentkit))
- **[URLGate MCP](https://urlgate.xyz/mcp)** — Remote Streamable HTTP MCP server that wraps URLGate pay-to-open short links, with tools to create links and to open a paid link using two EIP-3009 signatures (PAYMENT-SIGNATURE and PAYMENT-SIGNATURE-FEE) settled in USDC. ([Server card](https://urlgate.xyz/mcp/server-card)) ([Demo 402](https://urlgate.xyz/3coins))
- **[URLGate](https://urlgate.xyz/3coins)** — Pay-to-open short links for people and AI agents that answer an unpaid GET with Accept: application/json with HTTP 402 and an x402 v2 PAYMENT-REQUIRED header, settled natively in USDC on Base, Polygon, and Arbitrum. ([Site](https://urlgate.xyz/)) ([Manifest](https://urlgate.xyz/.well-known/x402)) ([llms.txt](https://urlgate.xyz/llms.txt))
- **[AutoTasker Hub](https://autotasker.highkingflower.com/api/x402/hotlist)** — x402 pay-per-call data API + streamable HTTP MCP server with 84 tools: free discovery and sample, plus pay-per-call China social trending data (Weibo, Douban, Zhihu, Bilibili) from $0.05 USDC per call on Base via x402. The linked endpoint is a real x402 endpoint: an unauthenticated GET returns HTTP 402 with payment requirements; the MCP transport is at /mcp (initialize + tools/call, protocol 2025-06-18). ([MCP](https://autotasker.highkingflower.com/mcp)) ([Manifest](https://autotasker.highkingflower.com/.well-known/x402.json)) ([Proof](https://autotasker.highkingflower.com/api/x402/proof))

**Last week** (Nov 9—15)

- **[TRON USDT Risk Checker](https://usdt.chikocorp.com/v1/x402/blacklist)** — Pay-per-request TRON USDT-TRC20 screening for agents, three tiers, all `POST` with `{"address":"T…"}`: `$0.01` `/v1/x402/blacklist` (live Tether `getBlackListStatus` read), `$0.10` `/v1/x402/screen` (freeze check across three sources + OFAC + OpenSanctions + Chainabuse + explainable risk score), `$1.00` `/v1/x402/report` (full AML report: counterparty exposure, two-hop tracing, flow heuristics, 0-100 score). USDC on Base (`eip155:8453`), payTo `0x820a7bf90d944bb26bfD9b62Ab172Fc3A0829cB9`. Not charged on invalid input or upstream failure. Discovery: https://usdt.chikocorp.com/.well-known/x402.json
- **[agent-exec RPC](https://agent-exec.448c.org/rpc?via=223)** — Accountless JSON-RPC: one call to Base, Base Sepolia, Ethereum or Solana with no provider account, $0.002 USDC per call, your own call id echoed back, a refused call costs nothing. ([OpenAPI](https://agent-exec.448c.org/openapi.json?via=223))
- **[agent-exec Relay](https://agent-exec.448c.org/relay?via=223)** — Gasless USDC relay for wallets holding no gas: sign an EIP-3009 TransferWithAuthorization on Base and agent-exec broadcasts it with its own ETH. $0.02 USDC flat per relay, $100 max per order, a refused order costs nothing. A free 503 `relay_gas_exhausted` fires before any charge if the relayer's own gas key runs dry, instead of a broadcast without a response. ([OpenAPI](https://agent-exec.448c.org/openapi.json?via=223))
- **[agent-exec](https://agent-exec.448c.org/check/address?via=223)** — Address, URL and x402-counterparty risk checks from public risk feeds: verdict, score and reasons, $0.02 USDC flat on Base or Solana, charged only on success. `POST /check/address`, `POST /check/url` and `POST /check/counterparty`. ([OpenAPI](https://agent-exec.448c.org/openapi.json?via=223))
- **[JPVerify](https://api.jpverify.com/.well-known/x402.json)** — Japanese company (corporate number), qualified-invoice (T-number) and address verification against NTA, Japan Post, EDINET and FSA public data: company verify/resolve/report, supplier evidence, T-number and invoice-issuer checks, JP PINT validation, and address normalize/parse/geocode/validate; 18 paid routes at $0.001–$0.25 USDC per call on Base mainnet, settled only after a successful result. Example: `POST /v1/jp/companies/verify {"corporate_number":"1010001008846"}`. ([OpenAPI](https://api.jpverify.com/openapi.json)) ([llms.txt](https://api.jpverify.com/llms.txt)) ([Site](https://www.jpverify.com))
- **[JPVerify MCP](https://api.jpverify.com/mcp)** — Remote streamable-http MCP wrapper over the JPVerify HTTP API with 9 tools for Japanese company (corporate number) verification and English-name resolution, supplier evidence, qualified-invoice T-number and invoice-issuer checks, and address normalization and validation; `jpverify_guide` and `jpverify_balance` are free and paid tools cost $0.005–$0.25 USDC on Base via x402, settled only after a successful result. Example tool call: `jp_invoice_registration_verify {"registration_number":"T1013301046627"}`. ([Manifest](https://api.jpverify.com/.well-known/x402.json)) ([Registry](https://registry.modelcontextprotocol.io/v0.1/servers?search=com.jpverify))
- **[Horizon Pulse](https://horizonpulse.dev/.well-known/x402)** — Returns crypto market data (BTC/ETH/SOL pulse, RSI/MACD/Bollinger signals, DefiLlama yields, Base+Ethereum wallet portfolio, gas, OKX funding) and web utilities (URL to markdown, SSRF-safe HTTP proxy, structured page extract) for $0.005-$0.04 USDC per call on Base mainnet via x402 v2. Example: `GET /api/pulse`. ([OpenAPI](https://horizonpulse.dev/openapi.json)) ([llms.txt](https://horizonpulse.dev/llms.txt))
- **[Go Bag](https://gobagesim.com/buy)** — Prepaid travel eSIM data plans for a person's phone or tablet, bought by an AI agent per order in USDC on Base via x402, from $0.99 with no account, sign-up or ID; plans are listed free at `GET /catalog`, and an empty `POST /buy` answers 402 without buying anything.
- **[Aura Verification](https://aura-home.aura-5d4.workers.dev/.well-known/x402)** — Deterministic checks for agents and x402 sellers: verify a public HTTPS page's reachability, backlink, canonical URL, noindex and content digest ($0.005 USDC), or audit an unpaid x402 v2 endpoint's challenge, price, asset, network and discovery ($0.05 USDC). Base, no API key. Example: `POST /x402/verify {"url":"https://www.cloudflare.com/"}`.
- **[AgentSearch](https://api.agentsearchhq.com/.well-known/x402)** — Web search ($0.008), page-to-Markdown extract ($0.007) and headless-browser render for JavaScript pages ($0.010), USDC per call on Base via x402 v2 and the Coinbase CDP facilitator, settled only after a successful, non-empty answer. Example: `POST /x402/v1/search {"query":"x402"}`. ([Docs](https://agentsearchhq.com/docs/x402)) ([OpenAPI](https://api.agentsearchhq.com/openapi.json)) ([llms.txt](https://agentsearchhq.com/llms.txt))
- **[Scrapling Data](https://scraplingdata.xyz/.well-known/x402)** — Pay-per-call crypto, DeFi, prediction-market, stock and GPU-price datasets and lookups for AI agents via x402 (USDC on Base, Polygon, Arbitrum or Solana; USDC or USDT on BNB Chain). Example: `GET /v1/lookup/coin?coin=bitcoin`. ([MCP](https://scraplingdata.xyz/mcp)) ([OpenAPI](https://scraplingdata.xyz/openapi.json)) ([llms.txt](https://scraplingdata.xyz/llms.txt))
- **[StockDatum](https://api.stockdatum.com/v1/form4?ticker=AAPL)** — Structured SEC EDGAR records (Form 4, 8-K/6-K, Form 144, insider purchase clusters) with a source-filing link per row, $0.02 per call ($0.03 clusters) in USDC on Base. Example: `GET /v1/form4?ticker=AAPL`.
- **[SatBotly](https://satbotly.com/apis)** — Free, source-checked directory of what AI agents can pay for on their own: x402, L402 and MPP pay-per-call APIs priced from their unpaid HTTP 402 challenge (nothing is paid to read a price), plus agent wallets, payment services and MCP servers. ([llms.txt](https://satbotly.com/llms.txt))
- **[HTML Pack](https://174-138-26-48.sslip.io/v1/html-to-markdown)** — Converts one caller-supplied HTML document to Markdown for 0.002 USDC on Base via x402 v2. Example: `POST /v1/html-to-markdown {"html":"<h1>Hi</h1><p>Hello</p>"}`. ([OpenAPI](https://174-138-26-48.sslip.io/openapi.json))
- **[Bot Agora x402 Q&A desk](https://agora-x402-desk.sirgrokkius.workers.dev/ask?question=hello)** — Pay-per-answer AI Q&A (`GET /ask?question=...`) and bash lint (`POST /lint`) for agents at 10 sats sBTC on Stacks mainnet via the AIBTC x402 relay; `POST /lint/free` and `GET /health` are free. Example: `GET /ask?question=hello`.
<!-- NEW-THIS-WEEK:END -->

---

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sections/quickstart-dark.svg">
  <img src="assets/sections/quickstart-light.svg" alt="Section: Quick Start" width="680">
</picture>

## Quick Start

> **New to x402?** Three steps to your first payment.

**1. Pick a facilitator**

| Use case | Facilitator |
|----------|-------------|
| Most chains, full SDK support | [Coinbase CDP](https://docs.cdp.coinbase.com/x402) |
| Edge deployment, global latency | [Cloudflare x402](https://developers.cloudflare.com/agents/tools/payments/x402/) |
| Enterprise billing + disputes | [Stripe Machine Payments](https://docs.stripe.com/payments/machine/x402) |

**2. Install the SDK**

```bash
# TypeScript
npm install x402-express        # or the core package: @coinbase/x402

# Python
pip install x402
```

```bash
# Rust
cargo add x402-axum x402-reqwest   # x402-rs — see SDKs & Libraries shelf
```

_Checked 2026-09-20. A crate literally named `x402` exists on crates.io but is a placeholder
with no working code — use `x402-rs`'s crates (`x402-axum` for servers, `x402-reqwest` for
clients) instead._

**3. Add payment middleware**

```typescript
import { paymentMiddleware } from '@coinbase/x402-express';

app.use(paymentMiddleware(wallet, {
  '/api/data': { price: '$0.01', network: 'base-mainnet' }
}));
```

That's it. The middleware returns 402 with payment details, verifies the client's payment header, and lets the request through.

[Full quickstart →](https://docs.cdp.coinbase.com/x402/quickstart-for-sellers) · [Testnet setup →](https://docs.cdp.coinbase.com/x402/network-support)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sections/howitworks-dark.svg">
  <img src="assets/sections/howitworks-light.svg" alt="Section: How x402 Works" width="680">
</picture>

## How x402 Works

```
1. Client  →  GET /api/data                              (initial request)
2. Server  ←  402 Payment Required                       (payment details in header)
               payment-required: <base64 challenge>       (v2; v1 used X-Payment-Required
                                                           and put the detail in the body)
3. Client  →  EIP-3009 gasless USDC transfer             (client signs + submits)
4. Client  →  GET /api/data  +  X-Payment: {signed tx}  (retry with payment)
5. Facilitator  →  verify + settle on-chain              (~2 seconds)
6. Server  ←  200 OK  +  X-Payment-Response              (resource returned)
```

No gas for the sender. No subscription. No API key. Payment IS authentication.

[Protocol spec →](https://github.com/coinbase/x402) · [EIP-3009 →](https://eips.ethereum.org/EIPS/eip-3009)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sections/needmore-dark.svg">
  <img src="assets/sections/needmore-light.svg" alt="Section: Need More?" width="680">
</picture>

## Need More?

This README is the front door. The full curated directory — every shelf, every entry — is in [`directory/`](directory/).

**Other lists worth knowing:** the community [awesome-x402](https://github.com/xpaysh/awesome-x402) accepts everything and is the right place for exhaustive coverage. [Glama](https://glama.ai/mcp/servers) indexes MCP servers at enormous scale and publishes its own health data, which is rarer than it should be. Different jobs. Use all three.

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sections/contributing-dark.svg">
  <img src="assets/sections/contributing-light.svg" alt="Section: Contributing" width="680">
</picture>

## Contributing

gold-402 is curated, not exhaustive. Every entry earns its place.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the curation standard, badge system, acceptance criteria, and submission process.

**Quick rules:**
- Entry must use the x402 protocol (HTTP 402 + X-Payment), not just USDC or general crypto payments.
- Live URL or public GitHub repo. Link must work.
- Last activity within 12 months (for libraries and resources without a live endpoint).
- One entry per pull request. Format: `[Name](url) — Description starting uppercase, ending with period.`
- Descriptions are factual. No marketing language.

---

<p align="center">
  <b>Curated by <a href="https://24klabs.ai">24K Labs</a></b><br>
  <sub>If this saved you time, star the repo.</sub><br><br>
  <a href="https://24klabs.ai">24klabs.ai</a> •
  <a href="https://x402.org">x402.org</a> •
  <a href="https://github.com/coinbase/x402">Protocol Spec</a> •
  <a href="https://docs.cdp.coinbase.com/x402">Coinbase Docs</a> •
  <a href="https://discord.gg/x402">Discord</a> •
  <a href="https://agenteconomy.to">Live Dashboard</a>
</p>
