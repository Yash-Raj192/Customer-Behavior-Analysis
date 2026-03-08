<h1 align="center">Customer Shopping Behavior Analysis</h1>

<p align="center">
<img src="https://img.shields.io/badge/Python-3.x-blue">
<img src="https://img.shields.io/badge/SQL-PostgreSQL-green">
<img src="https://img.shields.io/badge/Visualization-PowerBI-yellow">
<img src="https://img.shields.io/badge/Project-Data%20Analytics-success">
</p>

<hr>

<h2>Project Overview</h2>

<p>
This project analyzes <b>customer shopping behavior</b> using transactional data to uncover insights
about purchasing patterns, product performance, customer segments, and the impact of discounts
and subscriptions.
</p>

<p>The project demonstrates a complete data analytics workflow including:</p>

<ul>
<li>Data Cleaning & Preprocessing using <b>Python</b></li>
<li>Business Analysis using <b>SQL</b></li>
<li>Data Visualization using <b>Power BI</b></li>
</ul>

<hr>

<h2 align="center">Dashboard Preview</h2>

<p align="center">
<img src="Dashboard Image.png" width="900">
</p>

<hr>

<h2>Business Problem</h2>

<p>
Retail companies generate large volumes of transaction data through online and offline
shopping platforms. However, many organizations struggle to extract meaningful insights
from this data.
</p>

<p>This project aims to:</p>

<ul>
<li>Identify customer spending patterns</li>
<li>Understand customer segments</li>
<li>Analyze impact of discounts and subscriptions</li>
<li>Identify top performing products</li>
<li>Provide actionable business insights</li>
</ul>

<hr>

<h2>Dataset Information</h2>

<table>
<tr>
<th>Feature</th>
<th>Value</th>
</tr>

<tr>
<td>Total Rows</td>
<td>3900</td>
</tr>

<tr>
<td>Total Columns</td>
<td>18</td>
</tr>

<tr>
<td>Missing Values</td>
<td>37 (Review Rating)</td>
</tr>
</table>

<br>

<h3>Key Attributes</h3>

<b>Customer Information</b>
<ul>
<li>Age</li>
<li>Gender</li>
<li>Location</li>
<li>Subscription Status</li>
</ul>

<b>Purchase Information</b>
<ul>
<li>Item Purchased</li>
<li>Category</li>
<li>Purchase Amount</li>
<li>Season</li>
<li>Size</li>
<li>Color</li>
</ul>

<b>Shopping Behavior</b>
<ul>
<li>Discount Applied</li>
<li>Promo Code Used</li>
<li>Previous Purchases</li>
<li>Frequency of Purchases</li>
<li>Review Rating</li>
<li>Shipping Type</li>
</ul>

<hr>

<h2>Project Workflow</h2>

<h3>1. Data Cleaning & Preparation (Python)</h3>

<ul>
<li>Loaded dataset using <b>Pandas</b></li>
<li>Data exploration using <code>info()</code> and <code>describe()</code></li>
<li>Handled missing values</li>
<li>Renamed columns to <b>snake_case</b></li>
<li>Created new features: <code>age_group</code> and <code>purchase_frequency_days</code></li>
<li>Loaded cleaned dataset into <b>PostgreSQL</b></li>
</ul>

<h3>Libraries Used</h3>

<ul>
<li>Pandas</li>
<li>NumPy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
<li>Psycopg2</li>
</ul>

<hr>

<h2>SQL Analysis</h2>

<p>Business questions answered using SQL:</p>

<ul>
<li>Revenue by gender</li>
<li>Customers using discounts but spending above average</li>
<li>Top 5 highest rated products</li>
<li>Average purchase amount by shipping type</li>
<li>Subscribers vs non subscribers spending behavior</li>
<li>Products with highest discount usage</li>
<li>Customer segmentation</li>
<li>Top 3 products per category</li>
<li>Repeat buyers and subscription relationship</li>
<li>Revenue contribution by age group</li>
</ul>

<p>All SQL queries are available in:</p>

<pre>
customer_behavior_sql_queries.sql
</pre>

<hr>

<h2>Power BI Dashboard</h2>

<table>
<tr>
<th>Metric</th>
<th>Value</th>
</tr>

<tr>
<td>Total Customers</td>
<td>3.9K</td>
</tr>

<tr>
<td>Average Purchase Amount</td>
<td>$59.76</td>
</tr>

<tr>
<td>Average Review Rating</td>
<td>3.75</td>
</tr>
</table>

<br>

<b>Dashboard Visualizations</b>

<ul>
<li>Revenue by Category</li>
<li>Sales by Category</li>
<li>Customer Distribution by Subscription Status</li>
<li>Revenue by Age Group</li>
<li>Sales by Age Group</li>
</ul>

<hr>

<h2>Key Insights</h2>

<ul>
<li>Majority of customers are non subscribers</li>
<li>Loyal customers represent a large portion of buyers</li>
<li>Customers using Express shipping spend more</li>
<li>Discounts significantly influence purchasing behavior</li>
</ul>

<hr>

<h2>Business Recommendations</h2>

<ul>
<li><b>Boost Subscriptions</b> by offering exclusive benefits</li>
<li><b>Loyalty Programs</b> to reward repeat customers</li>
<li><b>Product Positioning</b> highlighting top rated products</li>
<li><b>Targeted Marketing</b> for high value customer segments</li>
</ul>

<hr>

<h2>Project Files</h2>

<table>

<tr>
<th>File</th>
<th>Description</th>
</tr>

<tr>
<td>Customer_Shopping_Behavior_Analysis.ipynb</td>
<td>Data cleaning and analysis using Python</td>
</tr>

<tr>
<td>customer_behavior_sql_queries.sql</td>
<td>SQL queries for business insights</td>
</tr>

<tr>
<td>customer_behavior_dashboard.pbix</td>
<td>Power BI dashboard</td>
</tr>

<tr>
<td>customer_shopping_behavior.csv</td>
<td>Dataset</td>
</tr>

<tr>
<td>Customer-Shopping-Behavior-Analysis.pptx</td>
<td>Project presentation</td>
</tr>

<tr>
<td>Customer Shopping Behavior Analysis.pdf</td>
<td>Project report</td>
</tr>

</table>

<hr>

<h2>Tools & Technologies</h2>

<table>

<tr>
<th>Tool</th>
<th>Purpose</th>
</tr>

<tr>
<td>Python</td>
<td>Data preprocessing</td>
</tr>

<tr>
<td>SQL</td>
<td>Data analysis</td>
</tr>

<tr>
<td>PostgreSQL</td>
<td>Database management</td>
</tr>

<tr>
<td>Power BI</td>
<td>Visualization</td>
</tr>

<tr>
<td>Jupyter Notebook</td>
<td>Analysis environment</td>
</tr>

</table>

<hr>

<h2>Author</h2>

<p>
<b>Yash Raj Singh</b><br>
B.Tech CSE – BIT Mesra<br>
</p>
