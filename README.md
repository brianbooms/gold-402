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

**This week** (Oct 19—25)

_No new listings yet._

**Last week** (Oct 12—18)

- **[nano-invoice](https://github.com/dhyabi2/nano-invoice#use-with-an-x402-seller)** — Python library for the settlement side of an x402 seller on Nano (XNO): an invoice's per-request tagged amount becomes the `amount` of a `nano:mainnet` entry in `accepts[]` beside the existing USDC entry, and the payment is settled from the Nano ledger, one block per invoice, with refunds addressed to the sender the ledger names.
- **[Verdix](https://api.verdixapi.com/.well-known/x402.json)** — Checks an EVM address on Base before an agent sends funds to it: OFAC sanctions, scam/phishing lists, live address-poisoning detection, and flagged deployers, answering safe, caution, or danger, $0.01-$0.50 USDC per call, never charged if the check can't complete.
- **[DrinkedIn data feeds](https://drinkedin.net/.well-known/x402)** — Records of licensed bars and venues from public alcohol-licensing registers, cocktail recipes, and venue-economy analytics for a fictional AI-agent bar simulation; large requests return an x402 v2 402 (`accepts` plus `Payment-Required` header) quoting USDC on Base, `exact` scheme. Pay either with standard x402 (retry with a signed `X-PAYMENT` header) or by a direct USDC transfer, then a retry with `payment_id` + `tx_hash`. Example: `GET /api/data/v1/cocktails?limit=1000` (returns 402). ([OpenAPI](https://drinkedin.net/openapi.json)) ([Agent guide](https://drinkedin.net/llms.txt)) ([MCP](https://ai.drinkedin.net/mcp))
- **[Kalshi ETH Hourly Signal](https://backend-production-69ff.up.railway.app/x402/signal/eth-hourly)** — Current model signal for Kalshi's ETH hourly above/below markets (KXETHD) from the same volatility model as the BTC signal, which trades these contracts with real money: the near-the-money strike where model and market disagree most, with model probability, market probability, edge and suggested side (yes/no); returns `signal: null` when no near-the-money market is open. Read-only data, not financial advice. $0.02 USDC per call on Base. Example: `GET /x402/signal/eth-hourly`. ([OpenAPI](https://backend-production-69ff.up.railway.app/openapi.json))
- **[Kalshi SOL Hourly Signal](https://backend-production-69ff.up.railway.app/x402/signal/sol-hourly)** — Current model signal for Kalshi's SOL hourly above/below markets (KXSOLD) from the same volatility model as the BTC and ETH signals: the near-the-money strike where model and market disagree most, with model probability, market probability, edge and suggested side (yes/no); returns `signal: null` when no near-the-money market is open. Read-only data, not financial advice. $0.02 USDC per call on Base. Example: `GET /x402/signal/sol-hourly`. ([OpenAPI](https://backend-production-69ff.up.railway.app/openapi.json))
- **[Open Rails Data Agent](https://open-rails-data-agent.shablony-pro.workers.dev/.well-known/x402)** — Seven pay-per-call x402 data endpoints on Celo mainnet for blocks, gas prices, wallet and token balances, transactions, receipts and ERC-8004 identity URIs, priced at 0.0005-0.002 USDC per call with no API keys. ([GitHub](https://github.com/Alex20Sas12/x402-open-rails-agent))
- **[Liam Tools Merchant Connect](https://liam-tools-merchant-connect.evangrant69420.workers.dev/v1/merchant-connect)** — Generates an 11-file business-specific x402 digital-service integration kit with catalog, OpenAPI, XRP gateway, persistent receipts, protected delivery, and an authorized Cloudflare installer; GET /v1/merchant-connect returns an x402 v2 challenge for 1 XRP on XRPL or 2 USDC on Base (RLUSD and Solana USDC also quoted), and paid POST with the [documented business catalog](https://liam-tools-merchant-connect.evangrant69420.workers.dev/skill.md) returns the kit. [Human checkout](https://liam-tools-merchant-connect.evangrant69420.workers.dev/) | [OpenAPI](https://liam-tools-merchant-connect.evangrant69420.workers.dev/openapi.json).
- **[Automaton-Sovereign](https://api.automatonsvrn.xyz/.well-known/x402)** — Pre-flight safety checks for Base before an agent signs: EVM bytecode analysis with honeypot and mint-backdoor detection (`GET /v2/security/scan?address=0x833589fCD6eDb6E08f4c7C32D4f71b54bdA02913`, $0.001), ERC-20 allowance and unlimited-approval drain risk (`POST /v2/token/approval-risk`, $0.01, body `{"token":"0x…","owner":"0x…"}`), unsigned-transaction simulation with anti-revert check (`POST /v2/firewall/simulate-tx`, $0.02, body `{"targetContract":"0x…","calldata":"0x…"}`), Base pool depth and liquidity telemetry, signed oracles and attestations — 18 paid routes (17 RPC + 1 SSE stream), $0.001–$0.05 USDC per call on Base mainnet via x402 v2 `exact`/EIP-3009, caller-bound and gasless for the buyer through the Coinbase CDP facilitator; no account, no API key, no ETH needed. A free probe validates any other service's 402 challenge before an agent signs: `GET /v1/x402-conformance?url=` (9 named checks, no payment). MCP server with 20 tools at `/mcp` and official Agent Kit SDK. ([Manifest](https://api.automatonsvrn.xyz/.well-known/x402)) ([OpenAPI](https://api.automatonsvrn.xyz/openapi.json)) ([llms.txt](https://api.automatonsvrn.xyz/llms.txt)) ([Agent Kit](https://github.com/baianomarceloeduardo-jpg/automaton-agent-kit))
- **[Hyrule Cloud](https://cloud.hyrule.host/.well-known/x402.json)** — IPv6-native VMs with root SSH from $0.20/day, network diagnostics (DNS, BGP, IP, RDAP/WHOIS, deep TLS, MX, port and NAT checks, VoIP) from $0.001, and one-shot requests over Direct, Tor, I2P or Yggdrasil from $0.01, on its own network AS215932. USDC on Base, Polygon and Arbitrum. Example: `POST /v1/dns/lookup {"name":"example.com","type":"AAAA"}`. ([OpenAPI](https://cloud.hyrule.host/openapi.json)) ([GitHub](https://github.com/AS215932/hyrule-cloud))
- **[GLEE Acceptance Verifier](https://gleephoenix.com/api/x402/verify/patch)** — Deterministic git unified diff acceptance verifier: checks delivered code patches against caller-declared path policies, static safety rules, and literal assertions; returns PASS/FAIL with an offline-verifiable Ed25519 cryptographic receipt. $0.05 USDC on Base mainnet. Includes sub-cent diagnostic health canary at $0.005 USDC (`GET /api/x402/ping`). ([OpenAPI](https://gleephoenix.com/openapi.json)) ([Discovery](https://gleephoenix.com/.well-known/x402)) ([Docs](https://platform.gleephoenix.com/docs/x402))
- **[Horizon Pulse](https://horizonpulse.dev/.well-known/x402)** — Returns crypto market data (BTC/ETH/SOL pulse, RSI/MACD/Bollinger signals, DefiLlama yields, Base+Ethereum wallet portfolio, gas, OKX funding) and web utilities (URL to markdown, SSRF-safe HTTP proxy, structured page extract) for $0.005-$0.04 USDC per call on Base mainnet via x402 v2. Example: `GET /api/pulse`. ([OpenAPI](https://horizonpulse.dev/openapi.json)) ([llms.txt](https://horizonpulse.dev/llms.txt))
- **[Checkpoint402 Transaction Explainer](https://api.checkpoint402.com/v1/tx-explain)** — Explains a Base or Ethereum transaction in plain English with the decoded sender, function called, token and NFT transfers, status and fee, for $0.03 USDC per call on Base. Example: `GET /v1/tx-explain?hash=0x1ddeee1cdb4dd126b56c1f249501e2b48d885eae512602b5321765597bc27c2a&chain=base`. ([OpenAPI](https://api.checkpoint402.com/openapi.json))
- **[Checkpoint402 DeFi Yield Finder](https://api.checkpoint402.com/v1/defi-yields)** — Returns top DeFi pool yields from DefiLlama filtered by asset, chain, minimum TVL and risk tier, with the reasons behind each pool's risk tier, for $0.05 USDC per call on Base. Example: `GET /v1/defi-yields?asset=USDC&chain=Base&limit=5`. ([OpenAPI](https://api.checkpoint402.com/openapi.json))
- **[Checkpoint402 New Token Safety Feed](https://api.checkpoint402.com/v1/new-tokens)** — Lists newly launched token pools on Base, Ethereum or BSC with a 0–100 safety score and red flags from GoPlus (honeypot, mintable, owner powers, high tax, unlocked liquidity), for $0.10 USDC per call on Base. Example: `GET /v1/new-tokens?chain=base&limit=5`. ([OpenAPI](https://api.checkpoint402.com/openapi.json))
- **[Checkpoint402 Company Events (SEC 8-K)](https://api.checkpoint402.com/v1/company-events)** — Returns the latest SEC 8-K filings market-wide or for one ticker, with item codes in plain English, high-impact events flagged and AI summaries of the filing text, for $0.10 USDC per call on Base. Example: `GET /v1/company-events?ticker=AAPL&limit=3`. ([OpenAPI](https://api.checkpoint402.com/openapi.json))
- **[Checkpoint402 Sanctions Screening](https://api.checkpoint402.com/v1/sanctions-screen)** — Screens a person or company name (fuzzy, alias-aware) and/or a crypto wallet address against the US Treasury OFAC SDN list including its extended remarks, for $0.05 USDC per call on Base; informational, not a compliance determination. Example: `GET /v1/sanctions-screen?address=0x098B716B8Aaf21512996dC57EB0615e2383E2f96`. ([OpenAPI](https://api.checkpoint402.com/openapi.json))
- **[Agent Hub](https://agents.torbrooknews.com/.well-known/x402)** — 48 pay-per-call tools for agents behind one wallet: web search, page-to-Markdown, scraping and JSON extraction, PDF and screenshots, LLM chat, speech-to-text and text-to-speech, translation, image generation and OCR, embeddings and reranking, SEC filings, papers, crypto prices, token risk reports, DeFi yields, perp funding rates and Polymarket odds; $0.002–$0.03 USDC on Base, Polygon, Arbitrum or World Chain, and failed calls are not billed. Example: `GET https://agents.torbrooknews.com/v1/weather?place=Toronto`. ([OpenAPI](https://agents.torbrooknews.com/openapi.json)) ([llms.txt](https://agents.torbrooknews.com/llms.txt)) ([Status](https://agents.torbrooknews.com/status))
- **[Agent Hub MCP](https://mcp.torbrooknews.com/mcp)** — Remote streamable-http MCP server with the 48 Agent Hub tools (web search, scraping, PDF and screenshots, LLM, speech, translation, OCR, embeddings, SEC filings, token risk reports, DeFi yields, perp funding rates, Polymarket odds) plus two prompts and a pricing resource; each tool call is paid via x402 in USDC on Base, Polygon, Arbitrum or World Chain, $0.002–$0.03, and failed calls are not settled. Listed in the official MCP Registry as `com.torbrooknews.mcp/agent-hub`. Example tool call: `weather {"place":"Toronto"}`. ([HTTP API](https://agents.torbrooknews.com/.well-known/x402)) ([Smithery](https://smithery.ai/servers/citiviewgroup/agent-hub)) ([Status](https://agents.torbrooknews.com/status))
- **[Softbot Reader](https://softbot-reader-mainnet.softbot.workers.dev/.well-known/x402)** — Converts a public web page URL to clean markdown, $0.003 USDC per call on Base or Solana via x402. `POST /v1/read {"url":"https://example.com"}`
- **[BTC Intel](https://9eouter-0f49c8.abyte.my.id/.well-known/x402)** — Live Stacks/Bitcoin market intelligence for AI agents: STX/BTC/USD spot, STX-BTC ratio and sats-per-STX; live PoX cycle (stacked ustx, cycle phases, block height); Bitcoin fee tiers plus Stacks mempool fee recommendations; sBTC supply on Stacks; npm/PyPI dependency version and health lookups. Dual-rail x402: USDC on Base (eip155:8453) or STX on Stacks mainnet, $0.01/call, no API keys or accounts. Example: `GET /market`. ([OpenAPI](https://9eouter-0f49c8.abyte.my.id/openapi.json)) ([llms.txt](https://9eouter-0f49c8.abyte.my.id/llms.txt)) ([Discovery](https://9eouter-0f49c8.abyte.my.id/.well-known/x402))
- **[Base Wallet Profile API](https://x402-wallet-profile-api-production.up.railway.app/wallet/0x0000000000000000000000000000000000000001)** — Returns a Base wallet activity profile with native balance, transaction counts, token transfers, first/last activity, and a heuristic 0–100 activity score; $0.01 USDC per GET via x402. History fields can be null when upstream data is unavailable.
- **[exhibit402](https://exhibit402.dylan-caponi.workers.dev/.well-known/x402)** — Dual-cloud evidence capture: two independently hosted, pinned-image browsers (Google Cloud us-west2, Fly.io lax) load a URL at one shared frozen timestamp; byte-identical screenshots are CERTIFIED, divergent ones are WITNESSED with the exact pixel-agreement percentage and a diff map. Every certificate carries a signed manifest, an RFC 3161 timestamp from an independent authority, and a canonical screenshot stored permanently on Arweave (SHA-256 + IPFS CIDv1); an ERC-721 certificate mints to the paying wallet on Base from a contract with no setter, burn, or upgrade path. $1.00 fullpage, $0.50 viewport, $0.02 to re-verify an existing certificate against Arweave and the chain. USDC on Base via the CDP facilitator. Example: `POST https://exhibit402.dylan-caponi.workers.dev/capture {"url":"https://en.wikipedia.org/wiki/SHA-2","mode":"viewport"}`. ([OpenAPI](https://exhibit402.dylan-caponi.workers.dev/openapi.json)) ([llms.txt](https://exhibit402.dylan-caponi.workers.dev/llms.txt))
- **[Softbot Token Check](https://softbot-tokencheck-mainnet.softbot.workers.dev/.well-known/x402)** — Returns a safe/caution/avoid verdict with reasons for a Solana token mint, $0.01 USDC per call on Base or Solana via x402. `POST /v1/check {"mint":"<solana mint>"}`
- **[Softbot Email Check](https://softbot-emailcheck-mainnet.softbot.workers.dev/.well-known/x402)** — Checks email address and domain deliverability signals without mailbox probing, $0.002 USDC per call on Base or Solana via x402. `POST /v1/email {"email":"a@example.com"}`
- **[AgentRXI](https://agentrxi.com/.well-known/x402)** — 232 pay-per-call tools for agents behind one wallet: 22 OpenAI-compatible LLMs priced per token, web search and crawling, a rentable browser, code sandbox, OCR and Office conversion, ffmpeg media conversion, vision (ask about or locate objects in images), image generation, email sending, multi-agent rooms and task queues, file storage, SQL and vector memory, UK KYB and Know-Your-Agent wallet checks, US economic data and maps. From $0.002 per call in USDC on Base, Polygon, Arbitrum or World Chain; failed calls are never charged. ([Site](https://agentrxi.com)) ([OpenAPI](https://agentrxi.com/openapi.json)) ([llms.txt](https://agentrxi.com/llms.txt))
- **[AgentRXI MCP](https://mcp.agentrxi.com/mcp)** — Remote streamable-http MCP server with all 232 AgentRXI tools (22 OpenAI-compatible LLMs, web search, a rentable browser, code sandbox, OCR and Office conversion, ffmpeg media conversion, vision, image generation, email sending, multi-agent rooms and task queues, storage, KYB and wallet trust checks) plus two prompts and a pricing resource; each tool call is paid via x402 in USDC on Base, Polygon, Arbitrum or World Chain, from $0.002. ([Site](https://agentrxi.com)) ([MCP Registry: com.agentrxi.mcp/agentrxi](https://registry.modelcontextprotocol.io/v0/servers?search=com.agentrxi.mcp/agentrxi))
- **[Solana Token Risk Check](https://x402-agent-tools.vercel.app/v1/solana/token-risk)** — Reports a Solana SPL or Token-2022 mint's mint and freeze authority, Metaplex metadata mutability, top-10 holder concentration, DexScreener liquidity and token age with a risk verdict, for $0.02 USDC per call on Base or Solana. Example: `GET /v1/solana/token-risk?mint=DezXAZ8z7PnrnRJjz3wXBoRgixCa6xjnB7YaB1pPB263`. ([Discovery](https://x402-agent-tools.vercel.app/.well-known/x402))
- **[Solana Token Risk Check](https://api.gptshopltd.com/v1/solana/token-risk)** — Reports a Solana SPL or Token-2022 mint's mint and freeze authority, Metaplex metadata mutability, top-10 holder concentration, DexScreener liquidity and token age with a risk verdict, for $0.01 USDC per call on Base or Solana. Example: `GET /v1/solana/token-risk?mint=DezXAZ8z7PnrnRJjz3wXBoRgixCa6xjnB7YaB1pPB263`. ([Discovery](https://api.gptshopltd.com/.well-known/x402))
- **[Base Token Risk Check](https://api.gptshopltd.com/v1/base/token-risk)** — Reports an ERC-20 on Base for honeypot/tax/owner-privilege flags (GoPlus), verified source, proxy/mint/pause/blacklist, top-10 holder share, DexScreener liquidity and pool age with a risk verdict, for $0.01 USDC per call on Base or Solana. Example: `GET /v1/base/token-risk?address=0x833589fcd6edb6e08f4c7c32d4f71b54bda02913`. ([OpenAPI](https://api.gptshopltd.com/openapi.json))
- **[Web Page to Clean Markdown](https://api.gptshopltd.com/v1/web/markdown)** — Fetches a public URL, strips nav/ads/scripts with Mozilla Readability, and returns clean Markdown plus title, byline, site, publish date, language and word count, for $0.005 USDC per page on Base or Solana. Example: `GET /v1/web/markdown?url=https://en.wikipedia.org/wiki/HTTP_402`. ([OpenAPI](https://api.gptshopltd.com/openapi.json))
- **[LLM Token Price Feed](https://api.gptshopltd.com/v1/prices/llm)** — Current USD per 1M input/output token prices for ~300 LLMs from OpenRouter's public model list (refreshed every 5 min); optional `q` filters by model id/name, for $0.002 USDC per call on Base or Solana. Example: `GET /v1/prices/llm?q=gpt-4o`. ([OpenAPI](https://api.gptshopltd.com/openapi.json))
- **[GPU Rental Price Feed](https://api.gptshopltd.com/v1/prices/gpu)** — Current on-demand GPU rental prices (min and median USD per GPU-hour by GPU model) from Vast.ai's public marketplace (refreshed every 5 min); optional `q` filters by GPU name, for $0.002 USDC per call on Base or Solana. Example: `GET /v1/prices/gpu?q=H100`. ([OpenAPI](https://api.gptshopltd.com/openapi.json))
- **[x402 Ping / UUID / Time](https://api.gptshopltd.com/v1/util/ping)** — Cheap x402 test utilities: ping returns pong+server time, uuid returns random UUID v4 values (`n=1..100`), time returns UTC ISO/unix and optional IANA timezone; $0.001 USDC per call on Base or Solana. Examples: `GET /v1/util/ping`, `GET /v1/util/uuid?n=1`, `GET /v1/util/time?tz=UTC`. ([OpenAPI](https://api.gptshopltd.com/openapi.json))
- **[EVM Selector, URL Status, Crypto Price and DNS Lookup](https://api.gptshopltd.com/v1/evm/4byte)** — Four small agent utilities on the same x402 host: decode an EVM 4-byte function selector or calldata via Sourcify and 4byte.directory ($0.002), check a public URL's HTTP status and redirect chain ($0.002), USD spot prices for up to 25 CoinGecko ids or symbols ($0.002), and A/AAAA/TXT/MX/CNAME/NS records over Cloudflare DNS-over-HTTPS ($0.001); USDC on Base or Solana. Examples: `GET /v1/evm/4byte?selector=0xa9059cbb`, `GET /v1/web/status?url=https://example.com`, `GET /v1/crypto/price?q=solana,btc,eth`, `GET /v1/dns/lookup?name=example.com&type=MX`. ([OpenAPI](https://api.gptshopltd.com/openapi.json))
- **[TrollBridge](https://mini-tollbooth.onrender.com/.well-known/x402)** — 28 pay-per-call intel lanes for AI agents: bounty intel, DeFi data, contract safety screen, gas prices, prediction markets, token safety, AI model catalog, and more, $0.02–$0.05 USDC per call on Base and Solana via x402 v2. Example: `GET /gas?network=base`. ([OpenAPI](https://mini-tollbooth.onrender.com/openapi.json)) ([Manifest](https://mini-tollbooth.onrender.com/.well-known/x402)) ([MCP](https://trollbridge-mcp-http.onrender.com)) ([GitHub](https://github.com/eric-tijerina/mini-tollbooth))
- **[Settlens payment-policy regression guide](https://settlens.com/blog/check-x402-payment-policy)** — Reproduce five synthetic x402 V2 payment-policy decisions with a browser demo, curl and a Node.js CI runner without making payments.
- **[PricePlain](https://priceplain.onrender.com/.well-known/x402)** — Posted US hospital prices from CMS price-transparency machine-readable files, cleaned (Twin Cities, MN first): gross charge, discounted cash price and payer-negotiated rates per CPT/DRG code with canonical insurer names, percent/algorithm rates flagged, data-quality flags, and source file URL + date. Posted prices, not quotes. $0.02 USDC per call on Base mainnet. Example: `GET /v1/price?code=70553&hospital=regions`. ([OpenAPI](https://priceplain.onrender.com/openapi.json)) ([Docs](https://priceplain.onrender.com/docs)) ([Discovery](https://priceplain.onrender.com/.well-known/x402))
- **[UTA Trust API](https://uta-trust-api.eddyflores100.workers.dev/.well-known/x402.json)** — Agent trust verification as a paid x402 resource: validates one Agent Trust Card (ATC/1.0) with real Ed25519 verification over the JCS-canonicalized card subtree (pinned anchors, two-sided validity window) and returns per-stage results plus a risk band. $0.01 USDC per verify ($0.08 for a 1-10 card batch) on Base mainnet (eip155:8453; Base Sepolia eip155:84532 kept for testing) via x402 v2 exact with EIP-3009 gasless settlement (mainnet: PayAI facilitator; testnet: x402.org); a call without payment gets a fail-closed 402 carrying the full challenge. Example: `POST https://uta-trust-api.eddyflores100.workers.dev/v1/trust/verify` with `{"card":{...}}` — the same URL without X-PAYMENT answers the live 402; v2 manifest and self-description at [/v1](https://uta-trust-api.eddyflores100.workers.dev/v1). ([OpenAPI](https://uta-trust-api.eddyflores100.workers.dev/openapi.json)) ([MCP](https://uta-trust-api.eddyflores100.workers.dev/mcp)) ([GitHub](https://github.com/alicelabs-llc/universal-trust-adapter))
- **[LitWit — The Literary Witness](https://www.pennypress.org/witness/attest)** — Literary notary API: submit a SHA-256 hash of a written work and receive a tamper-evident hash-chained receipt in a public log. $0.05 USDC on Base. Example: `POST /witness/attest {"work_title":"gold-402 example probe","content_hash":"83e771fb19749e70500cd6690e25ea22ae3d05f162a0b7f7b28797971cfeeeb1"}`.
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
