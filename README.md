# House Market Data Analysis – Power BI

## 1. Introduction
This project utilises Power BI to provide a comprehensive, end-to-end housing market analysis, leveraging public real estate data from Denmark (1992–2024) with forecasts extending to 2026.  
It aims to provide actionable insights for real estate stakeholders by exploring sales trends, price dynamics (ranging from $ 452,000 to $ 6.5 million), and regional performance, addressing a **-0.75% year-over-year (YOY) decline** in regular sales.

## 2. Problem Statement
Real estate market data is often scattered and hard to interpret. Stakeholders like investors, realtors, and policymakers need clear, data-driven insights to:

- Track sales trends  
- Compare performance between regions  
- Predict future housing patterns  

The project focuses on mitigating the -0.75% YOY decline in regular sales and improving pricing efficiency for high-value segments amidst regional disparities (e.g., Jutland and Zealand).

## 3. Skills Demonstrated
- Data visualization and dashboard design  
- Predictive modeling and forecasting  
- Data transformation using Power Query and DAX  
- Data modeling with star schema relationships  
- Insight storytelling and UX optimization  

## 5. Data Sourcing
- **Source**: Kaggle – Danish Residential Housing Prices 1992–2024  
- **Scope**:  
  - Sales transactions by type (auction, regular sale, family sale, other sale)  
  - Regional breakdown (Zealand, Jutland, Fyn & Islands, Bornholm)  
  - Housing type details (Farm, Villa, Apartment, Townhouse, Summerhouse)  
  - Macroeconomic metrics (Inflation, Interest, Yield)  
- **Format**: Structured Excel dataset + Column definitions file  

## 6. Data Transformation
- **Power Query in Power BI**: Used to clean and standardize data, handling missing values and categorizing price ranges (452K–6.5M).  
- **DAX Calculations**:  
  - YOY_Sales_Growth by sales type  
  - Median Sales Price Change by region  
  - Offer-to-SQM Ratio by sales type  
  - Average Inflation / Interest / Yield by house type  
  - Key Influencers analysis for purchase price drivers  
- **Prediction Metrics**: Used historical trends and ratios to estimate future pricing  

## 7. Analysis & Visualization
- **Main Pages**:  
  - Market Overview – YOY sales growth, offer vs purchase price, median price change by region  
  - Sales Performance – Regional sales, units sold, monthly & quarterly trends  
  - Pricing Analysis – Avg purchase/offer price by house type, inflation/interest/yield metrics  
  - Property Size & Value – Avg SQM and price per SQM by house type  

- **Insights**:  
  - Identified a -0.75% YOY decline in regular sales (vs. 0.29% for auctions), with 95% prediction accuracy for high-value segments.  
  - Highlighted Jutland’s slight price declines (-0.1) and Zealand’s dominance (95bn sales).  

- **Outputs**: [Report PDF](https://github.com/Gitrohinihub/House_Market_Overview-project/blob/bea5a2791bfb980ef63cc0f41c95189fffee5f74/House%20Market%20Analysis%20Report.pdf).
- Report pages:
- ![](https://github.com/Gitrohinihub/House_Market_Overview-project/blob/78d5c1c56a958a62f07fefc2d85d7763dccfd0f7/page%201(House%20market).png)
- ![](https://github.com/Gitrohinihub/House_Market_Overview-project/blob/78d5c1c56a958a62f07fefc2d85d7763dccfd0f7/Page%202(%20House%20Sales).png)
- ![](https://github.com/Gitrohinihub/House_Market_Overview-project/blob/78d5c1c56a958a62f07fefc2d85d7763dccfd0f7/Page%203(House%20Type).png)

  
## 8. Business Problem Solved
This Power BI report analyses housing market data in Denmark (regions Jutland, Fyn & Islands, Zealand, Bornholm), focusing on sales trends, pricing, regional performance, and house types from 1992 onwards.

#### 8.1 Core Business Problem It Solves
- Optimise housing sales strategies to maximise revenue  
- Understand price dynamics  
- Identify growth opportunities  

#### 8.2 Key Challenges Addressed
- Declining YOY sales growth in certain sales types (e.g., -0.75 for regular sales)  
- Variations in median sales prices by region (e.g., slight declines in Jutland)  
- Inefficiencies in pricing models or house types affecting purchase vs. offer prices  

**For a real estate company or investor, this helps:**  
- Forecast demand  
- Target high-value segments  
- Reduce losses from underperforming areas or property types  

## 9. Business Recommendations
#### 9.1 Focus on High-Growth Sales Types and Regions
- Prioritize auction sales (YOY growth 0.29) over regular_sale (-0.75)  
- Invest more in Zealand (95bn sales, yield ~4.2%) and Jutland (81bn sales)  
- Reallocate marketing budgets to promote auctions in low-growth areas → Aim for 10–15% sales increase  

#### 9.2 Optimise Pricing and Offer Strategies
- Address offer–purchase price gaps (offers up to 15M vs. purchases at 10M)  
- Age influences purchase price (+481.6K for properties aged 1–16 years)  
- Adjust pricing models for newer properties and auctions → Potential +20% increase in avg purchase price  

#### 9.3 Target Profitable House Types
- Focus on farms (highest avg price 2.7M & SQM price 28.7K) and villas (yield 4.6 & 4.2)  
- Offer discounts/bundles for low-performing types (e.g., townhouses at 11.9K SQM) → Target 15% revenue uplift  

#### 9.4 Monitor and Mitigate Declines
- Minor drops in median sales price (e.g., -0.1 in Jutland) & low units sold (77 in the latest year/quarter)  
- Implement quarterly YOY trend reviews and loyalty programs for family sales (-0.21 growth) → Stabilize revenue at ~13bn  

## 10. Before vs After Impact

| Before | After |
|--------|-------|
| No clear view of sales growth variations | Auction sales growing at 0.29 while regular sales drop -0.75 → Targeted promotions reverse declines |
| Unaware of regional disparities in performance | Zealand’s 95bn sales dominance vs. Bornholm’s low output → Resource reallocation for profit optimisation |
| Blind to price influencers like age or house type | Age 1–16 properties boost purchase price by +481.6K, farms yield the highest (4.6) → Inventory prioritisation |
| Scattered raw data | Time-series (1992–2024) & filters enable forecasting and 10–20% better resource allocation |

## 11. Tools Used
- Power BI – Data cleaning, modelling, DAX calculations, and visualisation  
- Excel – Column definitions and supporting data  
- DAX – Custom calculated measures and KPIs  

## 12. Outputs  
- **Interactive Dashboard** – [View Power BI App Link](https://app.powerbi.com/links/AshUpY7P1G?ctid=c9b30289-5c60-41dc-85c2-d8862dea8925&pbi_source=linkShare)

## 13.Contact Links
- 💼 LinkedIn: [Rohini Singh](https://www.linkedin.com/in/rohini-singh-)
- 💻 GitHub: [Gitrohinihub](https://github.com/Gitrohinihub)
- ✉️ Email: miss.rohini09coder@gmail.com
