# Quantium-Virtual-Internship-Retail-Strategy-and-Analytics-Task-1
Overview
This project simulates a real-world data analytics task from Quantium, focusing on the retail chips category.
The goal is to analyze transactional and customer data, uncover actionable insights on purchasing behavior, and recommend strategies to the Category Manager.

Project Summary
Objective: Analyze supermarket transaction and customer data to identify chip buying patterns and deliver data-driven recommendations to improve category performance.
Role: Data Analyst / Commercial Analyst (Simulated via Forage’s Quantium internship).

Data Sources
Transactions: QVI_transaction_data.xlsx
Contains every chip purchase: transaction date, product, quantity, and sales value.
Customers: QVI_purchase_behaviour.csv
Maps loyalty card numbers to life stage and affluence segment.

Business Questions
Who buys chips? (Which life stages and affluence segments drive sales?)
What products are most popular? (Brands, pack sizes)
What is the average basket size and spend?
Are there outliers or anomalies that skew the data?
How do customer segments differ in purchase behavior?
What actionable commercial opportunities exist for category growth?

Analysis Workflow
1. Data Preparation & Cleaning
Inspected data for completeness and correct types.
Converted date fields to datetime.
Identified and removed outlier transactions (e.g., bulk purchases of 200+ packs).
Filtered to chips-only products.

2. Feature Engineering
Extracted PACK_SIZE (grams) from product names.
Extracted BRAND from product names and standardized brand naming.
Merged transactions with customer segments.

3. Exploratory Analysis
Summary statistics for sales, quantity, frequency.
Visualized daily sales trends, highlighted holiday effects (e.g., December dip).
Uncovered missing data patterns (e.g., Christmas store closures).

4. Segmentation & Visualization
Proportional stacked bar and sunburst plots of sales and customer mix by life stage & affluence.
Average units and price per unit by segment.
Affinity analysis for brand and pack size by target segments.

5. Statistical Analysis
t-test to confirm if Mainstream young/midage singles/couples pay significantly more per packet.

Key Insights & Visualizations
Sales are concentrated:
Budget Older Families, Mainstream Young Singles/Couples, and Mainstream Retirees drive most sales.

Product preferences:
Most purchases are for standard-size packets (e.g., 150g–175g). KETTLE and DORITOS are the top brands.

Holiday effect:
Clear December sales spike and dip, aligning with seasonal promotions and store closures.

Segment differences:
Families buy more chips per customer. Mainstream young singles/couples are willing to pay higher prices per unit.

Brand affinity:
Mainstream young singles/couples are 23% more likely to buy Tyrrells and large packs (270g), highlighting cross-promotion opportunities.

Technical Skills Demonstrated
Data wrangling: Pandas, Numpy, handling missing values, merging datasets
Feature engineering: Regex-based extraction, data normalization
Visualization: Matplotlib, Seaborn, Plotly (interactive & static plots)
Statistical testing: t-test (scipy, statsmodels)
Storytelling: Clear comments and commercial translation of analysis
Python best practices: Clean, modular, well-annotated code

Recommendations
Promote key brands (Tyrrells, Twisties, Kettle) and larger pack sizes in locations frequented by young singles/couples and families.
Leverage sales spikes with targeted campaigns before holiday periods.
Monitor and continue refining category strategy based on ongoing transactional data.
Segmented marketing: Use customer segmentation to tailor promotions by affluence and life stage.

How to Run
Download the datasets from the Quantium Forage internship portal.
Run Task1_quantium_retail_analysis.ipynb in Jupyter Notebook or VSCode.
All code and outputs are self-contained; update data paths as needed.
Visualizations can be exported as PNG/HTML for presentations.

About Quantium Virtual Internship
This project was completed as part of the Quantium Data Analytics Virtual Internship (Forage, May 2025),
designed to give early-career analysts real-world experience with business data science in a commercial context.

Note: This program is a simulation and not an offer of employment by Quantium.

Contact
For questions or collaborations, reach out via www.linkedin.com/in/chinelo-nweke  or GitHub Issues.
