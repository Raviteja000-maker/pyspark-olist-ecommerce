# PySpark E-Commerce Analytics — Olist Dataset

This repository contains a Spark-based analytics pipeline built on the Brazilian E-Commerce dataset from Olist. It demonstrates modular data engineering practices using PySpark, from ingestion to serving.

---

## Project Modules

| Module | Notebook | Description |
|--------|----------|-------------|
| Module 1 | `Data Ingestion and Exploration` | Load CSVs, explore schemas, and inspect nulls using PySpark DataFrames. |
| Module 2 | `Data Cleaning and Transformation` | Format dates, cast types, handle missing values, and normalize columns. |
| Module 3 | `Data Integration and Aggregation` | Join multiple datasets and generate KPIs like monthly revenue and customer order behavior. |
| Module 4 | `Property Optimization` | Apply Spark optimizations: partitioning, broadcasting, and query tuning for performance. |
| Module 5 | `Data Serving` | Final data preparation for storage or BI consumption, and exporting results. |

---

## Dataset

- Source: [Kaggle - Brazilian E-Commerce by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Format: CSV files (not included in the repo)
- Location: `data/` directory (locally stored, excluded from Git)

---

## Technologies Used

- Apache Spark (PySpark)
- Jupyter Notebooks
- Google Cloud Dataproc (optional)
- Pandas (for preview/validation)
- Parquet (for output data)

---

## How to Use

1. Start a Spark session (locally or in Dataproc).
2. Run each notebook sequentially:
   - Module 1 → Module 5
3. Adjust file paths in `data/` if running in a different environment.

---

## Repository Structure
pyspark-olist-ecommerce/
├── README.md
├── .gitignore
├── data/                             
├── images/                           
├── Module 1 - Data Ingestion and Exploration.ipynb
├── Module 2 - Data Cleaning and Transformation.ipynb
├── Module 3 - Data Integration and Aggregation.ipynb
├── Module 4 - Property Optmization.ipynb
├── Module 5 - Data Serving.ipynb