# Basic Data Exploration and Cleaning using Pandas

## Project Overview
In this project, I performed basic data exploration and data cleaning using the Pandas library in Python on the `tops.csv` dataset.

## Tasks Performed
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
- Cleaned the `final_price` column
- Created a derived column: `discount_amount`
- Saved the cleaned dataset as a new CSV file

## Technologies Used
- Python
- Pandas
- Jupyter Notebook

## Files Included
- `Data_Cleaning.ipynb`
- `tops.csv`
- `cleaned_tops.csv`

## Derived Column
```python
discount_amount = initial_price - final_price
```

## Output
Cleaned dataset saved as:

```text
cleaned_tops.csv
```
