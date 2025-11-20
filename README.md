# Python-Projects
# 🐍 Python Data Analysis Portfolio: Mastering Pandas for EDA

## Project Overview

This repository showcases a portfolio of projects focused on **Exploratory Data Analysis (EDA)** and data manipulation using the **Python programming language**, with a strong emphasis on the **Pandas library**. The notebooks demonstrate the end-to-end data workflow, from loading raw data to cleaning, transforming, and preparing it for advanced analysis or visualization.

The primary dataset used for practice is **`GDP (nominal) per Capita.csv`**, which contains global economic and demographic statistics from various reporting agencies.

***

## ⚙️ Core Python and Data Science Skills

### 1. Python Fundamentals
* **Coding Principles:** Applied fundamental Python concepts including variable assignment, data structures (lists, dictionaries), control flow (implied through data transformations), and basic function calls.
* **Library Management:** Demonstrated proficiency in importing and aliasing essential libraries (`import pandas as pd`, `import matplotlib.pyplot`, `import seaborn`) to access specialized data analysis functions.
* **Jupyter Notebook Usage:** Utilized Jupyter Notebooks for interactive coding, documentation (Markdown), and step-by-step documentation of the analysis process.

### 2. Pandas Deep Dive: Data Manipulation and Transformation
The Pandas library is the core focus, enabling efficient manipulation of tabular data through the **DataFrame** object. Key skills demonstrated include:

| Pandas Feature | Use Case in Project | Demonstrated Methods |
| :--- | :--- | :--- |
| **Data Ingestion** | Loading external CSV data (e.g., the GDP dataset) into a DataFrame. | `pd.read_csv()` |
| **Data Inspection** | Understanding data structure, checking data types, and identifying initial data quality issues. | `.head()`, `.info()`, `.describe()` |
| **Selection & Filtering** | Isolating specific columns or rows for focused analysis. | `df[['Column Name']]`, Boolean Indexing |
| **Data Cleaning** | Identifying and handling missing or null values in the dataset. | `.isna()`, `.sum()`, `.dropna()`, `.fillna()` |
| **Transformation** | Creating new features, renaming columns, and formatting values for consistency. | Creating new columns, `.rename()`, `.round()` |
| **Exploratory Analysis** | Calculating summary statistics, detecting and handling outliers, and performing initial groupings. | `.value_counts()`, Box Plots/Statistical Methods |
| **Data Export** | Saving the cleaned and transformed DataFrame back to file formats. | `.to_csv()`, `.to_excel()` |

***

## 📝 Project Notebook Deep Dive

### 1. Pandas Day 1: Introduction to DataFrames
* **File:** `Pandas_Day_1.ipynb`, `PandasDataFrames_01_Solutions.ipynb`
* **Focus:** Laying the foundation for Pandas usage.
* **Content:** Covers the basic mechanics of creating DataFrames from existing Python objects, viewing DataFrame properties, selecting single columns, and calculating descriptive statistics on numerical data.
* **Skills Reinforced:** **Data Ingestion**, **Basic Selection**, and **Descriptive Stats**.

### 2. DataFrames Continued: Cleaning and Transformation
* **File:** `Pandas_DataFrames_Continued_01_Solutions.ipynb`
* **Focus:** Addressing data quality issues, specifically **missing values**.
* **Content:** Demonstrates how to systematically identify nulls (`.isna().sum()`), calculate the proportion of missing data, and apply strategies to handle them (e.g., dropping rows or columns with excessive missingness) to ensure data integrity for downstream tasks.
* **Skills Reinforced:** **Data Cleaning (Missing Values)**, **Transformation** (rounding values, exporting clean data).

### 3. Regional Pandas Practice: EDA and Visualization
* **File:** `Regional_Pandas_Practice_Notebook.ipynb`
* **Data Source:** Primarily utilizes the `GDP (nominal) per Capita.csv` dataset.
* **Focus:** Applying comprehensive Pandas skills for **Exploratory Data Analysis (EDA)** and integrating basic visualization tools (Matplotlib/Seaborn).
* **Content:** This notebook combines all foundational skills to analyze a real-world dataset. It includes:
    * **EDA:** Understanding patterns and summary statistics of GDP estimates.
    * **Handling Nulls:** Cleaning the `WorldBank_Estimate` and `UN_Estimate` columns.
    * **Outlier Detection:** Applying statistical or visual methods to identify and manage outliers in the high-value GDP fields.
    * **Data Visualization:** Creating charts to communicate initial insights about regional or country-level GDP differences.
* **Skills Reinforced:** **EDA**, **Outlier Handling**, **Visualization Integration**.

***

## 📂 Repository Files

| File Name | Type | Description |
| :--- | :--- | :--- |
| `GDP (nominal) per Capita.csv` | CSV Dataset | Real-world dataset used for all analytical practice notebooks. Contains GDP estimates from various sources. |
| `Pandas_Day_1.ipynb` | Jupyter Notebook | Introductory practice covering basic DataFrame creation, selection, and inspection. |
| `PandasDataFrames_01_Solutions.ipynb` | Jupyter Notebook | Solution notebook for introductory Pandas tasks, including renaming and descriptive statistics. |
| `Pandas_DataFrames_Continued_01_Solutions.ipynb` | Jupyter Notebook | Advanced practice focusing on identifying, counting, and removing missing values in DataFrames. |
| `Regional_Pandas_Practice_Notebook.ipynb` | Jupyter Notebook | Comprehensive notebook demonstrating Exploratory Data Analysis (EDA), outlier handling, and data visualization using the GDP data. |

***

## 🚀 Getting Started

1.  **Clone the Repository:** Download the files to your local machine.
2.  **Install Dependencies:** Ensure you have Python, Pandas, Matplotlib, and Seaborn installed (`pip install pandas matplotlib seaborn`).
3.  **Launch Jupyter:** Open the `.ipynb` files in Jupyter Notebook or VS Code to review and run the code cells interactively.
