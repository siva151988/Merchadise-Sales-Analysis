# Merchadise-Sales-Analysis
### Merchandise Sales Analysis created using PowerBi

#### Project Objective
Lee Chatmen is a popular influencer from the United States with over 7 million TikTok followers. He became famous for his entertaining videos, where he plays popular songs on miniature guitars. In 2023, Lee launched his own line of merchandise. This analysis looks at how his merchandise sales are going and what we can learn from the data.

#### Dataset used

- <a href="https://github.com/siva151988/Merchadise-Sales-Analysis/blob/main/Onyx%20Data%20-DataDNA%20Dataset%20Challenge%20-%20Merchandise%20Sales%20Dataset%20-%20January%202025.xlsx">Merchandise Sales Data</a>

#### Questions (KPIs)
-	What are the overall sales trends?
-	Which product categories perform the best?
-	What are the most and least popular products?
-	How does location affect sales performance?
-	What impact does international shipping have on sales?
-	What is the demographic profile of buyers?
-	How do ratings and reviews correlate with sales?
-	What are the trends in shipping charges?
-	How do discounts or promotional pricing influence purchasing behavior?
-	Are there any patterns in repeat purchases?
-	Dashboard Interaction <a href="https://github.com/siva151988/Merchadise-Sales-Analysis/blob/main/Merchandise%20sales1.pbix">View Dashboard</a>

#### Process
- Verified and understood all fields including Order Date, Sales, Units Sold, Category, Region, etc.
- Cleaned column headers and removed unnecessary formatting in Power Query Editor.Converted data types for dates, numbers, and categories.Ensured column consistency (e.g., corrected nulls, checked date ranges).
- Created a **Date Table** to support time intelligence functions.
- Created a Tables to perform analysis and join those tables using snowflake modelling to build a realtionship between tables.
- Created DAX Calculations to perform KPI trends like **Total Sales**,**Net Profit**,**Total Quantity**,**Total Orders**,**Shipping Charges** etc..
- Added Interactive Features like Slicers,Drill Dowm capabilities, Dynamic titles and Tooltips.

#### Dashboard
![Merchandise sales screenshot1](https://github.com/user-attachments/assets/8a34330a-c6c2-47fc-a126-6815ca0e414f)

![Merchandise sales screenshot2](https://github.com/user-attachments/assets/f65021ab-bfcb-4672-ba7a-791f790118e0)

![Merchandise sales screenshot3](https://github.com/user-attachments/assets/79e47bad-5bcc-4da0-92c2-a740a510efab)

#### Project Insights
- The **monthly revenue trend** shows a steady decline from **$81K in May 2024 to $10K in November 2024**.While the total sales are significant ($856.46K), this downward trend may suggest seasonal effects or reduced marketing effectiveness in later months.
- **Clothing** is the top-performing category, contributing **74.4% of total revenue**.**Ornaments** follow at **18.1%**, and **Other products** account for only **7.41%.Customer** distribution also supports this: **50.09% of customers purchased Clothing**.
- Top products (by revenue and units sold):
  - Product ID **BF1548, BF1543, and BF1549** under the Clothing category each generated **over $140K in revenue**.
  - Products like **BF1555 and BF1553** (under "Other") generated **less than $10K**, indicating low customer interest.
- **Sydney ($48K)**, followed by **San Francisco ($41K)** and **New Jersey ($40K)**.Sales spread across **North America, Europe, Asia, and Australia**, as shown in the map visualization. Domestic vs. International sales split is nearly even:
    - International: $469.61K (54.83%)
    - Domestic: $386.86K (45.17%)
- International sales **outperform domestic**, with a **54.83% share**.
- The buyer demographic leans **young(25-30 yrs) and male (70%)**, typical for e-commerce retail in fashion categories.
- **5-Star** products generate **$259K**, while **4-Star** rated products closely follow at **$256K**.Poorly rated products (2-Star) contribute just **$59K**,highlighting a **positive correlation between rating and sales performance**.
- Customers are more concentrated in regions with lower or moderate shipping fees, possibly influencing purchase decisions.
- Drop in revenue toward year-end (despite steady orders) could imply price reductions or discounts.
- Same products **(e.g., BF1543, BF1548)** appear multiple times.Combined with high ratings and consistent demand, these are likely repeat purchases, especially in Clothing.

#### Final Outcome
The Merchandise Sales Dashboard effectively consolidates performance data across product, region, demographic, and rating dimensions. Key takeaways include:
- Clothing dominates sales, backed by high ratings and global demand.
- International shipping broadens reach, contributing more than 50% of revenue.
- Young male buyers (25–30) are the dominant demographic.
- Sales are positively influenced by higher ratings, repeat purchases, and accessible shipping.

This dashboard empowers stakeholders to make data-driven decisions on product strategy, customer targeting, and regional expansion, with clear opportunities for improving underperforming products and customer segments.




