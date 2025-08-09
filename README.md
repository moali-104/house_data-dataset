O<!DOCTYPE html>
<html>
<head>
<title>Online Shopping Dataset Analysis</title>
</head>
<body>

<h1>Online Shopping Dataset Analysis</h1>

<p>This project analyzes an online shopping dataset to gain insights into customer behavior, product trends, and sales performance.</p>

<h2>Notebook Contents</h2>

<p>The analysis is performed in a Jupyter Notebook and covers the following tasks:</p>

<h3>Task 1: Data Exploration</h3>
<ul>
  <li>Display the first 5 rows of the DataFrame.</li>
  <li>Display the column names and data types in the DataFrame.</li>
  <li>Show the summary statistics (mean, median, min, max, etc.) for numerical columns.</li>
</ul>

<h3>Task 2: Data Manipulation</h3>
<ul>
  <li>Add a new column 'Total' that contains the sum of 'Avg_Price' and 'Delivery_Charges'.</li>
  <li>Filter the DataFrame to show rows where 'Total' > 120.</li>
  <li>Sort the DataFrame based on 'CustomerID' in ascending order.</li>
</ul>

<h3>Task 3: Data Analysis</h3>
<ul>
  <li>Calculate the average value of the 'Total' column.</li>
  <li>Find the most frequent value in the 'Gender' column.</li>
  <li>Group the data by 'Delivery_Charges' and calculate the mean for each group.</li>
</ul>

<h3>Task 4: Data Visualization</h3>
<ul>
  <li>Create a histogram to visualize the distribution of a numerical column (This step is planned but not yet implemented).</li>
  <li>Generate a bar chart to represent the frequency of categories in the 'Location' column.</li>
</ul>

<h3>Task 5: Data Cleaning</h3>
<ul>
  <li>Perform data imputation to handle missing values in the DataFrame by dropping rows with missing values.</li>
</ul>

<h2>Getting Started</h2>

<p>To run this notebook, you will need to have Python and the following libraries installed:</p>

<ul>
  <li>pandas</li>
  <li>matplotlib</li>
  <li>numpy</li>
</ul>

<p>You can install these libraries using pip:</p>

<pre><code>pip install pandas matplotlib numpy</code></pre>

</body>
</html>
