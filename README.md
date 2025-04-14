# README: ETL Pipelines Tutorial | World Bank Datasets

This notebook documents my learning journey through the ETL (Extract, Transform, Load) process using World Bank datasets. This work is inspired by and builds upon the knowledge gained from Udacity's Data Scientist Nanodegree program, which significantly enhanced my understanding of advanced data science concepts, particularly PySpark. I extend my sincere gratitude to Udacity for providing such high-quality educational content.

**ETL stands for Extract, Transform, Load.**

This lesson focuses on utilizing data from the World Bank, sourced from the following locations:

* **[World Bank Indicator Data](https://data.worldbank.org/indicator)**: Contains socio-economic indicators for countries worldwide, such as population, arable land, and central government debt.
* **[World Bank Project Data](https://datacatalog.worldbank.org/dataset/world-bank-projects-operations)**: Provides information about World Bank project lending activities since 1947.

#### Outline of this notebook:

**Extract data from different sources such as:**

* CSV files
* JSON files
* APIs

**Transform data:**

* Combining data from different sources
* Data cleaning
* Data types management
* Parsing dates
* Handling file encodings
* Addressing missing data
* Managing duplicate data
* Creating dummy variables
* Removing outliers
* Scaling features
* Engineering new features

**Load:**

* Sending the transformed data to a database

**ETL Pipeline:**

* Developing a Python script to automate the ETL process

The primary objective of this notebook is to clean and integrate these distinct datasets into a unified table. As you'll observe, this process involves several complexities. By the conclusion of this notebook, an ETL pipeline will be implemented to extract, transform, and load the data into a new database.

The ultimate goal is to merge these datasets to enable the development of a machine learning model capable of predicting the total costs of World Bank projects.

This process will necessitate various data transformations. Finally, a comprehensive Python module will be created to read these datasets, perform the necessary transformations, and load the resulting data into a database in a single, automated step.

# Importing necessary libraries for the project
```python
import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
