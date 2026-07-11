# MSCS 634 Lab 1

## Data Visualization, Data Preprocessing, and Statistical Analysis Using Python

### Student
Anna Levinskaia

### Course
2026 Summer – Advanced Big Data and Data Mining (MSCS-634-B01) – Second Bi-term

## Purpose

The purpose of this lab is to demonstrate how Python and Jupyter Notebook can be used to collect, visualize, preprocess, and statistically analyze a dataset. The project uses a sales dataset containing dates, product categories, regions, units sold, unit prices, discounts, customer ratings, and total sales.

## Files

- `MSCS_634_Lab_1.ipynb` – Jupyter Notebook containing all lab steps
- `sales_data.csv` – Original dataset used in the analysis
- `screenshots/` – Folder for the required screenshots
- `README.md` – Project overview and summary

## Main Tasks Completed

1. Loaded the sales dataset into a Pandas DataFrame.
2. Displayed the first five rows of the dataset.
3. Created scatter, line, bar, histogram, box, and pie visualizations.
4. Detected and replaced missing values.
5. Identified and removed outliers using the IQR method.
6. Reduced the dataset using random sampling and column elimination.
7. Applied Min-Max scaling and discretized sales into categories.
8. Used `info()` and `describe()` to examine the dataset.
9. Calculated measures of central tendency and dispersion.
10. Created a correlation matrix for numerical variables.

## Key Insights

- Total sales generally increase when the number of units sold increases.
- The original dataset contains several unusually high sales values.
- The sales distribution is right-skewed because of high-value transactions.
- Missing numerical values were replaced using the mean, while missing categorical values were replaced using the mode.
- Removing extreme sales outliers produced a more representative dataset for statistical analysis.
- Correlation analysis helps identify relationships among units sold, unit price, discount, customer rating, and sales.

## Challenges and Decisions

One challenge was selecting appropriate techniques for handling missing values. Mean replacement was used for numerical values, while mode replacement was used for categorical values. Another challenge was deciding how to manage outliers. The IQR method was selected because it identifies extreme values without assuming that the data follows a normal distribution.

## How to Run

1. Install Python and Jupyter Notebook or use Google Colab.
2. Place `MSCS_634_Lab_1.ipynb` and `sales_data.csv` in the same folder.
3. Open the notebook.
4. Run each cell from top to bottom.
5. Save screenshots of the required outputs in the `screenshots` folder.

## Required Python Libraries

```bash
pip install pandas numpy matplotlib notebook
```
