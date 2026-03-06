# Shark-Tank-Investment-Analysis
An end-to-end data analytics project examining the investment patterns and startup ecosystem of Shark Tank India. This project transforms raw, unstructured pitch data into a high-impact Power BI dashboard to uncover which industries dominate the "Tank" and how the Sharks distribute their capital.

🛠️ Data Cleaning & Transformation:
The raw dataset required extensive cleaning in Excel and Python to ensure KPI accuracy:
1) Standardization: Cleaned Startup Names to remove duplicates and filled in missing names for data completeness.
2) Revenue Synchronization: Fixed discrepancies between Monthly and Annual Revenue by using a 12x multiplier to fill gaps and ensure financial consistency.
3) Unpivoting Data: Transformed Shark-specific investment and equity columns into a "Long" format, allowing for dynamic filtering by individual Shark.
4) Unit Normalization: Standardized all currency values (Lakhs and Crores) into a single numeric scale for accurate total investment calculations (1.09{bn}).

🐍 Python EDA Highlights:
Before building the dashboard, I performed a deep dive using Python (Pandas & Seaborn):
1) Duplicate Management: Identified and dropped duplicate entries to prevent skewed totals.
2) Feature Engineering: Extracted insights into the "Pitch-to-Investment" ratio across different seasons.
3) Data Validation: Verified the integrity of the total deals (175) against individual Shark investment records.

💡 Key Insights:
1) Industry Dominance: The Food industry is the clear leader, capturing over 22% of the total investment share.
2) Seasonality Trends: Season 2 saw a significant spike in total deal volume compared to Season 1, indicating a maturing startup market.
3) Equity Metrics: Despite high-stakes negotiations, the average equity stake across all successful deals remains a lean 5.08%.
4) Niche Interests: While Food is #1, Beauty/Fashion and Manufacturing emerged as the most active secondary sectors.

🧰 Tech Stack:
Data Cleaning: Microsoft Excel
Exploratory Data Analysis: Python (Pandas, Matplotlib, Seaborn)
Visualization: Power BI (DAX, Interactive Filtering)

Link to live interactive dashboard - https://app.powerbi.com/groups/me/reports/2a094edb-22af-4e18-bef9-afd02c31b411/9bead53f6e00ccebdcad?experience=power-bi
