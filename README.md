## Hi, I'm HDSer — Data & Analytics Engineer

I work on **large-scale event & transaction data**, **graph analytics**, and **simulations**.  
Recently that’s mostly been blockchain & P2P networks, but the problems are general:  
reliable data infrastructure, deep analytics, and modeling complex systems.

- 💻 **Stack:** Python, SQL, Rust, Go, dbt, ClickHouse, Postgres, Docker, Grafana, NetworkX, Mesa  
- 📊 **Domains:** transaction analytics, graph & trust networks, performance benchmarking, ABM simulations  

---

## Selected projects

### Data platforms & analytics engineering

- **[Graph Analyzer](https://github.com/hdser/graph_analyzer)**  
  Comprehensive toolkit for *transaction / trust networks*: builds graphs from SQL, computes 120+ NetworkX metrics,
  and serves them to **Cytoscape Desktop** or a **FastAPI web viewer**, backed by Postgres.

- **[Cryo Indexer](https://github.com/gnosischain/cryo-indexer)** & **[Beacon Indexer](https://github.com/gnosischain/beacon-indexer)**  
  Indexers that ingest execution- and consensus-layer blockchain data into **ClickHouse** / parquet, with Docker setup,
  schema design, and ELT flows for analytics.

- **[dbt Cerebro](https://github.com/gnosischain/dbt-cerebro)** & **[Metrics Dashboard](https://github.com/gnosischain/metrics-dashboard)**  
  dbt project and analytics dashboard powering Gnosis’ data stack: transforms raw data (P2P, consensus, EL, ESG, etc.)
  into **semantic models** and exposes them in dashboards for product & infra teams.

- **[ClickHouse Benchmark](https://github.com/hdser/clickhouse-benchmark)**  
  Benchmarking framework for ClickHouse: runs analytical workloads, tracks latency & memory, and helps tune queries
  and schema for heavy analytics.

- **[ClickHouse API Proxy](https://github.com/hdser/clickhouse-api-proxy)** & **[ClickHouse Migrations](https://github.com/hdser/clickhouse-migrations)**  
  Utilities around ClickHouse: a secure API proxy for dashboard metrics (Vercel-deployed) and a migrations helper for
  managing schema evolution in analytics environments.

- **[IP Info Crawler](https://github.com/hdser/ip_crawler)**  
  Dockerized service that enriches IPs using `ipinfo.io` and writes to ClickHouse, with batching, retries, rate-limit
  handling, and incremental month-by-month processing for large tables.

---

### Graphs, routing & trust networks

- **[TrustScore](https://github.com/hdser/trust-score)**  
  Framework implementing **EigenTrust, Appleseed, PageRank-style** trust scoring, plus liquidity and security
  metrics for sybil-resistance and network analysis.

- **[PyFinder](https://github.com/hdser/pyfinder)** & **[PyFinder-DGen](https://github.com/hdser/pyfinder-dgen)**  
  A path-finding / max-flow engine for routing value over trust networks and a companion data generator for realistic
  synthetic networks with multiple topology types and configurable token distributions.

- **[circles_subgraph](https://github.com/hdser/circles_subgraph)** & **[groups-flow-viz](https://github.com/hdser/groups-flow-viz)**  
  GraphQL subgraph and visualization tools to analyze Circles trust relationships, flows between groups, and network
  structure over time.

- **[network-anim](https://github.com/hdser/network-anim)**  
  Small toolkit to animate and visualize network evolution over time, used for exploratory analysis and presentations.

---

### Simulation & modeling

- **[PyCircleSim](https://github.com/hdser/PyCircleSim)**  
  Framework for simulations on the Circles network, modeling network evolution, value flows, and trust behavior.

- **[circlesubi-simulation](https://github.com/hdser/circlesubi-simulation)**  
  Agent-based Mesa + Panel simulation of a UBI system on a trust network: configurable scenarios, multi-run statistics,
  and interactive dashboards (playground, visualizer, network graphs).

- **[pathfinder-docs](https://github.com/hdser/pathfinder-docs)** & **[pathfinder2](https://github.com/hdser/pathfinder2)**  
  Documentation and Rust implementation of the pathfinding tool used in Circles UBI, covering methodology,
  performance considerations, and algorithmic details.

---

### Open-source, infra & collaborations

- **[Dune Spellbook](https://github.com/duneanalytics/spellbook)** – contributor  
  Shared SQL models powering on-chain analytics on Dune; contributions around Gnosis / Circles datasets and metrics.

- **[circles-nethermind-plugin](https://github.com/aboutcircles/circles-nethermind-plugin)** – contributor  
  C# plugin integrating Circles logic at the node level for data collection and protocol experiments.


---

## Elsewhere

- 🧮 **Dune Analytics:** https://dune.com/hdser  

---

![profile count](https://komarev.com/ghpvc/?username=hdser&color=red)&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/hdser?label=follow&style=social)](https://github.com/hdser)&nbsp;


![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=hdser&theme=transparent)
![](http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=hdser&theme=transparent)

