# Retail Sales ETL Pipeline using Python and Azure Blob Storage

## Overview

This project demonstrates an end-to-end **ETL (Extract, Transform, Load)** pipeline for retail sales data using **Python** and **Microsoft Azure Blob Storage**. The goal is to extract raw sales data, transform it by cleaning and enriching with calculated fields, and load the processed data back into Azure Blob Storage for further analysis or reporting.

---

## Project Structure

- `ETL.ipynb` - Python script performing the ETL operations (extract from blob, transform, and load back).
- `data/` - (Optional) Folder for local datasets (if any).
- `README.md` - This documentation file.

---

## Features

- Connects to Azure Blob Storage to download raw sales data.
- Cleans and processes data using Pandas.
- Filters data based on date.
- Uploads the cleaned data back to Azure Blob Storage.
- Fully cloud-integrated with local Python execution.

---

## Prerequisites

- Python 3.7+
- Azure Storage Account with Blob Storage
- Azure Storage connection string (with access key)
- Installed Python packages:
  - `pandas`
  - `azure-storage-blob`

Install packages using:
```bash
pip install pandas azure-storage-blob
