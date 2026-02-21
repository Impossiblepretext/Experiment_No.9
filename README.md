# Experiment – 9
## Title
Implementation of Tools For Exploratory Data Analysis - Pandas
## Aim

To learn and implement the Pandas library in Python for performing data manipulation, cleaning, and analysis using its specialized data structures.

## Objectives

To understand the basic structure of Series and DataFrames

To explore different methods of loading data from various file formats

To perform data cleaning tasks such as handling missing values and duplicate records

To apply data selection, filtering, and conditional operations

To understand and implement the "Split-Apply-Combine" concept using GroupBy

To perform merging, joining, and concatenation of datasets

### Theory on Pandas

Pandas is an open-source Python library mainly used for data analysis and manipulation. The term Pandas comes from “Panel Data,” which refers to multidimensional data used in economics.

While NumPy mainly works with numerical arrays, Pandas is specially designed to handle tabular data like Excel sheets or SQL tables. It can manage different types of data across columns, which makes it very useful for real-world datasets.

## Core Data Structures
### Series

A Series is a one-dimensional labeled array that can store different types of data such as integers, strings, and floating-point numbers.
Each element in a Series has an index label associated with it.

### DataFrame

A DataFrame is a two-dimensional tabular structure with rows and columns.
It can store different data types in different columns and is the most widely used object in Pandas.

## Characteristics of Pandas
### Label-based Indexing

Unlike NumPy, which mainly uses position-based indexing, Pandas allows indexing using row and column labels. This makes accessing data more readable and user-friendly.

### Handling Missing Data

Pandas provides built-in functions to detect and manage missing values (NaN).
We can either remove these values or fill them using suitable techniques.

### Alignment

During arithmetic operations, Pandas automatically aligns data based on labels.
This reduces errors caused by mismatched indices.

### Time-Series Functionality

Pandas has powerful features for working with date and time data, such as generating date ranges and performing time-based calculations.

## Data Manipulation Theory
### Data Ingestion and Inspection

Pandas supports reading data from multiple file formats like CSV, Excel, JSON, and SQL databases.

It also provides useful functions to inspect datasets, check data types, memory usage, and view summary statistics such as mean, count, and standard deviation.

### Data Cleaning (Preprocessing Phase)

Data cleaning is a crucial part of Exploratory Data Analysis.

### Filtering

Selecting only the required rows based on logical conditions.

### Imputation

Replacing missing values with mean, median, or fixed values to maintain data consistency.

### Deduplication

Identifying and removing duplicate records to improve data quality.

### The GroupBy Mechanism

GroupBy is one of the most important features in Pandas.
It works in three main steps:

Splitting the data into groups based on certain criteria

Applying functions like sum, mean, or count to each group

Combining the results into a new structured output

This process is commonly known as the "Split-Apply-Combine" approach.

## Advanced Analytical Operations
### Hierarchical Indexing (Multi-Indexing)

Pandas allows the use of multiple index levels on rows or columns.
This helps in organizing and analyzing higher-dimensional data in a simplified format, such as grouping by Year and Quarter.

### Reshaping and Pivoting

Pandas provides functions like pivot and melt to restructure data.

It can convert data from:

Long format (better for storing data)

Wide format (better for displaying and reporting data)

## Merging and Joining

Pandas provides operations similar to SQL joins to combine datasets.

### Inner Join

Returns only the records that have matching values in both datasets.

### Left/Right Join

Returns all records from one dataset and matching records from the other dataset.

### Outer Join

Returns all records from both datasets wherever matches are found.

## Applications of Pandas

### Financial Analysis – Studying stock trends and calculating moving averages

### Machine Learning – Preparing and transforming raw data into model-ready format

### Healthcare Data – Managing and analyzing patient information

### Web Analytics – Examining user activity and website traffic patterns

## Conclusion

Pandas plays a major role in Exploratory Data Analysis.
It simplifies tasks such as cleaning, filtering, grouping, and combining data.

Due to its flexibility and powerful features, Pandas is widely used in data science and real-world industry applications.
