---
title: Crypto Domain Knowledge
---

# Crypto Domain Knowledge

## Overview
- Start with the narrative in [landscape.md](landscape.md).
- Use [glossary.md](glossary.md) for term definitions and sources.
- CSV tables are the data source used for updates (optional to view).

## Navigation
- Landscape: [landscape.md](landscape.md)
- Glossary: [glossary.md](glossary.md)

## Data Tables (Optional)
<details>
  <summary>Show CSV tables</summary>

- [tables/chains.csv](tables/chains.csv)
- [tables/exchanges.csv](tables/exchanges.csv)
- [tables/dex.csv](tables/dex.csv)
- [tables/stablecoins.csv](tables/stablecoins.csv)
- [tables/wallets.csv](tables/wallets.csv)
- [tables/custody.csv](tables/custody.csv)
- [tables/security_tools.csv](tables/security_tools.csv)
- [tables/middleware.csv](tables/middleware.csv)
- [tables/multisig.csv](tables/multisig.csv)
</details>

## Diagram
<div class="mermaid">
flowchart TD
    Landscape[Crypto Domain Landscape]
    Landscape --> Chains[Chains]
    Landscape --> Trading[Trading]
    Landscape --> DataAnalytics[Data/Analytics]
    Landscape --> SecurityCompliance[Security/Compliance]
    Landscape --> Middleware[Middleware]
    Landscape --> Stablecoins[Stablecoins]
    Landscape --> Wallets[Wallets]
    Landscape --> Custody[Custody]
    Landscape --> Multisig[Multi-sig]
    Landscape --> ReadingPath[Reading Path]

    Chains --> L1[L1]
    Chains --> L2[L2]

    Trading --> CEX[CEX]
    Trading --> DEX[DEX]

    DataAnalytics --> Research[Research/Analytics]
    DataAnalytics --> Explorers[Explorers]

    SecurityCompliance --> KYT[KYT/Compliance]
    SecurityCompliance --> Labeling[Labeling/Intel]

    Middleware --> Oracle[Oracle]
    Middleware --> Messaging[Messaging]

    Stablecoins --> Fiat[Fiat-backed]
    Stablecoins --> Crypto[Crypto-collateralized]
    Stablecoins --> Synthetic[Synthetic]

    Wallets --> Software[Software]
    Wallets --> Hardware[Hardware]

    Custody --> HSM[HSM]
    Custody --> MPC[MPC]
    Custody --> CustodyMultisig[Multi-sig]

    Multisig --> SmartContract[Smart contract]
    Multisig --> NativePermission[Native permission]
    Multisig --> Script[Script]

    ReadingPath --> Glossary[Glossary]
    ReadingPath --> Tables[Tables]
</div>

<script src="https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.min.js"></script>
<script>
  mermaid.initialize({ startOnLoad: true });
</script>
