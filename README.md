# Anirudh Vadera

**Software Engineer III @ Walmart Global Tech | Distributed systems, event streaming, and financial data platforms**

[Portfolio](https://anirudh-vadera.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/anirudh-vadera-8836ba237/) · [LeetCode](https://leetcode.com/u/anirudh00711/) · [Email](mailto:anirudhvadera@gmail.com)

I build production systems where correctness, scale, and operational clarity matter. I own services in Walmart's financial ledger, which journals **~$2B a day (~$700B a year)** across **100M+ transactions/day**, working across Kafka, Spark, GCP, and PostgreSQL in Scala, Java, and Python.

<p align="center">
    <img alt="Anirudh Vadera profile banner" width="100%" src="./img/github_profile.jfif" />
</p>

## Featured Projects

| Project | What it is |
| --- | --- |
| [**CodeSage AI**](https://github.com/ANIRUDH-VADERA/CodeSage-AI) | Hybrid retrieval (BM25 + vectors + entity graph) over code, runbooks, and incidents, with cited answers, auto-generated wiki pages, and a PR guardrail that flags changes resembling past outages. Inspired by Karpathy's idea of an LLM-maintained wiki. |
| [**TwinAI**](https://github.com/ANIRUDH-VADERA/TwinAI) | A passive agent that turns an engineer's IDE, terminal, and review activity into a queryable "digital twin" with confidence-scored answers and expert routing. |
| [**GCS Archival Framework**](https://github.com/ANIRUDH-VADERA/gcs-archival-framework) | Age-based archival of cold GCS data with Storage Transfer Service: batch planning, cost estimates, an idempotent job ledger, and verification. |
| [**Portfolio**](https://github.com/ANIRUDH-VADERA/portfolio) | Interactive portfolio built with React and Three.js. |

## Selected Work at Walmart

| Initiative | Impact |
| --- | --- |
| **LATAM Ledger Expansion** | Expanded the ledger to **6 LATAM countries** and **200+ sources** with per-country isolation across Kafka, GCS, and PostgreSQL; posted **10M transactions in 7 days**. |
| **Balanced SAP Document Splitting** | Split multi-currency journals into balanced SAP documents under hard limits (max 995 line items, each under the 99.99B local-currency cap) with FX conversion: **zero rejections across 100K documents**. |
| **Streaming Acknowledgements** | Replaced an hourly batch with a **sub-second** Kafka and Spark Streaming pipeline delivering acks for **100M transactions/day**. |
| **Ending Inventory Reconciliation (Java)** | Event-driven, line-item-level design that cut processing from **1–2 hours to 3–5 minutes**. |
| **Audit Event Listener** | Scala/ZIO service with REST APIs and Pekko parallel processing, load-tested to **100K events/s**; per-event latency from **~5 s to sub-second**. |
| **PySpark-to-PostgreSQL Upsert** | **3 hours to 13 minutes** by bulk-loading with COPY into unlogged staging tables to skip WAL overhead. |
| **Cloud Storage Archival** | Archived **104 TB** of ledger data, saving **$45,000 per year**. |
| **Regression Testing Library** | Ran in CI across **128+ repositories**, cutting production failures by **50%**. |

## Core Stack

- **Languages:** Scala, Java, Python, SQL
- **Backend and Distributed Systems:** Microservices, REST APIs, Event-Driven Architecture, Akka/Pekko, ZIO
- **Streaming and Data:** Kafka, Spark, Spark Streaming, PySpark, Pub/Sub, Airflow, PostgreSQL, BigQuery
- **Cloud and DevOps:** GCP, Docker, Kubernetes, Terraform, Jenkins, ArgoCD
- **Testing and Observability:** ScalaTest, Mockito, integration and load testing, Grafana, Splunk, Apache Superset
- **AI:** LLMs, RAG, vector databases, knowledge graphs

## Ask Me About

- Designing reconciliation systems where one missing line item is a business problem, not just a bug.
- Turning a multi-hour PySpark and PostgreSQL job into a minutes-level one.
- Cost-aware data movement in GCS and BigQuery.
- Building event-driven source-to-ledger-to-SAP pipelines.
- Designing a knowledge twin for engineering teams without ignoring privacy boundaries.

## Highlights

- **LeetCode Knight** (top 5% globally): peak rating 1981, 1,100+ problems, [rank 668 in Weekly Contest 341](https://leetcode.com/contest/weekly-contest-341/ranking/27/?region=global_v2)
- **Making a Difference Award**, Walmart Global Tech, FY2025
- Finalist, Walmart FDF AI Hackathon and DevJams'21 (Google Developer Student Clubs VIT)
- B.Tech in Computer Science, Vellore Institute of Technology (CGPA 9.53/10)
