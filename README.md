🏠 End-to-End Housing Market Data Analysis – Power BI

📌 Project Overview
This project delivers a complete **end-to-end housing market analysis** using **public real estate data from Denmark**.  
The goal was to:
- **Analyze market trends** over time
- **Compare regional housing performance**
- **Predict housing metrics** using historical and calculated measures

The final output includes:
- A fully interactive **Power BI dashboard**
- A detailed PDF report for static viewing

---

🧠 Problem Statement
Real estate market data is often scattered and hard to interpret.  
Stakeholders like investors, realtors, and policymakers need **clear, data-driven insights** to:
- Track sales trends
- Compare performance between regions
- Predict future housing patterns

---

🗂️ Dataset Details
- **Source**: [Kaggle – Danish Residential Housing Prices 1992–2024](https://www.kaggle.com/datasets/martinfrederiksen/danish-residential-housing-prices-1992-2024/data)  
- **Scope**:
  - Sales transactions by type (auction, regular sale, family sale, other sale)
  - Regional breakdown (Zealand, Jutland, Fyn & Islands, Bornholm)
  - Housing type details (Farm, Villa, Apartment, Townhouse, Summerhouse)
  - Macroeconomic metrics (Inflation, Interest, Yield)
- **Format**: Structured Excel dataset + Column definitions file

---

🧮 Power BI & DAX Work Performed
- **Data Cleaning**: Performed entirely in Power BI Power Query
- **Data Modelling**: Relationships built between sales, region, house type, and macroeconomic data
- **Calculated Measures (DAX)**:
  - **YOY_Sales_Growth** by sales type
  - **Median Sales Price Change** by region
  - **Offer-to-SQM Ratio** by sales type
  - **Average Inflation / Interest / Yield** by house type
  - **Key Influencers** analysis for purchase price drivers
- **Prediction Metrics**: Used historical trends and ratios to estimate future pricing

---

📊 Dashboards
**Main Pages**:
1. **Market Overview** – YOY sales growth, offer vs purchase price, median price change by region
2. **Sales Performance** – Regional sales, units sold, monthly & quarterly trends
3. **Pricing Analysis** – Avg purchase/offer price by house type, inflation/interest/yield metrics
4. **Property Size & Value** – Avg SQM and price per SQM by house type
5. **Key Influencers** – Factors driving purchase price

---

💼 Business Problem Solved
This Power BI report analyses housing market data in Denmark (regions like Jutland, Fyn & Islands, Zealand, Bornholm), focusing on **sales trends, pricing, regional performance, and house types from 1992 onwards**.

The core business problem it solves:
- **Optimize housing sales strategies** to maximize revenue
- **Understand price dynamics**
- **Identify growth opportunities**

Key challenges addressed:
- Declining year-over-year (YOY) sales growth in certain sales types (e.g., -0.75 for regular sales)
- Variations in median sales prices by region (e.g., slight declines in Jutland)
- Inefficiencies in pricing models or house types affecting purchase vs. offer prices

For a **real estate company or investor**, this helps:
- Forecast demand  
- Target high-value segments  
- Reduce losses from underperforming areas or property types  

---

💡 Business Recommendations
1. **Focus on High-Growth Sales Types and Regions**  
   - Prioritize *auction* sales (YOY growth 0.29) over *regular_sale* (-0.75)  
   - Invest more in Zealand (95bn sales, yield ~4.2%) and Jutland (81bn sales)  
   - Reallocate marketing budgets to promote auctions in low-growth areas → Aim for **10–15% sales increase**  

2. **Optimise Pricing and Offer Strategies**  
   - Address offer–purchase price gaps (offers up to 15M vs. purchases at 10M)  
   - Age influences purchase price (+481.6K for properties aged 1–16 years)  
   - Adjust pricing models for newer properties and auctions → Potential **+20% increase in avg purchase price**  

3. **Target Profitable House Types**  
   - Focus on *farms* (highest avg price 2.7M & SQM price 28.7K) and *villas* (yield 4.6 & 4.2)  
   - Offer discounts/bundles for low-performing types (e.g., townhouses at 11.9K SQM) → Target **15% revenue uplift**  

4. **Monitor and Mitigate Declines**  
   - Minor drops in median sales price (e.g., -0.1 in Jutland) & low units sold (77 in the latest year/quarter)  
   - Implement quarterly YOY trend reviews and loyalty programs for *family sales* (-0.21 growth) → Stabilize revenue at ~13bn

---

🔄 Before vs After Impact
|            **Before**                                    |                                               **After** |
|------------------------------------------|----------------------------------------------------------------------------------------------------|
| No clear view of sales growth variations | Auction sales growing at 0.29 while regular sales drop -0.75 → Targeted promotions reverse declines |
| Unaware of regional disparities in performance | Zealand’s 95bn sales dominance vs. Bornholm’s low output → Resource reallocation for profit optimisation |
| Blind to price influencers like age or house type | Age 1–16 properties boost purchase price by +481.6K, farms yield the highest (4.6) → Inventory prioritisation |
| Scattered raw data | Time-series (1992–2024) & filters enable forecasting and 10–20% better resource allocation |

---

🛠️ Tools Used
- **Power BI** – Data cleaning, modelling, DAX calculations, and visualisation
- **Excel** – Column definitions and supporting data
- **DAX** – Custom calculated measures and KPIs

---

📊 Outputs
- **PDF Report** – Detailed static summary of findings  
- **Interactive Dashboard** – [View Power BI App Link](PUT-YOUR-LINK-HERE)

---

📫 Contact Links
- 💼 LinkedIn: [Rohini Singh](https://www.linkedin.com/in/rohini-singh-8a97a1229)
- 💻 GitHub: [Gitrohinihub](https://github.com/Gitrohinihub)
- ✉️ Email: miss.rohini09coder@gmail.com
