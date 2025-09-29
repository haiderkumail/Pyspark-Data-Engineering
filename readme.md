PySpark Data Engineering Project

This project demonstrates how to build a data engineering pipeline using PySpark. The focus is on working with large datasets, applying transformations, and storing optimized outputs in Parquet format — a key skill in modern data engineering.

Project Structure:
├── data/                # Raw and processed data
├── solution.ipynb       # Jupyter notebook with implementation
├── requirements.txt     # Python dependencies
└── readme.md            # Project documentation

Tech Stack:

Python 3.9+

PySpark for distributed data processing

Pandas for lightweight operations

Parquet/CSV for data storage formats

Features:

Ingest raw CSV datasets

Convert to Parquet for optimized storage

Apply cleaning and transformations (filtering, type casting, null handling)

Partition data for faster queries

Generate aggregated results for analytics

How to Run:

Clone the repo:

git clone https://github.com/haiderkumail/Pyspark-Data-Engineering.git
cd Pyspark-Data-Engineering


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook solution.ipynb


Run all cells to execute the pipeline.

Example Workflow:

Bronze Layer – Load raw CSV into Parquet

Silver Layer – Clean and partition Parquet data

Gold Layer – Aggregate for reporting/analytics

Learning Outcomes:

Working with PySpark DataFrames

Understanding Parquet format and why it’s used in big data

Applying Medallion Architecture (Bronze → Silver → Gold)

Optimizing storage and queries with partitioning

Contributing:

Contributions are welcome! Please open an issue or submit a pull request.

Contact:

Created by Kumail Haider — feel free to reach out hkumail245@gmail.com for feedback or collaboration.
