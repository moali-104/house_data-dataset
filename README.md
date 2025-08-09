Online Shopping Dataset Analysis
This project analyzes an online shopping dataset to gain insights into customer behavior, product trends, and sales performance.

Notebook Contents
The analysis is performed in a Jupyter Notebook and covers the following tasks:

Task 1: Data Exploration
Display the first 5 rows of the DataFrame.
Display the column names and data types in the DataFrame.
Show the summary statistics (mean, median, min, max, etc.) for numerical columns.
Task 2: Data Manipulation
Add a new column 'Total' that contains the sum of 'Avg_Price' and 'Delivery_Charges'.
Filter the DataFrame to show rows where 'Total' > 120.
Sort the DataFrame based on 'CustomerID' in ascending order.
Task 3: Data Analysis
Calculate the average value of the 'Total' column.
Find the most frequent value in the 'Gender' column.
Group the data by 'Delivery_Charges' and calculate the mean for each group.
Task 4: Data Visualization
Create a histogram to visualize the distribution of a numerical column (This step is planned but not yet implemented).
Generate a bar chart to represent the frequency of categories in the 'Location' column.
Task 5: Data Cleaning
Perform data imputation to handle missing values in the DataFrame by dropping rows with missing values.
Getting Started
To run this notebook, you will need to have Python and the following libraries installed:

pandas
matplotlib
numpy
You can install these libraries using pip:

