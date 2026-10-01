<div align="center">


### Quantitative Developer — AI-driven trading systems

Building autonomous research and trading agents · Security researcher on the side<br>
Advocate for decentralized, self-custodial and private systems

[![NexQuant](https://img.shields.io/badge/Project-NexQuant-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TPTBusiness/NexQuant)
[![Proton](https://img.shields.io/badge/Proton-Security_Contributor-6D4AFF?style=for-the-badge&logo=proton&logoColor=white)](https://proton.me/blog/protonmail-security-contributors)
[![Bitcoin](https://img.shields.io/badge/Bitcoin-Self--Custody-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white)](#principles)

</div>

---

## 🧬 NexQuant — Autonomous Multi-Agent Quant Research

```mermaid
flowchart LR
    A[Market Data<br/>TimescaleDB] --> B[Research Agents<br/>LLM]
    B --> C[Alpha Factors]
    C --> D[Strategy Evolution]
    D --> E[Backtest<br/>Walk-Forward / OOS]
    E --> F{Invariant &<br/>Property Tests}
    F -- pass --> G[Validated Strategy]
    F -- fail --> B
```

> [!NOTE]
> Strategies are judged out-of-sample with cost & slippage modelling — not by in-sample fit.

<details>
<summary><b>What it does</b></summary>

- Discovers and generates alpha factors with LLM-driven research agents
- Evolves and backtests strategies continuously
- Integrates time-series foundation models (e.g. Kronos) alongside classical factor models
- Verifies results with mathematical invariants and property-based testing

**Infra:** Redis · PostgreSQL/TimescaleDB · QLib · llama.cpp
</details>

---

<a id="principles"></a>
## ₿ Principles

> [!IMPORTANT]
> **Don't trust, verify.** I build for and support decentralized, permissionless and private systems —
> Bitcoin, self-custody, self-hosted infrastructure, end-to-end encryption.

---

## 🔍 Security Research

| | |
|---|---|
| 🏆 | Listed in the [Proton Security Contributors](https://proton.me/blog/protonmail-security-contributors) (*Nicolas Bohn*, 2026) |
| 🌐 | Bug bounty research on on-chain & exchange infrastructure — API, auth, protocol integrity |

---

## 🛠️ Stack

| Quant & AI | Data & Infra | Exploring |
|---|---|---|
| <kbd>Python</kbd> <kbd>QLib</kbd> <kbd>llama.cpp</kbd> <kbd>Multi-Agent</kbd> | <kbd>PostgreSQL</kbd> <kbd>TimescaleDB</kbd> <kbd>Redis</kbd> <kbd>Docker</kbd> <kbd>Linux</kbd> | <kbd>Rust</kbd> |

---

