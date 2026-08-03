# Mario Espinosa

**Lead Data Engineer | Institutional Web3 & Systems Architect**

[mario.espinosa.perales@gmail.com](mailto:mario.espinosa.perales@gmail.com) · [GitHub](https://github.com/marioespinosaperales)

I do not look for better dashboards. I make data a competitive advantage for the ecosystem — closing the gap between public blockchain/API data and **accountable, institutional-grade semantics**.

---

## Selected work

Three public projects that map to the institutional blockchain-data loop: **raw fragmented inputs → semantic models → maintainable SQL/dbt → quality methodology**.

| Project | What it demonstrates | Links |
|---|---|---|
| **[crypto-market-elt](https://github.com/marioespinosaperales/crypto-market-elt)** | Production ELT: CoinGecko + Binance → Parquet → DuckDB → dbt marts, pandera contracts, Dagster + hourly GitHub Actions | [Repo](https://github.com/marioespinosaperales/crypto-market-elt) · [Dashboard](https://crypto-market-elt-git-data-marioespinosaperales-projects.vercel.app/) |
| **[lp-history-reconstructor](https://github.com/marioespinosaperales/lp-history-reconstructor)** | Uniswap V3 LP event sourcing, NPM wallet attribution, on-chain verify (`liquidity` / `positions`), fees & IL vs HODL by range width | [Repo](https://github.com/marioespinosaperales/lp-history-reconstructor) · [Dashboard](https://lp-history-reconstructor.vercel.app/) |
| **[dex-trades-canonical](https://github.com/marioespinosaperales/dex-trades-canonical)** | Canonical `dex.trades` across Eth / Base / Arbitrum / Avalanche (Uniswap + Camelot / Aerodrome / Pharaoh); dust & self-churn **flagged, not deleted** | [Repo](https://github.com/marioespinosaperales/dex-trades-canonical) · [Dashboard](https://dex-trades-canonical.vercel.app) |

### How they fit together

1. **crypto-market-elt** — infra, data contracts, orchestration  
2. **lp-history-reconstructor** — on-chain decode + state fold + verification  
3. **dex-trades-canonical** — cross-chain/protocol semantic abstraction (`chain × protocol × pool`)

Shared stack: Python, Parquet, DuckDB, dbt, Evidence, CI — secrets only via env vars.

---

## Experience

### Avalanche Foundation — Lead Data Engineering  
*Dec 2024 – May 2026 · Remote*

- Architected high-throughput API / sub-second blockchain ingestion for real-time crypto decisioning.
- Led migration of data infrastructure onto **Allium** as a Single Source of Truth for Treasury (auditable lineage, high-fidelity reporting).
- Built adaptive behavioral agents for wallet classification (clustering + semi-supervised learning); airdrop retention policies reached **64%** token retention.
- Designed pipelines ingesting **~700 GB/day** on-chain and off-chain data.
- Directed autonomous risk-mitigation agents end-to-end → **+$15M USD** P&L optimization.
- Drove AI-native engineering culture (Cursor / Claude Code) and hub-and-spoke pipeline modularity.

### Citibanamex (Citibank) — SVP, Data Engineering  
*Sep 2023 – Dec 2024 · Mexico*

- Led a team of **20** data engineers; drove large annual development cost savings.
- Petabyte-scale HA platform: CI/CD, dbt tests, Snowflake monitoring → **40%** faster incident resolution.
- Technical strategy for Banamex divestiture data migration with global teams (Singapore).

### Citibanamex — AVP, Data Engineer  
*Jan 2019 – Sep 2023 · Mexico*

- Large-scale banking pipelines (**−30%** processing time).
- Fraud detection across **10M+** risky transactions; **$5M+** penalty avoidance.
- ML models for prospecting → **+15%** successful new client acquisitions.

### Costco Wholesale — Supply Chain Analyst  
*Jan 2016 – Dec 2018 · Mexico*

- RL / MDP bakery production optimization; perishable demand forecasting (**−15%** excess inventory).

### The Root Network — Sr. Tokenomics & Data Engineer *(part-time)*  
*May 2021 – Nov 2024*

- NFT data infra / ETL; tokenomics design (distribution, incentives, governance).

---

## Education

- **MSc Machine Learning & Artificial Intelligence** — OBS Barcelona / Universitat Online *(2026–2027)*
- **BSc Mechatronics Engineering** — Tecnológico de Monterrey *(2013–2018)* · CENEVAL National Award; IDEAL Program Committee

---

## Skills (selected)

**Leadership:** people management, technical roadmap, hiring & mentoring, Agile/Scrum  

**Data & platforms:** Python, SQL, dbt, Snowflake, Databricks, PySpark, Kafka, Airflow, PostgreSQL, DuckDB, ELT/ETL, data governance & quality  

**Cloud:** AWS (S3, Redshift, Glue, Lambda, CDK), Azure (ADF, Databricks), GCP  

**Web3 analytics:** on-chain pipelines, DeFi / tokenomics, Allium, Dune, Flipside, Kaiko, TRM  

**ML:** NumPy, Pandas, scikit-learn, TensorFlow, PyTorch  

**Languages:** English & Spanish (fluent)

---

*Repos in this portfolio map to production patterns: contracts at ingestion, canonical grains, documented methodology, and live Evidence dashboards.*
