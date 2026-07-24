# Awesome-Streaming-ETL
## Top Streaming ETL Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Real-Time Data Streaming, ETL & Event Processing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Streaming ETL**. These tools enable real-time data ingestion, transformation, and loading from various sources to sinks with low latency, supporting event streaming, change data capture, and continuous processing pipelines.

**Examples** include Confluent Cloud, Estuary, Decodable, Upsolver, RisingWave Cloud, Tinybird, Materialize, Aiven for Kafka, Redpanda Cloud, and StreamNative (the category leaders). Tools listed here emphasize **real-time processing**, scalability, fault tolerance, and integration with modern data stacks.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, full customization, and production streaming ETL pipelines — ideal for data engineers who want control and cost efficiency.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

### Core Platforms (Streaming ETL)

- **[Confluent Cloud](https://www.confluent.io/confluent-cloud/)**  
  Fully managed Kafka-based streaming platform with powerful ETL and processing capabilities.

- **[Estuary](https://estuary.dev/)**  
  Real-time data platform with strong streaming ETL and materialization features.

- **[Decodable](https://www.decodable.co/)**  
  Serverless streaming ETL platform with SQL-based transformations.

- **[Upsolver](https://www.upsolver.com/)**  
  Low-code streaming data platform for ETL and analytics.

- **[RisingWave Cloud](https://risingwave.com/)**  
  Cloud-native streaming database with powerful ETL and real-time analytics.

- **[Tinybird](https://www.tinybird.co/)**  
  Real-time data platform optimized for streaming ETL and API generation.

- **[Materialize](https://materialize.com/)**  
  Streaming database for real-time analytics and materialized views.

- **[Aiven for Kafka](https://aiven.io/)**  
  Fully managed Apache Kafka with streaming ETL support.

- **[Redpanda Cloud](https://redpanda.com/)**  
  Kafka-compatible streaming platform with high performance.

- **[StreamNative](https://streamnative.io/)**  
  Cloud-native event streaming platform built on Pulsar with strong ETL capabilities.

### Advanced & Specialized Platforms

**Other notable mentions**: Flink on cloud providers and various managed streaming services.

## Open-Source GitHub Projects

### Dedicated Streaming ETL Tools

- **[Apache Kafka](https://github.com/apache/kafka)**  
  The de-facto standard for streaming data pipelines with Connect for ETL and Streams for processing.

- **[Apache Flink](https://github.com/apache/flink)**  
  Powerful open-source stream and batch processing framework with excellent stateful ETL capabilities.

- **[Apache Spark Streaming](https://github.com/apache/spark)**  
  Unified analytics engine with robust streaming ETL and micro-batch processing.

- **[RisingWave](https://github.com/risingwavelabs/risingwave)**  
  Open-source streaming database for real-time ETL and materialized views.

- **[Materialize](https://github.com/MaterializeInc/materialize)**  
  Open-source streaming SQL database for incremental computation and real-time analytics.

- **[Apache Pulsar](https://github.com/apache/pulsar)**  
  Cloud-native distributed messaging and streaming platform with strong ETL support.

- **[Redpanda](https://github.com/redpanda-data/redpanda)**  
  Kafka-compatible streaming platform written in C++ for high performance.

- **[Estuary Flow](https://github.com/estuary/flow)**  
  Open-source real-time data platform for streaming ETL and materialization.

- **[Vector](https://github.com/vectordotdev/vector)**  
  High-performance observability data pipeline for collecting, transforming, and routing events.

- **[Fluent Bit](https://github.com/fluent/fluent-bit)**  
  Lightweight and high-performance log and data processor for streaming pipelines.

### Additional Strong Open-Source Options

- **[Kafka Connect](https://github.com/apache/kafka)** with numerous connectors for ETL.
- **[Debezium](https://github.com/debezium/debezium)** — Change data capture for streaming ETL from databases.
- **[Nifi](https://github.com/apache/nifi)** — Data flow automation and ETL with visual interface.
- **[Benthos](https://github.com/benthosdev/benthos)** — Lightweight stream processing with rich ETL capabilities.
- **[Bytewax](https://github.com/bytewax/bytewax)** — Python stream processing framework for custom ETL.
- **[Many Apache Flink** and **Kafka Streams** examples and templates.

**Frameworks for building custom pipelines**: Combine **Apache Kafka**, **Flink**, **RisingWave**, and **Vector** with **dbt** or **Materialize** for complete open-source streaming ETL solutions.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Streaming ETL performance depends heavily on data volume, latency requirements, and infrastructure.
- Self-hosted open-source solutions require robust monitoring and fault tolerance setup.

---

**Made for data engineers, streaming platform architects, and real-time analytics teams.**  
Let's make streaming ETL more open, scalable, and accessible.
