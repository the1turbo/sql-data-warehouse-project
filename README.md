# Data Warehouse and Analytics Project 🚀

Welcome to the **Data Warehouse and Analytics Project** repository!

This project demonstrates a complete **Data Warehousing and Analytics** solution, from ingesting raw data to generating actionable business insights. It showcases industry best practices in **Data Engineering**, **Data Modeling**, and **Analytics**.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture** approach with **Bronze**, **Silver**, and **Gold** layers.

<img width="1171" height="601" alt="Untitled Diagram drawio" src="https://github.com/user-attachments/assets/8114e83d-9716-4b18-a8bd-a7c3f100968a" />

### Bronze Layer
- Stores raw data exactly as received from source systems.
- Data is loaded from CSV files into SQL Server.
- No transformations are applied.

### Silver Layer
- Performs data cleansing and standardization.
- Handles normalization and quality improvements.
- Prepares data for analytics and reporting.

### Gold Layer
- Contains business-ready datasets.
- Implements dimensional modeling using a Star Schema.
- Optimized for reporting and analytical workloads.

---

## 📖 Project Overview

This project includes:

### Data Architecture
Designing a modern Data Warehouse using the Medallion Architecture approach.

### ETL Pipelines
Building ETL/ELT processes to:
- Extract data from source systems.
- Transform and clean data.
- Load data into the warehouse.

### Data Modeling
Creating:
- Fact Tables
- Dimension Tables
- Star Schema Models

### Analytics & Reporting
Developing SQL-based analytics and reports to generate business insights.

---

## 🎯 Skills Demonstrated

This project showcases expertise in:

- SQL Development
- Data Warehousing
- Data Engineering
- ETL/ELT Development
- Data Modeling
- Data Analytics
- Business Intelligence (BI)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|---------|
| SQL Server Express | Database Engine |
| SSMS | Database Management |
| Draw.io | Architecture & Data Modeling |
| Git & GitHub | Version Control |
| Notion | Project Management |
| CSV Files | Source Data |

---

## 🚀 Project Requirements

### Data Engineering

#### Objective
Develop a modern Data Warehouse using SQL Server to consolidate sales data and support analytical reporting.

#### Specifications

- Import data from ERP and CRM systems using CSV files.
- Clean and resolve data quality issues.
- Integrate source systems into a unified analytical model.
- Focus on the latest available dataset.
- Provide clear documentation for technical and business users.

---

### 📊 Analytics & Reporting

#### Objective
Develop SQL-based analytics to provide insights into:

- Customer Behavior
- Product Performance
- Sales Trends

These insights support data-driven decision-making and business growth.



## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```

---

## 📈 Data Flow

```text
ERP / CRM
    ↓
 Bronze Layer
    ↓
 Silver Layer
    ↓
 Gold Layer
    ↓
 Analytics & Reporting
```

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star.
