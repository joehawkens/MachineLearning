# Machine Learning

# Quick Reference:

## Setting up the Data

- Import pandas as pd
- data = pd.read_csv("https://raw.githubusercontent.com/byui-cse/cse450-course/master/data/netflix_titles.csv")
- data.head(5), shows the first 5 rows of the dataset.
- data.tail(5), shows the last 5 rows of the dataset.
- data.info(), shows technical information regarding each column (datatype, name)
- data.count(), total non-null rows for the data.
- data.shape[0], accesses a tuple that contains 0 - Rows and 1 - Columns - will print the amount of each, including null values.

## Exploring the Data (Visualization Tools) - Pandas and Altair

- Import altair as at
