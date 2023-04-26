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
- 


## Filtering Data

- only_movies = netflix[netflix['type'] == 'Movie'] - selects only the data that fits with the filter.


## Formulas

Recall - used to evaluate performance of a classification model:

- recall = true positives / (true positives + false negatives)

Precision - used to evaluate performance of a classification model:

- precision = true positives / (true positives + false positives)


## Exploring the Data (Visualization Tools) - Pandas and Altair

- Import altair as at - imports Altair as visual library.

# Create a simple bar chart
- alt.Chart(mpaa).mark_point().encode(
    x='rating',
    y='count(rating)'
) - uses mpaa as the data frame, 'rating' and 'count(rating)' are both attributes of the dataset, 

- You can also use .mark_bar() instead of mark_point()

## Types of Graphs

BOX PLOT

![image](https://user-images.githubusercontent.com/57330752/234424387-446091c9-3cd4-4235-8fd3-1b48a8a2dd87.png)
![image](https://user-images.githubusercontent.com/57330752/234429729-f3cac85a-e33a-402f-9b32-a7395be087e0.png)


SCATTER PLOT
![image](https://user-images.githubusercontent.com/57330752/234424487-1e9fa4c3-470b-495b-af19-1f66a43799dd.png)


SCATTER PLOT MATRIX
![image](https://user-images.githubusercontent.com/57330752/234429676-de6ce8a7-a44c-4195-b757-479d3c2d3cc5.png)


HISTOGRAM
![image](https://user-images.githubusercontent.com/57330752/234429760-23a41542-f32f-40b1-b681-2f702bbf09c9.png)


SMALL MULTIPLE BAR CHART
![image](https://user-images.githubusercontent.com/57330752/234429796-0b99f1ba-e500-473f-83e7-423cf05c8564.png)
