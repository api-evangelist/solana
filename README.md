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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Solana is a high-performance blockchain platform designed for fast, secure, and scalable decentralized applications and marketplaces. It exposes a JSON-RPC 2.0 API over HTTP and WebSocket for querying accounts, transactions, programs, token balances, blocks, and cluster state, as well as submitting and simulating transactions.

Three public clusters are available for different environments:

- **Mainnet** (`https://api.mainnet.solana.com`) - Production network with real SOL
- **Devnet** (`https://api.devnet.solana.com`) - Developer testing with free airdrop SOL
- **Testnet** (`https://api.testnet.solana.com`) - Validator stress-testing

## APIs

- **Solana RPC Accounts API** - getAccountInfo, getBalance, getMultipleAccounts, getProgramAccounts, and more
- **Solana RPC Tokens API** - SPL Token queries: balances, accounts by owner/delegate, supply, largest accounts
- **Solana RPC Transactions API** - sendTransaction, simulateTransaction, getTransaction, getSignaturesForAddress, and more
- **Solana RPC Blocks API** - getBlock, getBlockHeight, getBlocks, getBlockTime, and more
- **Solana RPC Cluster API** - getClusterNodes, getEpochInfo, getSlot, getVoteAccounts, and more
- **Solana RPC Economics API** - getInflationRate, getInflationReward, getSupply, getStakeMinimumDelegation
- **Solana RPC WebSocket Subscriptions API** - Real-time notifications for accounts, transactions, blocks, slots

## Resources

- [Developer Portal](https://solana.com/developers)
- [RPC Documentation](https://solana.com/docs/rpc)
- [Clusters and Endpoints](https://solana.com/docs/references/clusters)
- [Status Page](https://status.solana.com/)
- [Terms of Service](https://solana.com/tos)

## Rate Limits (Public Endpoints)

| Limit | Value |
|-------|-------|
| Requests per 10s per IP | 100 |
| Requests per 10s per single RPC | 40 |
| Concurrent WebSocket connections | 40 |
| Connection rate per 10s | 40 |
| Data transfer per 30s | 100 MB |

Public endpoints return HTTP 429 when rate limits are exceeded and HTTP 403 when an IP is blocked. Production applications should use a dedicated private RPC provider or self-hosted node.
