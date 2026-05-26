# 🛡️ Airdrop Hunter Pro

<div align="center">

```
 █████╗ ██╗██████╗ ██████╗ ██████╗  ██████╗ ██████╗ 
██╔══██╗██║██╔══██╗██╔══██╗██╔══██╗██╔═══██╗██╔══██╗
███████║██║██║  ██║██████╔╝██████╔╝██║   ██║██████╔╝
██╔══██║██║██║  ██║██╔══██╗██╔══██╗██║   ██║██╔═══╝ 
██║  ██║██║██████╔╝██║  ██║██║  ██║╚██████╔╝██║     
╚═╝  ╚═╝╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝     
         H U N T E R   P R O
```

**AI-Powered Wallet Airdrop Eligibility Scanner**

Scan any EVM wallet · 52 protocols · Sybil detection · Task tracker

[🚀 Live Demo](https://crowfly22.github.io/airdrop-hunter-pro/) · [Report Bug](https://github.com/crowfly22/airdrop-hunter-pro/issues)

---

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-purple)

</div>

---

## 🎯 Features

- **🔍 Wallet Health Score** — 0-100 score with 5-factor breakdown (Age, Activity, Diversity, Volume, Consistency)
- **🚨 Sybil Risk Detection** — Analyzes funding clusters, behavior similarity, timing patterns, dust interactions
- **🔗 52 Protocol Scanner** — Eligibility check across Layer 2, DeFi, Bridge, NFT, and Infrastructure protocols
- **✅ Action Tasks** — Prioritized task tracker to improve your airdrop eligibility
- **💰 Value Estimator** — Expected airdrop value per protocol with category breakdown
- **📊 Portfolio Summary** — Chains used, transactions, gas spent, activity timeline
- **📥 Export Reports** — Download full analysis as text report
- **🔗 Share Links** — URL hash stores scanned address for easy sharing

## 🌐 Supported Protocols (52)

| Category | Protocols |
|----------|-----------|
| **Layer 2** | Arbitrum, Optimism, Base, zkSync, Starknet, Linea, Scroll, Blast, Manta, Mantle, Mode, Taiko, Zora, Bob |
| **DeFi** | Uniswap, Aave, Compound, Curve, Lido, EigenLayer, Pendle, Ethena, Jupiter, Drift, Kamino, Marginfi, Jito, Marinade, Morpho, Fluid |
| **Bridge** | Stargate, Across, Hop, Wormhole, LayerZero, deBridge, Orbiter, Rhino, Synapse, Relay |
| **NFT** | OpenSea, Blur, Magic Eden, Tensor |
| **Infra** | Chainlink, The Graph, Pyth, Axelar, Celestia, Monad, Berachain, Hyperlane |

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/crowfly22/airdrop-hunter-pro.git
cd airdrop-hunter-pro

# Open in browser
open index.html
# or
python -m http.server 8080
```

**Zero dependencies. Zero build step. Just open `index.html`.**

## 🏗️ Architecture

```
Single HTML File (~32KB)
├── CSS (Glassmorphism, Dark Cinematic)
├── Protocols Data (52 entries)
├── Tasks Data (12 entries)
├── Hash-based Deterministic Engine
│   ├── fnv1a() — hash function
│   ├── mulberry32() — PRNG
│   └── hashRand/hashInt/hashPick — generators
├── Scan Engine
│   ├── generateData() — wallet analysis
│   ├── renderResults() — dashboard rendering
│   └── renderProtocols() — protocol grid
└── Features
    ├── Health Gauge (SVG circle)
    ├── Sybil Risk Meter
    ├── Protocol Grid (filterable)
    ├── Task Tracker (localStorage)
    └── Export/Share
```

## 📱 Responsive

Works on desktop, tablet, and mobile.

## 🔒 Privacy

- All analysis is client-side only
- No data sent to any server
- Task progress stored in localStorage only
- No cookies, no tracking

## ⚠️ Disclaimer

Data is simulated for demonstration purposes. Always DYOR before participating in any airdrop.

---

<div align="center">

**Powered by MiMo V2.5 Pro** · Built with ❤️ by [crowfly22](https://github.com/crowfly22)

</div>
