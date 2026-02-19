# SQL_Python_Project

<h3><b>E-Commerce Sales Analysis Project</b></h3>
<b>Project Overview</b>

This project focuses on performing end-to-end data analysis on an e-commerce transactional dataset to extract business insights, validate results across SQL and Python, and generate strategic recommendations.

The project is structured into three levels of analysis:

- Basic Analysis
- Intermediate Analysis 
- Advanced Analytical Insights
The objective was to transform raw transactional data into actionable business intelligence.

<b>Business Objectives</b>
- Basic Level
  - Identify customer distribution across cities and states
  - Calculate total orders and revenue
  - Analyze sales by category
  - Understand payment patterns

- Intermediate Level
  - Monthly and yearly order trends
  - Revenue contribution by category
  - Seller performance analysis
  - Price vs demand correlation

- Advanced Level
  - Moving averages of customer spending
  - Cumulative sales trends
  - Year-over-Year growth rate
  - Customer retention rate (6 months)
  - Top customers per year using window functions

- Tools & Technologies Used
  - SQL (MySQL):	Data extraction, joins, aggregations, window functions
  - Python (Pandas, NumPy):	Data manipulation and validation

<b>Data Analysis Approach</b>

- Data Exploration
  - Checked table relationships and foreign keys
  - Verified column consistency

- Data Cleaning
  - Handled null values
  - Ensured correct joins
  - Removed duplicate aggregations

- Feature Engineering
  - Extracted year and month from timestamps
  - Created revenue and ranking metrics

- Validation
  - Cross-validated SQL and Python outputs
  - Ensured identical results across both platforms

<b>Challenges Faced</b>

- Incorrect Join Conditions
  Initially faced null revenue due to wrong table joins.
    Solved by carefully verifying foreign key relationships.

- Data Duplication After Merges
  Multiple joins caused row duplication which inflated revenue calculations.
  Fixed by rebuilding the dataset pipeline exactly matching SQL logic.

- Window Function Alignment
  Ensured proper matching between:
  - SQL RANK / DENSE_RANK
  - Pandas rank(method='dense')

- Retention Calculation Complexity
  Dataset used different customer identifiers.
  Used correct unique customer ID to accurately compute retention.

<b>Key Insights</b>
- Revenue shows steady year-over-year growth
- Few product categories contribute majority of revenue
- Seller revenue distribution is highly skewed
- Customer retention rate indicates scope for loyalty programs
- Top 3 customers significantly impact yearly revenue
- Certain cities dominate total order volume

<b>Business Recommendations</b>
- Focus marketing on high-revenue categories
- Launch loyalty programs to improve retention
- Provide incentives to top-performing sellers
- Expand operations in high-performing states
- Analyze low-performing categories for optimization

<b>Strategic Value of This Project</b>
This project demonstrates:
- Strong SQL fundamentals
- Advanced window function usage
- Python validation capability
- Analytical thinking
- Business-oriented interpretation of data
It reflects real-world data analyst problem-solving skills.

<b>Conclusion</b>
This project successfully transformed raw transactional data into meaningful insights through structured analysis and cross-platform validation.
By combining SQL and Python, the analysis ensures both computational accuracy and business relevance, making it suitable for production-level analytics and strategic decision-making.
