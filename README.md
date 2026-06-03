# Hi, I'm OnerGit

I'm a Python Data Workflow Developer building small, reproducible projects for API data extraction, CSV/Excel data cleaning, JSON transformation, ETL, data validation, and reporting automation.

My current focus is helping small teams turn messy API, CSV, Excel, and JSON data into clean, validated, reporting-ready workflows.

## Current focus

* API / CSV / Excel / JSON data input
* data cleaning, validation, and transformation
* JSON flattening for reporting-ready tables
* CSV, SQLite, and PostgreSQL output
* data quality reports for handoff and review
* lightweight FastAPI data services
* pytest-based project checks
* Docker-based local development
* clear README files, screenshots, limitations, and usage notes

## Featured projects

### Data Quality ETL Starter

A small Python data quality ETL starter for cleaning, validating, exporting, and reporting messy CSV, Excel, JSON, and mock API-style data.

This project demonstrates a repeatable data workflow:

```text
messy CSV / Excel / JSON / mock API
        ↓
read and flatten
        ↓
normalize columns
        ↓
validate expected schema rules
        ↓
clean duplicate rows and text values
        ↓
export cleaned CSV + SQLite / PostgreSQL
        ↓
generate data quality report
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
* Markdown and JSON quality reports
* CLI execution
* pytest tests
* Docker-based execution
* practical documentation and screenshots

Repo: https://github.com/OnerGit/data-quality-etl-starter
Related writing: https://dev.to/bob_oner/build-a-python-data-quality-etl-starter-for-messy-csv-excel-json-and-api-style-data-46b

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
Related writing: https://dev.to/bob_oner/build-a-csv-data-quality-api-with-fastapi-pandas-pytest-and-docker-28ld

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
Related writing: https://dev.to/bob_oner/build-a-privacy-first-tampermonkey-script-for-long-chatgpt-conversations-2765

## Writing samples

### Project-based tutorials

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

I do not try to present every project as production infrastructure. I focus on clear, reviewable starter projects that can be adapted into client-specific workflows.

## Core stack

Python, pandas, FastAPI, Pydantic, pytest, Docker, API integration, CSV/Excel processing, JSON flattening, data validation, ETL, SQLite, PostgreSQL, reporting automation, browser userscripts, and technical documentation.
