# Codex Work Plan — crypto-domain-knowledge

## Objective
Build and maintain a factual, up-to-date blockchain/crypto domain knowledge landscape for non-expert readers, with a structured taxonomy + verifiable references.

Output must be:
- stable structure
- low ambiguity
- snapshot-based for fast-changing data
- easy to update via tables

## Audience
General audience with basic technical literacy. Avoid hype. Explain only necessary concepts.

## Non-negotiable rules
1. Do not invent facts, rankings, or market data.
2. Any ranking must specify metric:
   - market cap (市值)
   - TVL (Total Value Locked，DeFi 锁仓)
   - volume (交易量)
   - usage (链上活跃指标，需说明选用的指标)
3. Any fast-changing numbers must include:
   - Snapshot date: YYYY-MM-DD
   - Source link (official or reputable aggregator)
4. Separate "public figure/advocate" from "protocol governance/leadership".
5. Prefer structured data in CSV and reference it from Markdown docs.
6. If uncertain, add TODO with what to verify and where to verify it.

## Repository structure (target)
- README.md: project overview, how to update, data sources
- glossary.md: glossary (English term + concise CN explanation)
- landscape.md: main narrative + taxonomy + pointers to tables
- tables/*.csv: structured datasets used by docs
- diagrams/landscape.mmd: Mermaid diagram for one-page map

## Primary sources (preferred)
Use these for facts and rankings:
- CoinGecko (chains, tokens, market data)
- CoinMarketCap (market rankings, stablecoins)
- DefiLlama (TVL, DEX volume, stablecoins)
Use official project docs for architecture and security assumptions.

## Deliverables (v0.1)
1. glossary.md
   - 80–150 terms
   - format: Term | Chinese explanation | Notes | Source
2. landscape.md
   - sections: Chains, Trading, Data/Analytics, Security/Compliance, Middleware, Stablecoins, Wallets, Custody, Multi-sig, Reading Path
   - each section references relevant tables/*.csv rows
3. tables CSVs populated minimally (top 10–30 entries per category)
   - chains.csv
   - exchanges.csv
   - dex.csv (spot + perp)
   - stablecoins.csv
   - wallets.csv
   - custody.csv
   - security_tools.csv
   - middleware.csv (oracle + cross-chain messaging)
   - multisig.csv (by chain)
4. diagrams/landscape.mmd
   - one diagram that matches the taxonomy in landscape.md

## CSV schema (required columns)
### tables/chains.csv
- Name,Layer(L1/L2),NativeAsset,Category(General/DeFi/Payments/etc),KeyNotes,Figurehead(public),MetricSourceURL,SnapshotDate,OfficialURL

### tables/exchanges.csv
- Name,Type(CEX),RegionNotes,KeyNotes,MetricSourceURL,SnapshotDate,OfficialURL

### tables/dex.csv
- Name,Type(Spot/Perp),Chain,Ecosystem,KeyNotes,MetricSourceURL,SnapshotDate,OfficialURL

### tables/stablecoins.csv
- Name,Type(Fiat-backed/Crypto-collateralized/Synthetic),Issuer,PrimaryChains,KeyNotes,MetricSourceURL,SnapshotDate,OfficialURL

### tables/wallets.csv
- Name,Type(Software/Hardware),PrimaryEcosystems,KeyNotes,OfficialURL

### tables/custody.csv
- Name,Model(Multi-sig/MPC/HSM),TargetUsers,KeyNotes,OfficialURL

### tables/security_tools.csv
- Name,Type(KYT/Research/Explorer/Labeling),KeyNotes,OfficialURL

### tables/middleware.csv
- Name,Type(Oracle/Messaging/Bridge),KeyNotes,SecurityAssumptions,OfficialURL

### tables/multisig.csv
- Chain,MainSolution,Type(Smart contract/Native permission/Script/MPC),KeyNotes,OfficialURL,DocsURL

## Work phases (execute in order)

### Phase 1 — Scaffold (structure first)
- Create/validate directory layout.
- Create empty CSVs with headers (schemas above).
- Create outline-only glossary.md and landscape.md.

### Phase 2 — Populate facts (tables first)
Populate CSVs using reputable aggregators + official docs:
- chains.csv: top L1 + key L2 (no single "global ranking")
- dex.csv: include Spot + Perp
- stablecoins.csv: include USDT, USDC, USDe, USDD + other major ones
- middleware.csv: include Chainlink + LayerZero + Wormhole + Axelar + CCIP
- multisig.csv: include Ethereum Safe, Solana Squads, TRON account permissions, Bitcoin PSBT/script references

### Phase 3 — Narrative (docs reference tables)
- Write landscape.md section-by-section referencing tables.
- Add glossary terms referenced by landscape.md.

### Phase 4 — Diagram
- Produce diagrams/landscape.mmd (Mermaid).
- Ensure the diagram categories exactly match landscape.md headings.

### Phase 5 — QA / consistency
- Ensure no duplicated names with different spellings.
- Ensure every non-trivial claim has a source or TODO.
- Ensure snapshot dates exist for rankings/metrics.

## Style constraints
- Use English technical terms at first mention, then short CN explanation.
- Prefer bullet lists over long paragraphs.
- No marketing wording, no “best/king/霸主”.
- Keep each section scannable.

## Immediate next tasks (do now)
1. Create files + headers for all CSVs in tables/.
2. Write glossary.md initial 50 terms used by the landscape headings.
3. Populate: chains.csv (L1 + L2 minimal set).
4. Populate: stablecoins.csv + middleware.csv + multisig.csv.
5. Draft landscape.md using only information present in CSVs.

## TODO markers format
Use exactly:
- TODO(verify): <what> | <where to verify> | <owner> | <due YYYY-MM-DD>

Owner default: Codex

## Definition of done (v0.1)
- All files exist.
- landscape.md can be read end-to-end without missing core categories.
- tables contain enough rows to support the narrative.
- diagram exists and matches taxonomy.
- snapshot date recorded for each metric-based table row.

