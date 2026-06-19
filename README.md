# YieldLens — Contract

**Soroban smart contracts that provide on-chain data helpers for the YieldLens ecosystem.**

## The Problem

Yield tracking on Stellar requires reading data across Soroban WASM contracts and classic ledger entries. Without on-chain helper contracts, the backend must parse raw event emissions and perform complex computations off-chain — introducing latency, gas inefficiency, and potential desync. These contracts move critical data aggregation closer to the source.

## What This Project Does

- Provides on-chain utility methods for querying pool state
- Aggregates yield and reward data from supported protocols (Soroswap, Phoenix Hub, Aquarius)
- Emits standardized events that the YieldLens backend indexes

## Related Projects

| Project | Description |
|---------|-------------|
| [YieldLens-backend](../YieldLens-backend) | REST API & indexer |
| [YieldLens-frontend](../YieldLens-frontend) | React + TypeScript dashboard |

## Stack

- **Language:** Rust (Soroban SDK)
- **Blockchain:** Stellar / Soroban

## Development

```bash
# coming soon
```

## License

MIT
