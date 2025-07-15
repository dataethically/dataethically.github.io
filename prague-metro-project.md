---
layout: page
title: Prague Metro Data Pipeline
subtitle: Production-scale data engineering with Apache Airflow
---

# Prague Metro Data Pipeline Project

## Project Overview

A comprehensive data engineering project that simulates building a production-scale data pipeline for Prague's metro transit system. The project focuses on processing passenger tap data, fare information, and station analytics to support data-driven decision making for transit operations.

## Technical Architecture

### Core Technologies
- **Orchestration**: Apache Airflow with Docker containerization
- **Data Lake**: MinIO (S3-compatible) object storage with Parquet format
- **Data Warehouse**: PostgreSQL 15 with dimensional modeling
- **Analytics**: Grafana dashboards for business intelligence

### Key Achievements
- **Scalable Pipeline**: Daily processing with retry logic and error handling
- **Data Quality**: Robust validation and monitoring systems
- **Business Intelligence**: Real-time dashboards for transit management
- **Dimensional Modeling**: Star schema with fact and dimension tables

## Business Impact
- **Resource Optimization**: Data-driven train allocation recommendations
- **Customer Insights**: Demographic usage patterns for service planning
- **Operational Intelligence**: Real-time dashboards for transit management

**Technologies**: Apache Airflow, PostgreSQL, Docker, Python, DuckDB, Grafana, MinIO, Parquet
EOF < /dev/null