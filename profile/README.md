# Orkid Labs

Agent-native DeFi infrastructure: gasless, MEV-protected swap routing, cross-chain bridging, and the open-source building blocks underneath — [orkidlabs.xyz](https://orkidlabs.xyz) · [docs](https://docs.orkidlabs.xyz) · [@orkid-labs on npm](https://www.npmjs.com/org/orkid-labs)

## Flagship

| Project | What it is |
|---|---|
| [orkid-swap-mcp](https://github.com/jjcav84/orkid-swap-mcp) | MCP server — gasless, MEV-protected swap + bridge quotes for agents (`tools/call` → `orkid_quote`) |
| [orkid-sdk](https://github.com/orkid-labs/orkid-sdk) | TypeScript SDK + React widget for Orkid swap routing |
| [plugin-orkid](https://github.com/orkid-labs/plugin-orkid) | Orkid agent plugin — swap lifecycle inside agent frameworks |
| [plugin-mempalace](https://github.com/orkid-labs/plugin-mempalace) | MemPalace persistent memory plugin for agents |
| [eliza-trader-starter](https://github.com/orkid-labs/eliza-trader-starter) | Template — fork to launch an ElizaOS trading agent on Orkid |

## Rust crates

| Crate | What it does |
|---|---|
| [defi-core](https://github.com/orkid-labs/defi-core) | DeFi domain types — chains, tokens, pools, trades, errors |
| [cctp-utils](https://github.com/orkid-labs/cctp-utils) | Circle CCTP — depositForBurn encoding + Iris attestation verification |
| [splits-distributor](https://github.com/orkid-labs/splits-distributor) | 0xSplits contract interaction — discovery, balances, distribution |
| [event-broadcaster](https://github.com/orkid-labs/event-broadcaster) | Async pub/sub on tokio broadcast channels |
| [orkid-lru-cache](https://github.com/orkid-labs/lru-cache) | Dependency-free LRU cache, generic K/V |
| [negentropy](https://github.com/orkid-labs/negentropy) | Thermodynamic information-extraction scoring engine |
| [zenkinetic](https://github.com/orkid-labs/zenkinetic) | Privacy gate for Horizen Base L3 — negentropy-scored confidential txs |
| [horizen-attest](https://github.com/orkid-labs/horizen-attest) | ZK attestations on Horizen Base L3 |
| [horizen-age](https://github.com/orkid-labs/horizen-age) | Privacy-preserving age verification on Horizen Base L3 |
| [horizen-ballot](https://github.com/orkid-labs/horizen-ballot) | Anonymous on-chain voting — Halo2 + Solidity |
| [zk-ballot](https://github.com/orkid-labs/zk-ballot) | Halo2 ZK voting library |
| [zk-attest](https://github.com/orkid-labs/zk-attest) | ZK attestation platform on Hedera (HCS + HTS) |
| [zk-age](https://github.com/orkid-labs/zk-age) | Groth16 age verification for web2, settled on zkVerify |

## TypeScript utilities

| Package | What it does |
|---|---|
| [analytics-utils](https://github.com/orkid-labs/analytics-utils) | Keen.io analytics — UTM tracking, event collection, bot-aware telemetry |
| [react-utils](https://github.com/orkid-labs/react-utils) | React helpers — formatting, class merging |
| [settlement-types](https://github.com/orkid-labs/settlement-types) | Cross-chain settlement intent types (EVM + Hedera) |
| [hedera-utils](https://github.com/orkid-labs/hedera-utils) | Hedera utilities — HCS logging, milestone tracking |

## Python

| Package | What it does |
|---|---|
| [hedera-analytics](https://github.com/orkid-labs/hedera-analytics) | Hedera analytics — staking profiler, data refinery, Prolog facts |

## Skills

Every repo ships a [`SKILL.md`](https://agentskills.io) and is listed in the [Smithery Skills Registry](https://smithery.ai) under `orkidlabs/` — 20+ skills covering swaps, bridges, gasless execution, ZK privacy, Hedera, and agent memory.
