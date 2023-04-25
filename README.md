# Machine Learning

# Quick Reference:

## Setting up the Data

- Import pandas as pd
- data = pd.read_csv("https://raw.githubusercontent.com/byui-cse/cse450-course/master/data/netflix_titles.csv")

## Functions

- data.head(5), shows the first 5 rows of the dataset.
- data.tail(5), shows the last 5 rows of the dataset.
- data.info(), shows technical information regarding each column (datatype, name)
- data.count(), total non-null rows for the data.
- data.shape[0], accesses a tuple that contains 0 - Rows and 1 - Columns - will print the amount of each, including null values.


- data['rating'].value_counts(), counts the amount of data for each attribute.
- data = only_movies[only_movies['rating'].isin(['R', 'PG-13', 'NR', 'PG', 'G', 'UR', 'NC-17'])], filters only those that ARE IN the rating.


## Filtering Data

- only_movies = netflix[netflix['type'] == 'Movie'] - selects only the data that fits with the filter.




## Exploring the Data (Visualization Tools) - Pandas and Altair

- Import altair as at


## Types of Graphs

BOX PLOT

[![image](https://user-images.githubusercontent.com/57330752/234424387-446091c9-3cd4-4235-8fd3-1b48a8a2dd87.png)]

SCATTER PLOT
![image](https://user-images.githubusercontent.com/57330752/234424487-1e9fa4c3-470b-495b-af19-1f66a43799dd.png)


