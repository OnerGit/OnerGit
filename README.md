# Hi, I'm OnerGit

I'm a Python Data Workflow Developer building small, reproducible projects for API data extraction, CSV/Excel data cleaning, JSON transformation, ETL, data validation, and reporting automation.

My current focus is helping small teams turn messy API, CSV, Excel, and JSON data into clean, validated, reporting-ready workflows.

## Current focus

* API / CSV / Excel / JSON data input
* data cleaning, validation, and transformation
* JSON flattening for reporting-ready tables
* data quality checks for handoff and review
* CSV, SQLite, PostgreSQL, and Parquet output
* PostgreSQL reporting tables and lightweight SQL views
* BI-ready handoff notes for local reporting workflows
* AI-ready data handoff artifacts without calling LLM APIs
* lightweight FastAPI data validation services
* pytest-based project checks
* Docker-based local development
* clear README files, screenshots, limitations, and usage notes

## Featured projects

### Data Quality ETL Starter

A small Python data quality ETL starter for cleaning, validating, exporting, and reporting messy CSV, Excel, JSON, and mock API-style data.

This is my main portfolio project for Python data workflow development.

It demonstrates a repeatable data workflow:

```text
messy CSV / Excel / JSON / mock API-style data
        ↓
read and flatten
        ↓
normalize columns
        ↓
validate expected schema rules
        ↓
clean duplicate rows and text values
        ↓
export cleaned CSV + SQLite / optional PostgreSQL
        ↓
generate data quality reports
```

It also includes an optional analytics-ready path:

```text
generated messy order data
        ↓
existing validation and cleaning logic
        ↓
cleaned CSV
        ↓
cleaned Parquet
        ↓
DuckDB query demo
        ↓
summary CSV tables + benchmark report
```

It also includes an optional BI-ready path:

```text
generated messy order data
        ↓
validation and cleaning workflow
        ↓
analytics-ready order rows
        ↓
PostgreSQL reporting tables
        ↓
lightweight SQL views
        ↓
optional Metabase local dashboard demo
```

It also includes an optional AI-ready data preparation path:

```text
generated messy order data
        ↓
validation and cleaning workflow
        ↓
cleaned orders dataset
        ↓
schema profile JSON
        ↓
data dictionary JSON
        ↓
validation summary JSON
        ↓
feature-ready CSV
        ↓
embedding-ready text field extract
        ↓
AI-ready manifest + Markdown summary report
```

What it shows:

* CSV, Excel, JSON, and mock API-style input
* nested JSON flattening
* column normalization
* Pydantic-based workflow and schema models
* missing value, duplicate, email, date, and number validation
* cleaned CSV output
* SQLite output by default
* optional PostgreSQL export
* optional FastAPI validation service
* optional generated order data for larger workflow demos
* optional analytics-ready CSV and Parquet export
* optional DuckDB local analytics query demo
* optional PostgreSQL reporting tables and SQL views
* optional Metabase local dashboard demo
* optional AI-ready data preparation artifacts
* schema profile JSON
* data dictionary JSON
* validation summary JSON
* feature-ready CSV output
* embedding-ready text field extract
* AI-ready manifest and Markdown summary report
* Markdown and JSON data quality reports
* lightweight summary tables
* benchmark report and BI summary report
* CLI execution
* pytest tests
* Docker-based execution
* practical documentation and screenshots

Repo: https://github.com/OnerGit/data-quality-etl-starter

Related writing:

* Preparing AI-Ready Data Without Calling an LLM API
  https://dev.to/bob_oner/preparing-ai-ready-data-without-calling-an-llm-api-5daf

* From Clean Data to BI-Ready Reporting Tables with Python, PostgreSQL, and Metabase
  https://dev.to/bob_oner/from-clean-data-to-bi-ready-reporting-tables-with-python-postgresql-and-metabase-348p

* From Data Quality Checks to Analytics-Ready Parquet with Python
  https://dev.to/bob_oner/from-data-quality-checks-to-analytics-ready-parquet-with-python-39bd

* Build a Python Data Quality ETL Starter for Messy CSV, Excel, JSON, and API-Style Data
  https://dev.to/bob_oner/build-a-python-data-quality-etl-starter-for-messy-csv-excel-json-and-api-style-data-46b

### FastAPI CSV Quality API

A lightweight FastAPI service that accepts CSV uploads and returns structured JSON data quality reports.

This project demonstrates how a data validation workflow can be packaged as a small API service.

What it shows:

* CSV upload handling
* pandas-based data quality checks
* row count and column count analysis
* missing value checks
* duplicate row detection
* empty column detection
* optional expected-column validation
* Pydantic response models
* structured error handling
* pytest coverage
* Docker packaging
* Swagger UI screenshots and documentation

Repo: https://github.com/OnerGit/fastapi-csv-quality-api

Related writing:

* Build a CSV Data Quality API with FastAPI, Pandas, Pytest, and Docker
  https://dev.to/bob_oner/build-a-csv-data-quality-api-with-fastapi-pandas-pytest-and-docker-28ld

### ChatGPT Long Conversation Helper

A privacy-first Tampermonkey userscript for navigating long ChatGPT conversations locally in the browser.

This is not my main data workflow direction, but it demonstrates my engineering habits: small scope, local-first design, readable implementation, privacy boundaries, manual testing, documentation, screenshots, and clear limitations.

What it shows:

* browser-side UI enhancement
* collapse / expand controls
* MutationObserver support
* localStorage-based UI state
* no external API calls
* no telemetry
* no content upload
* practical troubleshooting notes

Repo: https://github.com/OnerGit/ChatGPT-Long-Conversation-Helper

Related writing:

* Build a Privacy-First Tampermonkey Script for Long ChatGPT Conversations
  https://dev.to/bob_oner/build-a-privacy-first-tampermonkey-script-for-long-chatgpt-conversations-2765

## Writing samples

### Project-based tutorials

* Preparing AI-Ready Data Without Calling an LLM API
  https://dev.to/bob_oner/preparing-ai-ready-data-without-calling-an-llm-api-5daf

* From Clean Data to BI-Ready Reporting Tables with Python, PostgreSQL, and Metabase
  https://dev.to/bob_oner/from-clean-data-to-bi-ready-reporting-tables-with-python-postgresql-and-metabase-348p

* From Data Quality Checks to Analytics-Ready Parquet with Python
  https://dev.to/bob_oner/from-data-quality-checks-to-analytics-ready-parquet-with-python-39bd

* Build a Python Data Quality ETL Starter for Messy CSV, Excel, JSON, and API-Style Data
  https://dev.to/bob_oner/build-a-python-data-quality-etl-starter-for-messy-csv-excel-json-and-api-style-data-46b

* Build a CSV Data Quality API with FastAPI, Pandas, Pytest, and Docker
  https://dev.to/bob_oner/build-a-csv-data-quality-api-with-fastapi-pandas-pytest-and-docker-28ld

* Build a Privacy-First Tampermonkey Script for Long ChatGPT Conversations
  https://dev.to/bob_oner/build-a-privacy-first-tampermonkey-script-for-long-chatgpt-conversations-2765

### Engineering reflection

* AI-Assisted Development Is Not Autopilot
  https://dev.to/bob_oner/ai-assisted-development-is-not-autopilot-15ie

## Working style

I prefer small, practical engineering projects that are:

* runnable locally
* easy to test
* clearly documented
* honest about limitations
* based on realistic workflow problems
* structured for handoff and maintenance
* simple enough for a client or reviewer to inspect

I do not try to present every project as production infrastructure. I focus on clear, reviewable starter projects that can be adapted into client-specific workflows.

## What I can help with

My current portfolio is most relevant to projects such as:

* cleaning messy CSV or Excel files
* validating required columns before reporting
* converting nested JSON into tabular data
* turning API-style data into CSV / Excel-ready outputs
* building repeatable Python ETL scripts
* generating data quality reports
* exporting cleaned data to SQLite or PostgreSQL
* preparing cleaned CSV / Parquet files for local analytics
* creating lightweight summary tables for reporting
* preparing PostgreSQL reporting tables and SQL views
* creating BI-ready handoff notes for local reporting workflows
* preparing schema profiles and data dictionaries
* creating validation summaries for downstream review
* preparing feature-ready CSV files
* extracting embedding-ready text fields without generating embeddings
* creating AI-ready data manifests without calling LLM APIs
* packaging a data validation workflow as a small FastAPI service
* adding tests, documentation, and handoff notes to existing scripts

## What this is not

My current portfolio is intentionally not focused on:

* enterprise data platforms
* production data warehouses
* Airflow / dbt / Spark pipelines
* Snowflake / Databricks projects
* full-stack SaaS applications
* production BI platform management
* Metabase production deployment
* LLM applications
* LLM-based data cleaning tools
* embedding generation pipelines
* vector database projects
* machine learning training pipelines
* prompt engineering frameworks
* RAG chatbots
* AI agents

The current goal is narrower: small, runnable, testable Python data workflows for cleaning, validation, export, reporting preparation, AI-ready data handoff, and documentation.

## Core stack

Python, pandas, FastAPI, Pydantic, pytest, Docker, API integration, CSV/Excel processing, JSON flattening, data validation, ETL, SQLite, PostgreSQL, Parquet, DuckDB, SQL views, reporting automation, schema profiling, data dictionaries, validation summaries, browser userscripts, and technical documentation.
