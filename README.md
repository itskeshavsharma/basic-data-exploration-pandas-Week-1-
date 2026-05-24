# Pandas Data Cleaning Projects

## Overview
This repository contains beginner-friendly data exploration and data cleaning projects completed using Python, Pandas, and Jupyter Notebook during my Celebal Technologies Internship.

In these projects, I worked with real-world ecommerce datasets and learned how to clean, explore, and transform raw data for analysis.

---

# Projects Included

## 1. Ecommerce Data Cleaning

### Dataset Used
- tops.csv

### Tasks Performed
- Loaded CSV dataset using Pandas
- Explored dataset using:
  - head()
  - tail()
  - shape
  - columns
  - dtypes
  - info()
- Checked and handled missing values
- Removed duplicate rows
- Filtered high-rated products
- Cleaned the final_price column
- Created derived column:
  ```python
  discount_amount = initial_price - final_price
  ```
- Saved cleaned dataset as cleaned_tops.csv

---

## 2. Jackets Data Cleaning

### Dataset Used
- jackets.csv

### Tasks Performed
- Explored and analyzed jackets dataset
- Handled missing values using fillna()
- Removed duplicate records
- Filtered expensive jackets
- Cleaned final_price column by removing currency symbols
- Converted price column into float datatype
- Created derived column:
  ```python
  price_difference = initial_price - final_price
  ```
- Saved cleaned dataset as cleaned_jackets.csv

---

# Skills Learned

Through these projects, I learned:

- Data Exploration
- Data Cleaning
- Handling Missing Values
- Removing Duplicate Rows
- Filtering Data
- Creating Derived Columns
- CSV File Handling
- Data Transformation
- Working with Real-World Datasets
- Pandas Operations

---

# Technologies Used

- Python
- Pandas
- Jupyter Notebook

---

# Repository Structure

```text
pandas-data-projects/
│
├── Ecommerce-Data-Cleaning/
│   ├── tops.csv
│   ├── cleaned_tops.csv
│   ├── ecommerce_cleaning.ipynb
│
├── Jackets-Data-Cleaning/
│   ├── jackets.csv
│   ├── cleaned_jackets.csv
│   ├── jackets_cleaning.ipynb
│
└── README.md
```

---

# About

These projects were created as part of my learning journey during my Celebal Technologies Internship to strengthen my understanding of data analysis and data cleaning using Python and Pandas.
