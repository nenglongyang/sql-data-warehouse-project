# SQL Data Warehouse & Analytics Project

Developed by **Nenglong Yang**

This repository contains an end-to-end SQL Data Warehouse and Business Intelligence solution designed using industry best practices in data engineering, data modeling, and analytical reporting.

---

## 🏗️ Data Architecture

The project implements the **Medallion Architecture** (Bronze, Silver, Gold):

![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Raw data ingestion from CSV source files (ERP & CRM) into SQL Server.
2. **Silver Layer**: Data cleansing, standardization, and normalization.
3. **Gold Layer**: Analytical star schema with optimized fact and dimension tables for reporting.

---

## 📖 Key Features & Scope

* **Data Engineering**: Built ETL pipelines in T-SQL to process raw datasets, handle data quality issues, and integrate disparate data sources (ERP & CRM).
* **Data Modeling**: Designed star schema models (fact and dimension tables) tailored for analytical query performance.
* **Analytics & Insights**: SQL queries and scripts focused on evaluating:
  * Customer Demographics & Behavior
  * Product & Sales Performance Metrics
  * Revenue Trends over Time

---

## 🛠️ Tools & Technologies

* **Database Engine**: Microsoft SQL Server Express
* **IDE / Management**: SQL Server Management Studio (SSMS)
* **Architecture & Modeling**: Draw.io

---

## 📂 Repository Structure


```

data-warehouse-project/
│
├── datasets/          # Raw ERP and CRM source CSV files
├── docs/              # Data architecture diagrams, data models, and data catalog
├── scripts/           # SQL scripts structured by layer
│   ├── bronze/        # Raw data loading scripts
│   ├── silver/        # Cleansing and transformation scripts
│   └── gold/          # Dimensional modeling scripts
├── tests/             # Data validation and testing scripts
├── README.md          # Project overview
└── LICENSE            # MIT License

```

---

## 👨‍💻 About Me

**Nenglong Yang**  
Engineering Researcher & Machine Learning Engineer specializing in data-driven modeling, high-performance computing, automated data pipelines (ETL), and computational solutions.

* **Email**: nenglong.yang.contact@gmail.com
* **LinkedIn**: [Nenglong Yang](https://www.linkedin.com/in/nenglong-yang-aa8392113/)

---

## 🛡️ License

This project is open-source and available under the [MIT License](LICENSE).
