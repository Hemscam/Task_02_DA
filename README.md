# Task_02_DA
📊 Exploratory Data Analysis (EDA) — Grocery Retail Data
Internship Task Submission
📁 Project Overview

This project performs a complete Exploratory Data Analysis (EDA) on four datasets related to grocery retail operations, including item-level information, transaction records, wholesale prices, and loss rates.
The purpose of the analysis is to extract meaningful business insights and better understand sales patterns, category behavior, pricing trends, and operational inefficiencies.

🎯 Objectives

Understand the structure and quality of each dataset

Merge datasets into a unified analytical table

Explore distributions, correlations, and missing values

Detect anomalies and outliers

Identify category-level trends

Analyze pricing, quantity sold, and loss rate patterns

Produce insights useful for business decisions

📦 Dataset Description
File Name	Description
annex1.csv	Item master data (item name, category, code)
annex2.csv	Transaction-level sales data (date, time, quantity sold, selling price, discount info)
annex3.csv	Wholesale price information by item
annex4.csv	Item-wise loss rate (%)

After preprocessing, all files were merged using Item Code and Category Code where applicable.

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib

SciPy

Jupyter Notebook

🔍 EDA Steps Performed
✔ 1. Data Understanding

Examined .info(), .shape(), .head(), and column profiles

Checked variable formats and consistency

Verified keys used for merging

✔ 2. Cleaning & Preprocessing

Identified missing values

Visualized missingness using a heatmap

Checked duplicates and inconsistencies

Repaired column name formatting

✔ 3. Merging Strategy

Merged sales, item master, and loss rate data using Item Code

Integrated wholesale pricing using Item Code and Date

Added category attributes using Category Code

✔ 4. Statistical Summary

Generated summary statistics for numerical & categorical features

Computed skewness for numerical variables

✔ 5. Visual Exploration

Histograms for quantity sold, prices, and other numeric fields

Boxplots to detect outliers

Correlation heatmap for numeric variables

Scatter matrix for multivariate relationships

Bar charts for top categories by volume and revenue

✔ 6. Advanced Insights

Z-score based outlier detection

Category-level aggregates using groupby()

Analysis of price behavior (retail vs wholesale)

Loss rate impact on high-volume items

📈 Key Insights (Summary)

Quantity sold shows strong right-skewness, indicating a long-tail distribution.

Wholesale prices differ significantly from retail prices in many items.

Several categories dominate transaction frequency and revenue.

Loss rate varies widely between categories and items.

Missing data mostly appears in wholesale pricing records.

Multiple outliers detected in quantity and price distributions.

Detailed insight breakdown is available in the accompanying Notebook and PDF Report.

📂 Deliverables Included in This Repository

merged_data.csv — Final merged dataset

eda_merged.ipynb — Full Jupyter Notebook with EDA workflow

EDA_Merged_Report.pdf — Visual report summarizing findings
