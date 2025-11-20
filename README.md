Python DA Assignment 1 – Data Analysis using NumPy and Pandas

This repository contains solutions and practice exercises for Python Data Analysis – Assignment 1, focusing on NumPy, Pandas Series, and Pandas DataFrames.
The objective of the assignment is to understand array operations, data manipulation, slicing, indexing, and basic exploratory data analysis.

📌 1. NumPy Array Operations
Problem Statement

Analyze daily temperature data recorded over two weeks using NumPy. Perform array creation, inspection, mathematical computations, and slicing.

✔️ Tasks Covered
1. Creating a 1D NumPy Array

Created an array temperatures_w1 with:

[22.5, 25.3, 20.8, 23.4, 26.1, 24.8, 21.9]

2. Inspection and Properties

Checked:

Shape

Data type

Number of elements

3. Array Operations

Converted Celsius temperatures to Fahrenheit.

Calculated:

Maximum temperature

Minimum temperature

Mean temperature

4. Array Slicing

Extracted:

First 3 days

Weekend temperatures

Middle 3 days

5. Creating a 2D NumPy Array

Two-week temperature data:

Week 1: [22.5, 25.3, 20.8, 23.4, 26.1, 24.8, 21.9]

Week 2: [19.2, 22.5, 21.3, 24.0, 23.5, 22.8, 20.1]

6. 2D Array Inspection and Slicing

Checked shape, datatype, and total elements.

Extracted per-week data and weekend temperatures for both weeks.

📌 2. Pandas Series Operations
✔️ Tasks Covered
1. Creating a Pandas Series

Series marks with:

Values: 95, 92, 89, 85, 80

Indices: 'Rank1', 'Rank2', 'Rank3', 'Rank4', 'Rank5'

2. Indexing & Slicing

Accessed marks using:

Integer index

loc for top 3 ranks

iloc for 3rd rank

Used boolean masking to filter marks > 90.

3. Manipulating the Series

Updated:

Rank1 → 100

Removed last rank

Converted all marks to CGPA by dividing by 10.

📌 3. Pandas DataFrame Operations
✔️ 1. Creating the DataFrame

A transactions DataFrame including:

TransactionID

ProductCategory

Region

Amount

(10 sample records)

✔️ 2. Data Exploration

Displayed DataFrame, head, tail, shape, column names, data types

Selected specific columns

Retrieved last 3 columns using iloc

Filtered rows (Region = "North" & Amount > 200)

Calculated:

Value counts of ProductCategory

Unique values in Region

Mean amount grouped by Region

✔️ 3. DataFrame Manipulation

Modified Amount for TransactionID 102 → 165

Added a new column Discount (10% of Amount)

Removed row with TransactionID 109

Deleted the Discount column

📁 Contents of This Repository

Jupyter Notebook / Python Scripts implementing all tasks

Clean, well-commented code for learning and reference

🚀 Skills Demonstrated

NumPy array creation & manipulation

Pandas Series indexing & filtering

DataFrame operations & EDA

Slicing, grouping, and data transformation
