# Global-Electronics-Retailer
Sales data for a fictitious global electronic retailer, including tables containing information about transactions, products, customers, stores and currency exchange rates.

## Table of Contents

- [Project Overview](#project-overview)
- [File Structure](#file-structure)
- [Data Sources](#data-sources)
- [Conclusion](#Conclusion)

## Project Overview

This repository contains a series of analyses related to customer behavior, store performance, and product trends, using data from the company's sales transactions. Each notebook focuses on answering specific business questions. The data used for these analyses is stored in CSV files within the data folder, and all analysis scripts are contained in the notebooks folder.

## File Structure

The project contains the following files:

- **data/**: Contains the raw data files, such as `sales.csv`, `products.csv`, `stores.csv`, `customers.csv`, and exchange rates.
- **notebooks/**: Contains Jupyter notebooks for data exploration, cleaning, and analysis.
  - `GER - Data Loading and Cleaning.ipynb`: Notebook for data cleaning and preprocessing.
  - `GER - Analysis 01.ipynb`: Analyzing the types of products sold and customer location.
    This file contains ploty image that could be seen here [GER - Analysis 01.ipynb (in Jupyter Viewer)](https://nbviewer.org/github/migbenav/Global-Electronics-Retailer/blob/bd9a81e0a243c13528bd6e09c018ff93eaadc987/Notebooks/GER%20-%20Analysis%2001.ipynb)
  - `GER - Analysis 02.ipynb`: Identifying seasonal patterns in order volume and revenue
  - `GER - Analysis 03.ipynb`: Calculating and analyzing the average delivery time over time.
  - `GER - Analysis 04.ipynb`: Comparing the average order value for online vs. in-store sales.
  - `GER - Analysis 05.ipynb`: Identifying underperforming stores
  - `GER - Analysis 06.ipynb`: Clustering store performance.
- **README.md**: This file, providing an overview and instructions.

## Data Sources

Original files could be found in [Maven](https://mavenanalytics.io/data-playground?dataStructure=Multiple%20tables&order=date_added%2Cdesc&search=retail)

## Conclusion
This repository provides a detailed exploration of customer and store performance data. Through various analyses, we uncover trends, seasonal behaviors, and the performance of stores, which can guide business strategies and operational decisions.

Feel free to explore each notebook for a detailed walkthrough of the analyses. If you have any questions or suggestions, feel free to open an issue in the repository.
