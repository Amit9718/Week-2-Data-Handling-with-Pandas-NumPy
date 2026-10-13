# Week 2: Data Handling with Pandas & NumPy

## Overview

Week 2 focuses on data manipulation using two of the most essential Python libraries for Data Science — **Pandas** and **NumPy**. Practiced loading real data, cleaning it, and extracting insights through filtering, sorting, and grouping.

## Tools & Environment

- Platform: Google Colab
- Language: Python 3
- Libraries: `pandas`, `numpy`

## Topics Covered

| Cell | Topic | What I Practiced |
|------|-------|-----------------|
| Cell 1 | NumPy Basics | Arrays, shape, dtype, sum, mean, max, min |
| Cell 2 | NumPy 2D Array | Matrix creation, slicing, arithmetic |
| Cell 3 | Pandas Series & DataFrame | Creating Series and DataFrame from dict |
| Cell 4 | Load CSV File | `to_csv()`, `read_csv()`, `info()`, `shape` |
| Cell 5 | Filtering & Sorting | Boolean filtering, `sort_values()` |
| Cell 6 | Grouping & Aggregation | `groupby()`, `mean()`, `max()`, `min()` |
| Cell 7 | Handling Missing Data | `isnull()`, `fillna()` with mean |

## Notebook

[Week_2_Data_Handling_with_Pandas_and_NumPy.ipynb](./Week_2_Data_Handling_with_Pandas_and_NumPy.ipynb)

## Key Concepts

- NumPy arrays are faster and more efficient than Python lists for numerical data
- Pandas DataFrame is like a table — rows and columns with labels
- Filtering uses boolean conditions to select specific rows
- Groupby splits data into groups and applies aggregate functions
- Missing values (`NaN`) should be handled before analysis

## Sample Output

```
Array: [1 2 3 4 5]  |  Mean: 3.0
DataFrame: 5 rows x 4 columns
Score > 85: Bob, Diana, Eve
Average Score — Science: 83.67 | Arts: 86.0
Missing values filled with column mean
```

## Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Guide](https://numpy.org/doc/stable/)
- [Google Colab](https://colab.research.google.com)

## Progress

- [x] Week 1 — Python Basics & Environment Setup
- [x] Week 2 — Data Handling with Pandas & NumPy
- [ ] Week 3 — Coming soon...
