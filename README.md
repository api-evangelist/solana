# Solana

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

Solana is a high-performance blockchain platform designed for fast, secure, and scalable decentralized applications and marketplaces. It exposes a JSON-RPC 2.0 API over HTTP and WebSocket for querying accounts, transactions, programs, token balances, blocks, and cluster state, as well as submitting and simulating transactions. Three public clusters are available — Mainnet, Devnet, and Testnet — with dedicated API nodes for each environment.

**Areas:** Solana · Blockchain · Cryptocurrency · Web3 · DeFi · Transaction · Tokens

## Solana on APIs.io

Everything profiled for Solana is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/solana/](https://apis.io/providers/solana/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Solana RPC Tokens API](https://apis.io/apis/solana/solana-rpc-tokens-api/) — SPL Token-oriented JSON-RPC methods for the Solana blockchain. Provides getTokenAccountBalance to return the token balance for an SPL Token account,…
- [Solana RPC Transactions API](https://apis.io/apis/solana/solana-rpc-transactions-api/) — Transaction-oriented JSON-RPC methods for the Solana blockchain. Includes sendTransaction to submit a signed transaction to the network, simulateTransaction…
- [Solana RPC Blocks API](https://apis.io/apis/solana/solana-rpc-blocks-api/) — Block and slot-oriented JSON-RPC methods for the Solana blockchain. Includes getBlock to retrieve a confirmed block at a given slot, getBlockCommitment for…
- [Solana RPC Cluster API](https://apis.io/apis/solana/solana-rpc-cluster-api/) — Cluster and validator-oriented JSON-RPC methods for the Solana network. Includes getClusterNodes for the list of nodes in the cluster, getEpochInfo and…
- [Solana RPC Economics API](https://apis.io/apis/solana/solana-rpc-economics-api/) — Economics and staking-oriented JSON-RPC methods for the Solana blockchain. Includes getInflationGovernor to retrieve current inflation parameters,…
- [Solana RPC WebSocket Subscriptions API](https://apis.io/apis/solana/solana-rpc-websocket-api/) — Real-time WebSocket subscription API for the Solana blockchain. Provides event-driven notifications for accounts (accountSubscribe, programSubscribe),…
- [Solana Accounts API](https://apis.io/apis/solana/solana-accounts-api/) — Methods for querying account state, balances, and program ownership
- [Solana Blocks API](https://apis.io/apis/solana/solana-blocks-api/) — Methods for querying blocks, slots, and ledger information
- [Solana Cluster API](https://apis.io/apis/solana/solana-cluster-api/) — Methods for querying cluster nodes, validators, and network state
- [Solana Economics API](https://apis.io/apis/solana/solana-economics-api/) — Methods for querying inflation, staking, and supply information
- [Solana Tokens API](https://apis.io/apis/solana/solana-tokens-api/) — Methods for querying SPL Token accounts, balances, and supply
- [Solana Transactions API](https://apis.io/apis/solana/solana-transactions-api/) — Methods for sending, simulating, and querying transactions

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (17)

Multi-step workflows that chain operations into a business task.

- [Solana Check Whether an Account Is Rent Exempt](https://apis.io/arazzos/solana/solana-account-rent-exemption-workflow/)
- [Solana Page an Address's Transaction History](https://apis.io/arazzos/solana/solana-address-transaction-history-workflow/)
- [Solana Inspect a Confirmed Block at the Current Slot](https://apis.io/arazzos/solana/solana-block-inspection-workflow/)
- [Solana Run a Cluster Health and Readiness Check](https://apis.io/arazzos/solana/solana-cluster-health-check-workflow/)
- [Solana Request a Devnet Airdrop and Confirm Funding](https://apis.io/arazzos/solana/solana-devnet-airdrop-workflow/)
- [Solana Estimate Transaction Fees and Priority Fees](https://apis.io/arazzos/solana/solana-fee-estimation-workflow/)
- [Solana Resolve the Current Epoch's Leader Schedule](https://apis.io/arazzos/solana/solana-leader-schedule-workflow/)
- [Solana Discover the Available Ledger Range and Backfill Blocks](https://apis.io/arazzos/solana/solana-ledger-backfill-range-workflow/)
- [Solana Sample Network Performance and Block Production](https://apis.io/arazzos/solana/solana-network-performance-workflow/)
- [Solana Snapshot Network Supply and Staking Economics](https://apis.io/arazzos/solana/solana-network-supply-economics-workflow/)
- [Solana Identify a Node and Its Cluster and Snapshot State](https://apis.io/arazzos/solana/solana-node-identity-snapshot-workflow/)
- [Solana Scan a Program's Owned Accounts](https://apis.io/arazzos/solana/solana-program-accounts-scan-workflow/)
- [Solana Submit a Transaction and Confirm It](https://apis.io/arazzos/solana/solana-send-transaction-lifecycle-workflow/)
- [Solana Audit Token Accounts Delegated to an Address](https://apis.io/arazzos/solana/solana-token-delegate-audit-workflow/)
- [Solana Analyze an SPL Token Mint and Its Largest Holders](https://apis.io/arazzos/solana/solana-token-mint-analytics-workflow/)
- [Solana Audit Validator Vote Accounts and Inflation Rewards](https://apis.io/arazzos/solana/solana-validator-rewards-workflow/)
- [Solana Snapshot a Wallet's SOL and SPL Token Holdings](https://apis.io/arazzos/solana/solana-wallet-portfolio-workflow/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [solana-dev-mcp](https://apis.io/servers/solana/solana-dev-mcp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Solana Agentic Access](https://apis.io/agentic-access/solana/solana-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Solana JSON-RPC API Schemas](https://apis.io/schemas/solana/solana-rpc-schemas/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Solana Rpc Context](https://apis.io/jsonld/solana/solana-rpc-context/)

#### Examples (1)

Example requests and responses.

- [Solana Rpc Examples](https://apis.io/examples/solana/solana-rpc-examples/)

#### Collections (12)

Postman and Open Collection request collections.

- [Solana JSON-RPC Accounts API](https://apis.io/collections/solana/open-solana-accounts-api/)
- [Solana JSON-RPC Accounts Blocks API](https://apis.io/collections/solana/open-solana-blocks-api/)
- [Solana JSON-RPC Accounts Cluster API](https://apis.io/collections/solana/open-solana-cluster-api/)
- [Solana JSON-RPC Accounts Economics API](https://apis.io/collections/solana/open-solana-economics-api/)
- [Solana JSON-RPC Accounts Tokens API](https://apis.io/collections/solana/open-solana-tokens-api/)
- [Solana JSON-RPC Accounts Transactions API](https://apis.io/collections/solana/open-solana-transactions-api/)
- [Solana JSON-RPC Accounts API](https://apis.io/collections/solana/postman-solana-accounts-api/)
- [Solana JSON-RPC Accounts Blocks API](https://apis.io/collections/solana/postman-solana-blocks-api/)
- [Solana JSON-RPC Accounts Cluster API](https://apis.io/collections/solana/postman-solana-cluster-api/)
- [Solana JSON-RPC Accounts Economics API](https://apis.io/collections/solana/postman-solana-economics-api/)
- [Solana JSON-RPC Accounts Tokens API](https://apis.io/collections/solana/postman-solana-tokens-api/)
- [Solana JSON-RPC Accounts Transactions API](https://apis.io/collections/solana/postman-solana-transactions-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Solana Rpc Api Overlay](https://apis.io/overlays/solana/solana-rpc-api-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Solana — jsonschema rules](https://apis.io/rules/solana/solana-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Solana Authentication](https://apis.io/security/solana/solana-authentication/)
- [Solana Domain Security](https://apis.io/security/solana/solana-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Solana Plans](https://apis.io/plans/solana/solana-plans/)

#### Rate limits (1)

Published request limits.

- [Solana Rpc Rate Limits](https://apis.io/rate-limits/solana/solana-rpc-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Solana Finops](https://apis.io/finops/solana/solana-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://solana.com/)
- [Documentation](https://solana.com/docs)
- [Getting started](https://solana.com/docs/intro/quick-start)
- [Changelog](https://solanacompass.com/learn/Changelog)
- [Blog](https://solana.com/news)
- [Terms of service](https://solana.com/tos)
- [Privacy policy](https://solana.com/privacy-policy)
- [GitHub](https://github.com/solana-labs)
- [Status](https://status.solana.com/)

## API Evangelist rating

**Kin Score 58.4** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 58.0 |
| Contract governance | 28.0 |
| Operational transparency | 52.6 |
| Developer ergonomics | 84.5 |
| Access clarity | 28.9 |

**Agent readiness 27.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/solana/](https://apis.io/providers/solana/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Solana: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/solana/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
