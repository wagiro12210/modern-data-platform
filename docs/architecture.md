# Modern Metadata-Driven Data Platform

## Purpose

This project implements a modern data platform focused on metadata-driven
orchestration, reusable data pipelines, dependency management, data quality,
and observability.

The platform will evolve incrementally as new Data Engineering technologies
are incorporated.

## Initial Architecture

The initial data flow will follow this structure:

Sources
  |
  v
Ingestion
  |
  v
Transformation
  |
  v
Data Platform
  |
  v
Consumption

Metadata will progressively be used to control pipeline configuration,
dependencies, execution, and monitoring.

## Main Components

### Sources
Data can originate from relational databases, APIs, and files.

### Ingestion
Python-based processes will extract and load data into the platform.

### Transformation
Transformation logic will evolve toward tools such as dbt and PySpark.

### Orchestration
Pipeline execution and dependencies will be managed by an orchestration layer.

### Metadata
Technical metadata will describe datasets, pipelines, dependencies, and
execution configuration.

### Data Quality
Automated validations will verify data integrity, freshness, and consistency.

### Observability
Pipeline execution, failures, execution times, and data quality results will
be monitored.

## Project Evolution

The architecture will evolve throughout the Modern Data Engineer bootcamp.

Future iterations will introduce:

- Python data pipelines
- REST API ingestion
- Docker
- PostgreSQL
- dbt
- Apache Airflow
- Data quality and observability
- BigQuery and GCP
- PySpark
- Databricks and Delta Lake
- Metadata-driven orchestration
- Data lineage
- CI/CD
- Infrastructure as Code