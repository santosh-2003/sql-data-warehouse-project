---

# Data Warehouse Project

Welcome to the **Data Warehouse Project** repository! 🚀
This project demonstrates the design and development of a modern data warehouse — from raw data ingestion to building a star schema. Designed as a portfolio project, it follows industry best practices in data engineering and modeling.

---

## 🏗️ Data Architecture

The architecture follows the **Medallion Architecture**:

* **Bronze Layer**: Stores raw data as-is from source systems (CSV to SQL Server DB).
* **Silver Layer**: Cleansed, standardized, and normalized data.
* **Gold Layer**: Business-ready data modeled into a star schema.

---

## 📖 Project Overview

The project includes:

1. **Data Architecture**: Medallion Architecture (Bronze, Silver, Gold).
2. **ETL Pipelines**: Extract, transform, and load from source systems to the data warehouse.
3. **Data Modeling**: Build fact and dimension tables for future analytics use.

### Skills Demonstrated:

* SQL Development
* Data Architecture
* ETL Pipeline Development
* Data Modeling
* Data Engineering

---

## 🛠️ Tools & Resources

* **Datasets**: Located in `/datasets/` (CSV format).
* **SQL Server Express**: Host your SQL databases.
* **SQL Server Management Studio (SSMS)**: GUI to manage your databases.
* **DrawIO**: Create architecture diagrams, data flows, and models.
* **Notion Project Template**: Organize your tasks and phases.
* **Notion Project Steps**: Detailed breakdown of all steps.

---

## 🚀 Project Requirements

### Data Engineering – Build the Data Warehouse

#### Objective

Build a modern data warehouse using SQL Server to consolidate sales data for future reporting.

#### Key Points:

* **Sources**: Two systems (ERP and CRM) as CSV files.
* **Data Quality**: Resolve duplicates, missing values, and standardize.
* **Integration**: Merge sources into one star schema for analytics readiness.
* **Scope**: Use only the latest dataset; historization not required.
* **Documentation**: Include a clear data model explanation.

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw ERP & CRM datasets (CSV)
│
├── docs/                               # Documentation & diagrams
│   ├── etl.drawio                      # ETL flow diagram
│   ├── data_architecture.drawio        # Medallion architecture design
│   ├── data_catalog.md                 # Dataset fields & metadata
│   ├── data_flow.drawio                # Data flow overview
│   ├── data_models.drawio              # Star schema modeling
│   ├── naming-conventions.md           # Naming guidelines
│
├── scripts/                            # SQL scripts
│   ├── bronze/                         # Load raw data
│   ├── silver/                         # Clean & transform data
│   ├── gold/                           # Build data models
│
├── tests/                              # Data quality and validation scripts
│
├── README.md                           # Project summary and instructions
├── LICENSE                             # License info
├── .gitignore                          # Git ignore rules
└── requirements.txt                    # Project dependencies
```

---

## 🛡️ License

Licensed under the [MIT License](LICENSE).
Free to use, modify, and share with proper attribution.

---
