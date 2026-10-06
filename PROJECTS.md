# Selected Professional Projects

[Back to my profile](README.md)

These summaries describe my responsibilities and the problems I worked on across data platforms, machine learning, and analytics.

## Current Project — Data Lakehouse

**October 2025–present**

I am working on the construction and evolution of a Databricks lakehouse, designing its platform architecture and supporting Data Engineering projects as new data use cases are incorporated.

My focus is on shared data foundations and reusable platform capabilities that help projects adopt new data use cases consistently.

I am also redefining the architecture around hub-and-spoke. Separate schemas for each project had led to duplicated data; the redesign aims to establish shared data foundations that multiple use cases can reuse.

## ML Migration — Baggage Connection Risk

**Within my machine learning work, 2021–2023**

The existing solution predicted whether passengers would miss their connections, supporting baggage handling decisions. My responsibility was to migrate the model implementation from an on-premise environment to Azure Databricks.

I refactored the Python codebase, reimplemented classification logic using XGBoost, and validated model behavior after migration. I worked with platform engineers responsible for integration into operational systems.

## Forecasting — Airport Passenger Volumes

**Within my machine learning work, 2021–2023**

This project forecast daily airport passenger volumes to support route planning and capacity management during the pandemic.

I built a pipeline that retrieved daily data through an API, stored it in Azure Data Lake, and processed it in Databricks. The load strategy supported rerunning a given execution date without accumulating duplicate loads.

I implemented Holt-Winters forecasting to capture trend and weekly seasonality, with historical backtesting to compare predictions against observed volumes.

## Data Warehousing — Banking Risk

**Within my banking consulting work, 2015–2018**

My work progressed from BI reporting to development for a risk data warehouse. I developed ETL logic in T-SQL on Sybase IQ, optimized queries and indexing, and orchestrated pipelines with UC4.

I also used metadata tables to automate environment migrations. This work established the foundations of my approach to data modeling, performance tuning, and reusable data engineering.

## Further Background

For more about my professional background, visit [LinkedIn](https://www.linkedin.com/in/enriquebenito1987). For technical notes, research, and learning material, explore my [knowledge map](KNOWLEDGE_MAP.md).
