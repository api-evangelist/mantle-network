# Mantle Network

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Mantle is a high-performance, EVM-compatible Ethereum Layer 2 network with a modular architecture that combines an optimistic rollup execution layer with EigenDA for data availability. The ecosystem also includes Mantle Liquid Staking Protocol (mETH) and Mantle Restaked ETH. Developer surface is built on standard Ethereum JSON-RPC endpoints (mainnet and Mantle Sepolia testnet), WebSocket subscriptions, the Mantle Explorer (Blockscout-based REST API), a canonical L1 <-> L2 bridge, and standard EVM SDKs (viem, ethers, Hardhat, Foundry, Thirdweb).

**Areas:** Layer 2 · Ethereum · Rollup · EigenDA · Liquid Staking · JSON-RPC · Cryptocurrency · Web3 · Real-Time

## Mantle Network on APIs.io

Everything profiled for Mantle Network is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/mantle-network/](https://apis.io/providers/mantle-network/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Mantle JSON-RPC (Mainnet)](https://apis.io/apis/mantle-network/json-rpc-mainnet/) — Standard Ethereum JSON-RPC endpoint for Mantle mainnet (chain ID 5000). Used by wallets, dApps, indexers, and tooling to read chain state and submit…
- [Mantle WebSocket (Mainnet)](https://apis.io/apis/mantle-network/websocket-mainnet/) — WebSocket endpoint for real-time JSON-RPC subscriptions on Mantle mainnet - new blocks, new pending transactions, and log subscriptions.
- [Mantle JSON-RPC (Sepolia Testnet)](https://apis.io/apis/mantle-network/json-rpc-sepolia/) — Standard Ethereum JSON-RPC endpoint for the Mantle Sepolia testnet, used for development, contract deployment dry runs, and integration testing.
- [Mantle Explorer API](https://apis.io/apis/mantle-network/explorer-api/) — Blockscout-based REST API behind explorer.mantle.xyz - blocks, transactions, addresses, tokens, smart-contract verification, and event log endpoints. Used…
- [Mantle Bridge](https://apis.io/apis/mantle-network/bridge/) — Canonical L1 <-> L2 bridge for ETH, MNT, ERC-20, and ERC-721 assets between Ethereum mainnet and Mantle. dApps integrate via the published Standard Bridge…
- [Mantle SDK](https://apis.io/apis/mantle-network/mantle-sdk/) — TypeScript SDK for bridging MNT, ETH, ERC-20, and ERC-721 tokens between Ethereum L1 and Mantle L2. Mirrors the Optimism SDK shape and wraps the Standard…
- [Mantle Liquid Staking Protocol (mETH)](https://apis.io/apis/mantle-network/meth-protocol/) — Mantle LSP issues mETH, a liquid staking token backed by ETH staked to Ethereum validators. Smart contracts on Ethereum L1 expose stake, unstake, and…
- [Mantle OP Stack Fork](https://apis.io/apis/mantle-network/op-stack/) — Mantle's node software, forked from Optimism's OP Stack and modified to use EigenDA for data availability and a token-gas MNT model. Source for op-node,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Mantle Network WebSocket JSON-RPC](https://apis.io/asyncapis/mantle-network/mantle-network-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/](https://apis.io/channels/mantle-network/untitled/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Mantle Network — asyncapi rules](https://apis.io/rules/mantle-network/mantle-network-asyncapi-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Mantle Network Domain Security](https://apis.io/security/mantle-network/mantle-network-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Mantle Network Plans Pricing](https://apis.io/plans/mantle-network/mantle-network-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Mantle Network Rate Limits](https://apis.io/rate-limits/mantle-network/mantle-network-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Mantle Network Finops](https://apis.io/finops/mantle-network/mantle-network-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.mantle.xyz/)
- [Documentation](https://docs.mantle.xyz/)
- [Blog](https://www.mantle.xyz/blog/rss.xml)

## API Evangelist rating

**Kin Score 23.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 40.6 |
| Contract governance | 11.4 |
| Operational transparency | 10.5 |
| Developer ergonomics | 16.7 |
| Access clarity | 5.3 |

**Agent readiness 14.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 5.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/mantle-network/](https://apis.io/providers/mantle-network/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Mantle Network: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/mantle-network/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
