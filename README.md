# Solana

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
