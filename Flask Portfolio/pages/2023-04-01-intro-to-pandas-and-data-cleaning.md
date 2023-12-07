title: Data Cleaning with Pandas
date: 2023-04-01
description: A beginner's guide to understanding Pandas DataFrames and basic data cleaning techniques in data science.

# Introduction to Pandas DataFrames and Data Cleaning

Pandas is a foundational library in Python for data analysis and manipulation. In this post, we'll cover the basics of Pandas DataFrames and some common data cleaning methods.

## What is a Pandas DataFrame?

A DataFrame is a two-dimensional, size-mutable, and potentially heterogeneous tabular data structure with labeled axes (rows and columns). It's one of the most commonly used Pandas objects.

### Creating a DataFrame

Here's how to create a simple DataFrame:

```python
import pandas as pd

data = {
    'Name': ['Anna', 'Bob', 'Catherine'],
    'Age': [28, 34, 29],
    'City': ['New York', 'Los Angeles', 'Chicago']
}
df = pd.DataFrame(data)
print(df)
