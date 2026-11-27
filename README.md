<img width="823" height="427" alt="image" src="https://github.com/user-attachments/assets/0bbe37db-7e47-45c5-b707-0e33fa8dd922" /># 👋 Hi, I'm Dongik

**Backend & AI Developer** at a software company in Seoul.

I design and build resilient backend services and pragmatic AI agent architectures.  
I focus on engineering software that is predictable in production, observable under failure, and built with a deep respect for real-world trade-offs.

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/-JAVA-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/-SPRING%20BOOT-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/-PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-LANGGRAPH-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-KAFKA-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/-ELASTICSEARCH-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" />
  <img src="https://img.shields.io/badge/-CLICKHOUSE-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black" />
  <img src="https://img.shields.io/badge/-GRAFANA-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/-GIT-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/-GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/-VS%20CODE-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/-LINUX-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

## 🏛 Philosophy behind `KoulLife`
> **Kenosis · Ouroboros · Umbra · Logos**  
> *"Empty the noise to see the cycle; confront the constraints to build lasting order."*

Four core principles guiding both my engineering and personal outlook:

* **[K]enosis (Simplicity through Emptying)**  
  Eliminating unnecessary complexity and over-engineering to focus entirely on the core problem and domain essence.

* **[O]uroboros (Continuous Cycle)**  
  Trusting the feedback loop of design, instrumentation, failure, and refactoring where systems and knowledge iteratively evolve.

* **[U]mbra (Embracing Constraints)**  
  Acknowledging the inherent imperfection and trade-offs in every system. Constraints and edge cases are not obstacles to avoid, but foundational premises for resilient architecture.

* **[L]ogos (Logic and Order)**  
  Structuring real-world chaos and intricate data pipelines into readable, verifiable code and well-defined interfaces.

## 🌱 Open Source Contributions

| Project | Contribution | PR |
|---|---|---|
| [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) | Fixed ClickHouse panel queries failing with multi-value variables: `StatusCode IN ($status)` was sent as `IN (Error)` instead of the plugin's `IN ('Error')`. Multi-value selections are now quoted like the ClickHouse plugin does, with unit tests. | [#1720](https://github.com/grafana/mcp-grafana/pull/1720) |
| [we-promise/sure](https://github.com/we-promise/sure) | Fixed the trade form saving a price in the wrong currency: the fee's currency picker overrode the one picked for the price, so `$305.6` was saved as `₩306`. The fee now follows the price's currency, with regression tests. | [#5842](https://github.com/we-promise/sure/pull/5842) |
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | Corrected the Korean (ko-KR) username validation message, which said Hangul was allowed while the actual pattern only accepts Hanja. | [#4025](https://github.com/Tencent/WeKnora/pull/4025) |
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | Fixed a regression in the chat model connection test that marked healthy models as failed, with regression tests. | [#3929](https://github.com/Tencent/WeKnora/pull/3929) |
| [toeverything/AFFiNE](https://github.com/toeverything/AFFiNE) | Fixed the Block Diff Playground modal being drawn under the editor's isolated stacking context by portaling it to the document body instead of the editor host. | [#15890](https://github.com/toeverything/AFFiNE/pull/15890) |
