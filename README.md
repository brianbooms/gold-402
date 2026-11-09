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

**This week** (Nov 9—15)

- **[TRON USDT Risk Checker](https://usdt.chikocorp.com/v1/x402/blacklist)** — Pay-per-request TRON USDT-TRC20 screening for agents, three tiers, all `POST` with `{"address":"T…"}`: `$0.01` `/v1/x402/blacklist` (live Tether `getBlackListStatus` read), `$0.10` `/v1/x402/screen` (freeze check across three sources + OFAC + OpenSanctions + Chainabuse + explainable risk score), `$1.00` `/v1/x402/report` (full AML report: counterparty exposure, two-hop tracing, flow heuristics, 0-100 score). USDC on Base (`eip155:8453`), payTo `0x820a7bf90d944bb26bfD9b62Ab172Fc3A0829cB9`. Not charged on invalid input or upstream failure. Discovery: https://usdt.chikocorp.com/.well-known/x402.json
- **[agent-exec RPC](https://agent-exec.448c.org/rpc?via=223)** — Accountless JSON-RPC: one call to Base, Base Sepolia, Ethereum or Solana with no provider account, $0.002 USDC per call, your own call id echoed back, a refused call costs nothing. ([OpenAPI](https://agent-exec.448c.org/openapi.json?via=223))
- **[agent-exec Relay](https://agent-exec.448c.org/relay?via=223)** — Gasless USDC relay for wallets holding no gas: sign an EIP-3009 TransferWithAuthorization on Base and agent-exec broadcasts it with its own ETH. $0.02 USDC flat per relay, $100 max per order, a refused order costs nothing. A free 503 `relay_gas_exhausted` fires before any charge if the relayer's own gas key runs dry, instead of a broadcast without a response. ([OpenAPI](https://agent-exec.448c.org/openapi.json?via=223))
- **[agent-exec](https://agent-exec.448c.org/check/address?via=223)** — Address, URL and x402-counterparty risk checks from public risk feeds: verdict, score and reasons, $0.02 USDC flat on Base or Solana, charged only on success. `POST /check/address`, `POST /check/url` and `POST /check/counterparty`. ([OpenAPI](https://agent-exec.448c.org/openapi.json?via=223))

**Last week** (Nov 2—8)

- **[AgentForge](https://agentforge-taupe.vercel.app/.well-known/x402)** — DeFi safety APIs for agents: pre-sign EVM transaction simulation, sanctions and scam address screening, a risk-scored new-token launch feed, batch token rug checks, Aave liquidation risk, and transaction decode; 24 endpoints, $0.001-$0.35 USDC on Base or Solana. Example: `POST /v1/address-check {"address":"0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48"}`. ([MCP](https://agentforge-taupe.vercel.app/mcp)) ([OpenAPI](https://agentforge-taupe.vercel.app/openapi.json))
- **[SCRYX Merchant Intelligence](https://scryx-api.onrender.com/merchant/intelligence)** — Returns structured public-commerce evidence for one merchant homepage with explicit unknowns; POST only, $0.05 USDC per call on Base mainnet via x402 v2. Example: `POST /merchant/intelligence {"url":"https://merchant.example"}`. ([Discovery](https://scryx-api.onrender.com/.well-known/x402)) ([OpenAPI](https://scryx-api.onrender.com/openapi.json)) ([llms.txt](https://scryx-api.onrender.com/llms.txt))
- **[Crypto Pulse](https://cryptopulseapi.com/v1/pulse)** — BTC/ETH/SOL/HYPE spots with 24h change, Fear & Greed, Hyperliquid funding and open interest, and DefiLlama TVL plus top stable yields in one call with a plain-English summary; $0.02 USDC per pulse and $0.005 for spots-only on Solana via x402, with a free stale sample and Streamable HTTP MCP. Example: `GET /v1/pulse`. ([OpenAPI](https://cryptopulseapi.com/openapi.json)) ([Discovery](https://cryptopulseapi.com/.well-known/x402)) ([MCP](https://cryptopulseapi.com/mcp)) ([GitHub](https://github.com/midnight232/crypto-pulse-api))
- **[Project Zero Cited Briefs](https://preview-chat-985505b1-9dc0-470f-9fc3-3704d8b625e3.space-z.ai/api/x402/research-brief)** — Cited research briefs from the live web: the Research Brief endpoint searches, reads 3-6 sources and returns a structured JSON brief with source-linked findings ($0.05), Quick Brief returns a snippet-level digest ($0.01), and Wallet Balance looks up native balances across BTC/ETH/Base/Sol/Tron/Ronin ($0.001); USDC per call on Base mainnet, failed calls are not charged. Catalog: [llms.txt](https://preview-chat-985505b1-9dc0-470f-9fc3-3704d8b625e3.space-z.ai/llms.txt).
- **[Trench Lessons](https://trench-lessons.vercel.app/.well-known/x402)** — Solana meme coin research for trading bots: read-only heuristic flags for a mint (curve-skip PumpSwap pool, unlocked LP, Mayhem mode, bundle handoff), each with status and confidence, $0.01, and a structured daily findings feed on pump.fun, PumpSwap and Meteora with sources, $0.005. USDC on Solana and Base via PayAI, x402 v2 exact, no API key. Example: `GET /api/signals/risk?mint=DFMt2FyLpB6ekPNAzVErLXgpSnJ9CRf1VnxBAkTLpump`. ([OpenAPI](https://trench-lessons.vercel.app/openapi.json)) ([llms.txt](https://trench-lessons.vercel.app/llms.txt))
- **[AskZephy Solana Audit](https://audit.askzephy.com/audit)** — Static PATTERN scan of a Solana/Anchor Rust repository: flags risky code shapes (missing signer/owner checks, account confusion, PDA seed issues, unsafe CPI, unchecked arithmetic) with file:line, evidence and suggested fix. Deterministic, no LLM. $0.05 USDC on Base per `GET /audit?repo=owner/name`; one-line verdict at `GET /quick-scan?repo=owner/name` for $0.005. Honest limits: scored 0/11 recall on Anchor's labelled vulnerability corpus — findings are leads for human review, not an audit verdict. ([OpenAPI](https://audit.askzephy.com/openapi.json))
- **[useful-work-agent](https://github.com/dav3trad3r/useful-work-agent)** — MIT TypeScript agent and tool-maker kit for the useful-work x402 extension: the agent pays for x402 calls by passing a proofreading or link-check job instead of paying USDC, and a tool maker's server can offer those jobs and is paid 0.002 USDC per passed check on Base. ([npm](https://www.npmjs.com/package/useful-work-agent))
- **[Goldsky Edge RPC](https://edge.goldsky.com/standard/evm/8453)** — Pay-per-call EVM JSON-RPC across 150+ chains, 5 atomic USDC ($0.000005) per call, x402 or API key. The 402 challenge asks for a 5000 atomic USDC ($0.005) prepaid top-up, which funds about 1,000 calls.
- **[Goldsky Feeds: Prediction markets and Chain datasets](https://edge.goldsky.com/data/blocks/base?number=1)** — Pay-per-call Polymarket activity and EVM block data, 10 atomic USDC ($0.00001) per request flat. The 402 challenge asks for a 5000 atomic USDC ($0.005) prepaid top-up, which funds about 500 requests.
- **[Goldsky Feeds: Wallets and Tokens](https://edge.goldsky.com/data/feeds/wallets/balances?address=0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045)** — Pay-per-call wallet balances, transfers, and token prices, 350 atomic USDC ($0.00035) per request. The 402 challenge asks for a 50000 atomic USDC ($0.05) prepaid top-up, which funds about 142 requests.
- **[Useful Work tools](https://tools.usefulwork.app/tools/read-page?url=https://example.com/)** — Reads a public web page as text, checks up to 15 links on a page, or looks up DNS records (A, AAAA, CNAME, MX, NS, TXT, CAA) for 0.002 USDC per call on Base via x402 v2, or lets an agent that sends an X-Useful-Work-Agent header pay by passing a checkable job instead. Example: `GET /tools/dns?name=example.com&type=A`.
- **[x402-sanctions-guard](https://github.com/acarchidi/x402-sanctions-guard)** — Express and Hono middleware for x402 sellers that screens each payer wallet against OFAC sanctions and scam-wallet lists and refuses it with a 403 before the payment is verified or settled; payer extraction for EVM (EIP-3009, Permit2) and Solana payments, per-payer cache, screening via AgentForge at $0.003 per new payer. MIT.
- **[aptu.dev](https://aptu.dev)** — Machine-payable API microservices for agents: echo probe (`POST /v1/echo`, $0.01), resume ATS scoring (`POST /v1/resume-eval`, $0.005), domain agent-readiness audit (`POST /v1/agent-readiness`, $0.05), and BTC market regime check (`GET /v1/btc-regime`, $0.003), USDC via x402 on Base and Solana, no account or API key. Example: `POST /v1/echo {"message":"hello"}`. ([OpenAPI](https://aptu.dev/v1/openapi.json)) ([Manifest](https://aptu.dev/.well-known/x402))
- **[OceanAlt](https://oceanalt.com/.well-known/x402)** — Pre-payment check for agents: takes a payee address and returns allow, review or decline with supporting evidence. $0.002 USDC per call on Base, X Layer or Solana.
- **[Momentum Brief](https://momentum-brief.fly.dev/v1/brief)** — Pay-per-call 8–12 line crypto momentum brief (price, 24h/7d change, market cap, trending rank, top DEX pair, liquidity, volume, buy/sell mix) cited to CoinGecko or DexScreener; $0.10 USDC on Base via x402, no account; not trading advice; no charge if no data. Example: `POST /v1/brief {"query":"ETH"}`. ([OpenAPI](https://momentum-brief.fly.dev/openapi.json)) ([Pricing](https://momentum-brief.fly.dev/.well-known/pricing))
- **[Indo News MCP](https://indo-news-api.vercel.app/mcp)** — Remote MCP server for Indonesian news and data: headlines by topic with entities and sentiment, keyword search, a delta feed with a since-cursor, briefings, a deterministic 0-100 sentiment index, coverage timelines and an 8-topic digest, plus USD/IDR and any published pair with a 30-day series, crypto prices in rupiah from Indodax, the Indodax-vs-global premium, BMKG earthquakes and public holidays. 31 tools, 8 free and 23 paid. Paid tools answer an unpaid call with an x402 PaymentRequired payload ($0.05–$2.50 USDC per call for the 19 news and data tools, Base, Polygon, Arbitrum or Avalanche); free preview tools return a 3-item sample of the same shape the paid tools fill to 25. The same service also sells a $49 written 30-day coverage report and unmetered licences over HTTP that differ by scope: $19/$99 for 30 days, $399 for 30 days with 1,825 prints per call of FX history, $700 for 90 days with 3,650 prints per call. ([Manifest](https://indo-news-api.vercel.app/.well-known/x402)) ([OpenAPI](https://indo-news-api.vercel.app/openapi.json)) ([llms.txt](https://indo-news-api.vercel.app/llms.txt))
- **[Indo News API](https://indo-news-api.vercel.app/headlines)** — Indonesian news and reference data for agents: headlines by topic, keyword search, deduped briefings with keyword trends and top sources, an all-topics digest, FX for published pairs with daily history beyond 30 days, rupiah crypto prices, BMKG earthquake alerts, holiday and working-day decisions, and a public-page reader. $0.05–$2.50 USDC per call on the 20 news and data routes, settled by x402 v2 on Base, Polygon, Arbitrum or Avalanche (PayAI facilitator) or by MPP on Tempo from the same 402, plus a $49 written coverage report and unmetered Bearer licences from $19/30 days to $700/90 days. Example: `GET /headlines?topic=finance`. ([OpenAPI](https://indo-news-api.vercel.app/openapi.json)) ([llms.txt](https://indo-news-api.vercel.app/llms.txt)) ([Manifest](https://indo-news-api.vercel.app/.well-known/x402))
- **[Indo News API](https://indo-news-api.vercel.app/indonesia)** — Indonesian data for agents over 25 paid GET routes and 31 MCP tools at `POST /mcp` (8 free): up to 25 headlines by topic, keyword search, a deduped delta feed with a since-cursor, recency-ranked briefings, an 8-topic digest, a brand coverage monitor, a deterministic 0-100 sentiment index, USD/IDR and any published pair with a 30-day series plus /series daily history beyond it, a currency converter, BTC/ETH/USDT in rupiah from Indodax plus the Indodax-vs-global premium, BMKG earthquakes with an `?alert=true&minMagnitude=5` alert view, public holidays with working-day, next-working-day and single-date checks, and a `/read` clean-text page reader. $0.05–$2.50 USDC per call on the 20 news and data routes, settled by x402 v2 on Base, Polygon, Arbitrum or Avalanche or by MPP on Tempo from the same 402, plus a $49 written 30-day coverage report and unmetered licences that differ by enforced scope: $19 and $99 for 30 days ($99 raises /series to 365 prints per call), $399 for 30 days with 1,825 prints per call, $700 for 90 days with 3,650 prints per call — the top two also take the whole series as one `?format=csv|jsonl` download; no API keys, free samples (the export file shape is free at `/series/preview?format=csv`, with the series hash so depth can be checked before paying). Example: `GET /headlines?topic=finance`. ([OpenAPI](https://indo-news-api.vercel.app/openapi.json)) ([llms.txt](https://indo-news-api.vercel.app/llms.txt)) ([Manifest](https://indo-news-api.vercel.app/.well-known/x402)) ([MCP](https://indo-news-api.vercel.app/mcp))
- **[Penny x402 utilities](https://pennyagent.pythonanywhere.com/paid/hash?s=hello)** — Small dev utilities per call: hash digests, base64, UUID, slug, URL parse, time, Nostr NIP-19 decode and event verify, BOLT11 invoice decode. $0.001 USDC on Base. Example: `GET /paid/hash?s=hello&alg=sha256`. Also a remote MCP server at https://pennyagent.pythonanywhere.com/mcp (registry: io.github.pennyops/penny-x402-utils).
- **[Meridian by MioDio](https://meridian.miodiollc.com/.well-known/x402)** — Read-only pre-sign checks for agents on Base USDC via x402: OFAC SDN exact-match address screen, intent-drift check, transaction dry run, recipient readiness and x402 preflight, $0.005 to $0.10 per call.
- **[x402nic by easyDNS](https://app.domainhelp.com/.well-known/x402)** — Registers domain names and provisions them into easyDNS accounts using x402 v2 USDC payments on Base, with domain-specific quotes and a prepared registration order required before payment. ([Website](https://x402nic.com)) ([Registration workflow](https://dnsskills.md/register-domain/SKILL.md)) ([OpenAPI](https://dnsskills.md/register-domain/openapi.yaml))
- **[JPVerify](https://api.jpverify.com/.well-known/x402.json)** — Japanese business document OCR and public-registry verification: receipt, invoice and business-card extraction, corporate-number and qualified-invoice (T-number) checks against NTA public data, and Japanese address normalization; 24 paid routes at $0.001–$0.10 USDC per call on Base mainnet, with invalid input rejected with HTTP 422 before payment. Example: `POST /jp-company/verify {"corporate_number":"1010001008846"}`. ([OpenAPI](https://api.jpverify.com/openapi.json)) ([llms.txt](https://api.jpverify.com/llms.txt)) ([Site](https://www.jpverify.com))
- **[JPVerify MCP](https://api.jpverify.com/mcp)** — Remote streamable-http MCP wrapper over the JPVerify HTTP API with 12 tools for Japanese company (corporate number) and qualified-invoice T-number verification, address normalization and validation, invoice/receipt/business-card OCR, supplier resolution, and EU VAT/Peppol counterparty checks; `jpverify_guide` is free and paid tools cost $0.005–$0.10 USDC on Base via x402, settled only after a successful result. Example tool call: `jp_invoice_registration_verify {"registration_number":"T1013301046627"}`. ([Manifest](https://api.jpverify.com/.well-known/x402.json)) ([Registry](https://registry.modelcontextprotocol.io/v0.1/servers?search=com.jpverify))
- **[Vauban Pay Facilitator](https://pay.vauban.tech/x402-tiers-base-mainnet/supported)** — Public x402 facilitator for exact USDC payments on Base (eip155:8453) and Base Sepolia (eip155:84532), x402 v2, open /supported, /verify and /settle without API key; third-party sellers register with a per-seller split contract and withdraw themselves. [Docs](https://pay.vauban.tech/#sell).
- **[BSC Agent Utilities](https://bsc-agent-utilities.raninndia.workers.dev)** — 8 pay-per-call utility APIs for AI agents at $0.001 USDC per call on Base via x402 v2, no API key: BSC gas price, token price, tx status, contract safety check, email check, IP lookup, WHOIS, and QR code. Example: `GET /v1/gas`. ([OpenAPI](https://bsc-agent-utilities.raninndia.workers.dev/openapi.json)) ([Discovery](https://bsc-agent-utilities.raninndia.workers.dev/.well-known/x402))
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
