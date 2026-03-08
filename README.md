<body>

<header>
<h1>Customer Shopping Behavior Analysis</h1>

<div class="badges">
<img src="https://img.shields.io/badge/Python-3.x-blue">
<img src="https://img.shields.io/badge/SQL-PostgreSQL-green">
<img src="https://img.shields.io/badge/Visualization-PowerBI-yellow">
<img src="https://img.shields.io/badge/Project-Completed-success">
</div>

</header>


<div class="container">


<div class="section">
<h2>Project Overview</h2>

<p>
This project analyzes customer shopping behavior using transactional data to uncover insights
about purchasing patterns, product performance, customer segments, and the impact of
discounts and subscriptions.
</p>

<p>
The project demonstrates a complete data analytics workflow including:
</p>

<ul>
<li>Data Cleaning & Preprocessing using <b>Python</b></li>
<li>Business Analysis using <b>SQL</b></li>
<li>Data Visualization using <b>Power BI</b></li>
</ul>

</div>


<div class="section dashboard">

<h2>Dashboard Preview</h2>

<img src="Dashboard Image.png" alt="Customer Behavior Dashboard">

</div>



<div class="section">

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

</div>



<div class="section">

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

<b>Key Attributes</b>

<ul>

<li><b>Customer Information</b>
<ul>
<li>Age</li>
<li>Gender</li>
<li>Location</li>
<li>Subscription Status</li>
</ul>
</li>

<li><b>Purchase Information</b>
<ul>
<li>Item Purchased</li>
<li>Category</li>
<li>Purchase Amount</li>
<li>Season</li>
<li>Size</li>
<li>Color</li>
</ul>
</li>

<li><b>Shopping Behavior</b>
<ul>
<li>Discount Applied</li>
<li>Promo Code Used</li>
<li>Previous Purchases</li>
<li>Frequency of Purchases</li>
<li>Review Rating</li>
<li>Shipping Type</li>
</ul>
</li>

</ul>

</div>



<div class="section">

<h2>Project Workflow</h2>

<h3>1. Data Cleaning & Preparation (Python)</h3>

<ul>
<li>Loaded dataset using Pandas</li>
<li>Data exploration using info() and describe()</li>
<li>Handled missing values</li>
<li>Renamed columns to snake_case</li>
<li>Created new features: age_group and purchase_frequency_days</li>
<li>Loaded cleaned data into PostgreSQL</li>
</ul>

<h3>Libraries Used</h3>

<ul>
<li>Pandas</li>
<li>NumPy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
<li>Psycopg2</li>
</ul>

</div>



<div class="section">

<h2>SQL Analysis</h2>

<p>Business questions answered using SQL:</p>

<ul>
<li>Revenue by gender</li>
<li>Customers using discounts but spending above average</li>
<li>Top 5 highest rated products</li>
<li>Average purchase amount by shipping type</li>
<li>Subscribers vs non subscribers spending</li>
<li>Products with highest discount usage</li>
<li>Customer segmentation</li>
<li>Top 3 products per category</li>
<li>Repeat buyers and subscription relationship</li>
<li>Revenue contribution by age group</li>
</ul>

</div>



<div class="section">

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
<li>Customer Distribution by Subscription</li>
<li>Revenue by Age Group</li>
<li>Sales by Age Group</li>
</ul>

</div>



<div class="section">

<h2>Key Insights</h2>

<ul>
<li>Majority of customers are non subscribers</li>
<li>Loyal customers represent a large portion of buyers</li>
<li>Express shipping customers spend more on average</li>
<li>Discounts strongly influence purchasing behavior</li>
</ul>

</div>



<div class="section">

<h2>Business Recommendations</h2>

<ul>
<li><b>Boost Subscriptions</b> by offering exclusive benefits</li>
<li><b>Loyalty Programs</b> to reward repeat customers</li>
<li><b>Product Positioning</b> highlighting top rated products</li>
<li><b>Targeted Marketing</b> towards high value customer segments</li>
</ul>

</div>



<div class="section">

<h2>Tools & Technologies</h2>

<table>

<tr>
<th>Tool</th>
<th>Purpose</th>
</tr>

<tr>
<td>Python</td>
<td>Data cleaning and preprocessing</td>
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
<td>Data visualization</td>
</tr>

<tr>
<td>Jupyter Notebook</td>
<td>Analysis environment</td>
</tr>

</table>

</div>



</div>


<footer>

<p>Author: <b>Yash Raj Singh</b></p>
<p>BIT Mesra | CSE</p>
<p>Email: btech60136@bitmesra.ac.in</p>

</footer>


</body>
</html>
