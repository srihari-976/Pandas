# Pandas Functions Guide

## Reading Data

- **pd.read_csv()**: Used to read a comma-separated values (CSV) file into a DataFrame.
    ```bash
    pd.read_csv()
    ```
- **pd.read_excel()**: Used to read an Excel file into a DataFrame.
    ```bash
    pd.read_excel()
    ```
- **pd.read_json()**: Used to read a JSON file into a DataFrame.
    ```bash
    pd.read_json()
    ```

## Data Exploration

- **df.head()**: Returns the first n rows of a DataFrame.
    ```bash
    df.head()
    ```
- **df.info()**: Provides a concise summary of a DataFrame.
    ```bash
    df.info()
    ```
- **df.describe()**: Generates descriptive statistics.
    ```bash
    df.describe()
    ```
- **df.shape**: Returns the dimensions of the DataFrame.
    ```bash
    df.shape
    ```
- **df.columns**: Returns the column labels of the DataFrame.
    ```bash
    df.columns
    ```

## Data Cleaning

- **df.dropna()**: Removes missing values.
    ```bash
    df.dropna()
    ```
- **df.fillna()**: Fills NA/NaN values using the specified method.
    ```bash
    df.fillna()
    ```
- **df.drop()**: Removes specified labels from rows or columns.
    ```bash
    df.drop()
    ```
- **df.rename()**: Renames the labels of rows or columns.
    ```bash
    df.rename()
    ```

## Data Manipulation

- **df.groupby()**: Groups the DataFrame using a mapper or by a Series of columns.
    ```bash
    df.groupby()
    ```
- **df.merge()**: Merges DataFrame or named Series objects with a database-style join.
    ```bash
    df.merge()
    ```
- **df.sort_values()**: Sorts by the values along either axis.
    ```bash
    df.sort_values()
    ```
- **df.apply()**: Applies a function along an axis of the DataFrame.
    ```bash
    df.apply()
    ```
- **df.map()**: Maps values of Series according to the input correspondence.
    ```bash
    df.map()
    ```

## Data Analysis

- **df.mean()**: Returns the mean of the values over the requested axis.
    ```bash
    df.mean()
    ```
- **df.median()**: Returns the median of the values over the requested axis.
    ```bash
    df.median()
    ```
- **df.std()**: Returns the standard deviation of the values over the requested axis.
    ```bash
    df.std()
    ```
- **df.corr()**: Computes pairwise correlation of columns.
    ```bash
    df.corr()
    ```

## Data Visualization

- **df.plot()**: Plots data.
    ```bash
    df.plot()
    ```
- **df.hist()**: Draws a histogram of the DataFrame’s columns.
    ```bash
    df.hist()
    ```
- **df.boxplot()**: Draws a box plot of the DataFrame’s columns.
    ```bash
    df.boxplot()
    ```
- **df.scatter()**: Generates a scatter plot.
    ```bash
    df.scatter()
    ```

## Advanced Functions

- **df.pivot_table()**: Creates a pivot table.
    ```bash
    df.pivot_table()
    ```
- **df.crosstab()**: Computes a simple cross-tabulation of two (or more) factors.
    ```bash
    df.crosstab()
    ```
- **pd.concat()**: Concatenates pandas objects along a particular axis.
    ```bash
    pd.concat()
    ```

- **pd.merge()**: Merges DataFrame or named Series objects with a database-style join.
    ```bash
    pd.merge()
    ```

- **df.isnull()**: Detects missing values.
    ```bash
    df.isnull()
    ```

- **df.notnull()**: Detects non-missing values.
    ```bash
    df.notnull()
    ```

