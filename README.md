# Airbnb Data Engineering & Analytics Assignment

## Overview

This repository contains my submission for the Expernetic Data Engineering Internship Assignment. The project focuses on analyzing Airbnb marketplace data through data engineering processes including data ingestion, profiling, cleaning, enrichment, and dimensional modeling. The objective is to transform raw Airbnb datasets into analytics-ready data and generate meaningful business insights.

---

## Repository Structure

```text
├── notebooks/
│   ├── 01_dataset_familiarization.ipynb
│   └── 02_data_engineering.ipynb
│
├── reports/
│   └── Final_Report.pdf
│
├── data/
│   ├── raw/
│   └── processed/
│
└── README.md
```

---

## Components

### 1. Dataset Familiarization Notebook

**File:** `notebooks/01_dataset_familiarization.ipynb`

This notebook covers:

* Dataset exploration
* Schema documentation
* Primary and foreign key identification
* Dataset relationships
* Data dictionary review
* Dataset limitations and assumptions
* Business domain understanding

---

### 2. Data Engineering Notebook

**File:** `notebooks/02_data_engineering.ipynb`

This notebook covers:

* Data ingestion and profiling
* Data quality assessment
* Missing value analysis
* Duplicate detection
* Data cleaning and standardization
* Dataset enrichment and joining
* Dimensional modeling (Star Schema)
* SQL-based analytical queries
* Pipeline design considerations

---

### 3. Final Report

**File:** `dataengineering report pdf`

The report includes:

* Executive Summary
* Objectives and Scope
* Dataset Overview
* Methodology
* Engineering Approach
* Exploratory Data Analysis Findings
* Statistical Findings
* Business Recommendations
* Limitations and Future Improvements
* Reflection
* AI Usage Disclosure

---

## Review Order

For the best understanding of the project, review the artifacts in the following order:

1. `reports/Final_Report.pdf`
2. `notebooks/01_dataset_familiarization.ipynb`
3. `notebooks/02_data_engineering.ipynb`

---

## How to Run

### Requirements

Python 3.10+

Recommended libraries:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn duckdb jupyter
```

### Running the Notebooks

1. Open Jupyter Notebook or Google Colab.
2. Open `01_dataset_familiarization.ipynb`.
3. Run all cells sequentially.
4. Open `02_data_engineering.ipynb`.
5. Run all cells sequentially.

---

## Dataset Source

The project uses Airbnb datasets obtained from the Inside Airbnb platform.

Datasets analyzed include:

* listings.csv
* reviews.csv
* calendar.csv
* neighbourhoods.csv

---

## Data Privacy & Security

* No API keys or credentials are included in this repository.
* No personal or sensitive information has been collected or stored.
* All data used is publicly available and intended for research and analytical purposes.

---

## Author

Submitted as part of the Expernetic Data Engineering Internship Assessment.
