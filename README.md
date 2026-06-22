# Hi, I'm OnerGit

I'm a Python Data Workflow Developer building small, reproducible projects for API data extraction, CSV/Excel data cleaning, PDF-to-data workflows, JSON transformation, ETL, data validation, and reporting automation.

My current focus is helping small teams turn messy API, CSV, Excel, JSON, PDF, retail, and Shopify-style data into clean, validated, reporting-ready workflows.

## Current focus

* API / CSV / Excel / JSON / PDF data input
* data cleaning, validation, and transformation
* JSON flattening for reporting-ready tables
* text-based PDF extraction review and validation
* PDF-to-CSV / Excel-style handoff workflows
* data quality checks for handoff and review
* CSV, SQLite, PostgreSQL, and Parquet output
* PostgreSQL reporting tables and lightweight SQL views
* BI-ready handoff notes for local reporting workflows
* AI-ready data handoff artifacts without calling LLM APIs
* real retail dataset workflow validation and local benchmark evidence
* Shopify-style API reporting workflow case studies
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

It also includes an optional real retail dataset benchmark path:

```text
manually downloaded public retail dataset
        ↓
prepare and normalize source columns
        ↓
existing validation and cleaning workflow
        ↓
quality reports + SQLite export
        ↓
local benchmark report
        ↓
summary CSV outputs
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
* optional real retail dataset preparation
* local benchmark report
* retail summary CSV outputs
* source and license notes
* Markdown and JSON data quality reports
* lightweight summary tables
* benchmark report and BI summary report
* CLI execution
* pytest tests
* Docker-based execution
* practical documentation and screenshots

Repo: [data-quality-etl-starter](https://github.com/OnerGit/data-quality-etl-starter)

Related writing:

* [Running a Real Retail Dataset Through a Python Data Quality Workflow](https://dev.to/bob_oner/running-a-real-retail-dataset-through-a-python-data-quality-workflow-490b)
* [Preparing AI-Ready Data Without Calling an LLM API](https://dev.to/bob_oner/preparing-ai-ready-data-without-calling-an-llm-api-5daf)
* [From Clean Data to BI-Ready Reporting Tables with Python, PostgreSQL, and Metabase](https://dev.to/bob_oner/from-clean-data-to-bi-ready-reporting-tables-with-python-postgresql-and-metabase-348p)
* [From Data Quality Checks to Analytics-Ready Parquet with Python](https://dev.to/bob_oner/from-data-quality-checks-to-analytics-ready-parquet-with-python-39bd)
* [Build a Python Data Quality ETL Starter for Messy CSV, Excel, JSON, and API-Style Data](https://dev.to/bob_oner/build-a-python-data-quality-etl-starter-for-messy-csv-excel-json-and-api-style-data-46b)

### Shopify-Style API Reporting Workflow

A public case study for turning Shopify-style order, product, customer, and line-item data into validated, normalized, reporting-ready outputs.

This is my vertical e-commerce reporting workflow case study. It applies the same data workflow thinking from `data-quality-etl-starter` to a more specific client-style scenario.

The workflow shape is:

```text
Shopify-style API data
        ↓
pagination-aware workflow design
        ↓
field mapping
        ↓
normalized reporting tables
        ↓
validation and review
        ↓
CSV / Excel / SQLite outputs
        ↓
Markdown report preview
```

What it shows:

* Shopify-style order, product, customer, and line-item data
* mock REST-style workflow evidence
* GraphQL-shaped mock response planning
* pagination-aware reporting workflow design
* field mapping and normalization notes
* CSV / Excel-style output expectations
* SQLite-style reporting table previews
* Markdown report preview
* screenshots and public-safe sample outputs
* implementation boundary notes
* delivery workflow planning
* privacy and customer-data boundary notes
* public/private asset separation

Repo: [shopify-api-reporting-workflow](https://github.com/OnerGit/shopify-api-reporting-workflow)

Related writing:

* [From Mock API Workflow to Delivery-Ready Asset: Extending a Shopify-style Reporting Case Study](https://dev.to/bob_oner/from-mock-api-workflow-to-delivery-ready-asset-extending-a-shopify-style-reporting-case-study-558f)
* [Designing a Shopify-style API Reporting Workflow as a Public Case Study](https://dev.to/bob_oner/designing-a-shopify-style-api-reporting-workflow-as-a-public-case-study-3f9f)

This repository is intentionally a public case-study asset, not a public runnable package. The goal is to show workflow design, output expectations, implementation boundaries, and delivery judgment without exposing reusable private code, credentials, store domains, or client-sensitive material.

### PDF to Clean Data Workflow

A public case study for turning text-based PDFs into structured, reviewable, validated data outputs.

This project covers a common data workflow problem: PDFs often look structured to humans, but extraction quality depends on layout stability, table structure, field validation, partial failure handling, and review checkpoints.

The workflow shape is:

```text
text-based PDF input
        ↓
sample review
        ↓
extraction
        ↓
normalization
        ↓
validation
        ↓
CSV / Excel-style / SQLite-style handoff
        ↓
quality report
        ↓
client review checkpoint
```

What it shows:

* fixed-layout invoice-style extraction
* invoice header and line-item style outputs
* tabular PDF report extraction
* synthetic multi-page table examples
* batch processing across known layouts
* layout detection and transparent detection evidence
* extraction quality scoring
* validation summaries
* expected-vs-actual review files
* selected official public PDF validation samples
* known limitations and failure cases
* public-safe previews
* public/private implementation boundary
* sample review workflow before full-batch processing

Repo: [pdf-to-clean-data-workflow](https://github.com/OnerGit/pdf-to-clean-data-workflow)

Related writing:

* [From Text-Based PDFs to Clean Data: A Practical Workflow Case Study](https://dev.to/bob_oner/from-text-based-pdfs-to-clean-data-a-practical-workflow-case-study-2jga)

This repository is intentionally a bounded PDF-to-data case study. It does not publish the full parser implementation or claim universal PDF support. The current scope is text-based PDFs, reviewed layouts, sample validation, public-safe previews, quality reporting, and known limitations.

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

Repo: [fastapi-csv-quality-api](https://github.com/OnerGit/fastapi-csv-quality-api)

Related writing:

* [Build a CSV Data Quality API with FastAPI, Pandas, Pytest, and Docker](https://dev.to/bob_oner/build-a-csv-data-quality-api-with-fastapi-pandas-pytest-and-docker-28ld)

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

Repo: [ChatGPT-Long-Conversation-Helper](https://github.com/OnerGit/ChatGPT-Long-Conversation-Helper)

Related writing:

* [Build a Privacy-First Tampermonkey Script for Long ChatGPT Conversations](https://dev.to/bob_oner/build-a-privacy-first-tampermonkey-script-for-long-chatgpt-conversations-2765)

## Writing samples

### Project-based tutorials and case studies

* [From Text-Based PDFs to Clean Data: A Practical Workflow Case Study](https://dev.to/bob_oner/from-text-based-pdfs-to-clean-data-a-practical-workflow-case-study-2jga)
* [From Mock API Workflow to Delivery-Ready Asset: Extending a Shopify-style Reporting Case Study](https://dev.to/bob_oner/from-mock-api-workflow-to-delivery-ready-asset-extending-a-shopify-style-reporting-case-study-558f)
* [Designing a Shopify-style API Reporting Workflow as a Public Case Study](https://dev.to/bob_oner/designing-a-shopify-style-api-reporting-workflow-as-a-public-case-study-3f9f)
* [Running a Real Retail Dataset Through a Python Data Quality Workflow](https://dev.to/bob_oner/running-a-real-retail-dataset-through-a-python-data-quality-workflow-490b)
* [Preparing AI-Ready Data Without Calling an LLM API](https://dev.to/bob_oner/preparing-ai-ready-data-without-calling-an-llm-api-5daf)
* [From Clean Data to BI-Ready Reporting Tables with Python, PostgreSQL, and Metabase](https://dev.to/bob_oner/from-clean-data-to-bi-ready-reporting-tables-with-python-postgresql-and-metabase-348p)
* [From Data Quality Checks to Analytics-Ready Parquet with Python](https://dev.to/bob_oner/from-data-quality-checks-to-analytics-ready-parquet-with-python-39bd)
* [Build a Python Data Quality ETL Starter for Messy CSV, Excel, JSON, and API-Style Data](https://dev.to/bob_oner/build-a-python-data-quality-etl-starter-for-messy-csv-excel-json-and-api-style-data-46b)
* [Build a CSV Data Quality API with FastAPI, Pandas, Pytest, and Docker](https://dev.to/bob_oner/build-a-csv-data-quality-api-with-fastapi-pandas-pytest-and-docker-28ld)
* [Build a Privacy-First Tampermonkey Script for Long ChatGPT Conversations](https://dev.to/bob_oner/build-a-privacy-first-tampermonkey-script-for-long-chatgpt-conversations-2765)

### Engineering reflection

* [AI-Assisted Development Is Not Autopilot](https://dev.to/bob_oner/ai-assisted-development-is-not-autopilot-15ie)

## Working style

I prefer small, practical engineering projects that are:

* runnable locally when appropriate
* easy to test
* clearly documented
* honest about limitations
* based on realistic workflow problems
* structured for handoff and maintenance
* simple enough for a client or reviewer to inspect

I do not try to present every project as production infrastructure. I focus on clear, reviewable starter projects and case studies that can be adapted into client-specific workflows.

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
* preparing public retail dataset benchmark workflows
* summarizing retail transaction datasets into reporting-ready CSV outputs
* designing Shopify-style API reporting workflow structures
* mapping order, product, customer, and line-item style data into reporting tables
* preparing CSV / Excel / SQLite / Markdown reporting outputs
* reviewing text-based PDF samples before extraction
* turning known-layout PDF fields or tables into structured outputs
* preparing PDF-to-CSV / Excel-style extraction handoff workflows
* generating PDF extraction quality reports and exception notes
* packaging a data validation workflow as a small FastAPI service
* adding tests, documentation, screenshots, and handoff notes to existing scripts

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
* Shopify app development
* production Shopify connectors
* public Shopify credential handling
* e-commerce web scraping
* lead scraping or gray automation
* universal PDF parsing
* OCR or scanned-PDF processing
* handwriting extraction
* AI document extraction
* production invoice, bank statement, or tender parsers

The current goal is narrower: small, runnable, testable Python data workflows and public-safe case studies for cleaning, extraction, validation, export, reporting preparation, AI-ready data handoff, Shopify-style reporting workflow design, PDF-to-clean-data review, and documentation.

## Core stack

Python, pandas, FastAPI, Pydantic, pytest, Docker, API integration, CSV/Excel processing, JSON flattening, data validation, ETL, SQLite, PostgreSQL, Parquet, DuckDB, SQL views, reporting automation, schema profiling, data dictionaries, validation summaries, text-based PDF extraction review, public-safe workflow documentation, browser userscripts, and technical documentation.
