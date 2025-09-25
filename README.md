# E-commerce Sales Performance Analysis

This analysis evaluates a company’s sales performance using a large dataset (over 1 million rows across six CSV files, sourced from Freedom Edoh’s YouTube channel). The focus is on revenue, customer behavior, product performance, and market trends, with actionable insights for growth, risk management, and operational strategy. The data shows that the company made a lot of money overall ($105 million), and that international markets were the main reason for this growth. Customer spending habits, product focus, and payment preferences show both chances and dangers for long-term growth.

## Tools & Methodology

**Tools:**  
- Power Query (data cleaning & transformation)  
- Microsoft Excel (data modeling, pivot tables, DAX measures, and visualization)  

**Data Cleaning:**  
- Addressed missing values, typos (e.g., `coustomer_key` → `customer_key`), and inconsistent text formats.  
- Standardized capitalization, removed unwanted characters, and corrected invalid rows (e.g., incorrect bank names).  
- Excluded partial 2021 data to prevent misleading year-over-year analysis.  

**Data Transformation:**  
- Standardized units (e.g., “ct.” → “count”), engineered new features (Market Type: Domestic vs. International).  
- Split combined date-time fields and validated calculations (`total_price = quantity × unit_price`).  
- Renamed columns for clarity and improved analytical usability.  

**Data Modeling:** 
- Created DAX measures for Total Sales, Total Quantity, Customers, Average Order Value (AOV), Domestic vs. International Sales, and Year-over-Year Growth.  
- Developed PivotTables and dashboards for dynamic reporting and stakeholder insights.
- Established relationships between the fact table and dimension tables for relational queries using [Data Model](data%20visualisation%20and%20model.md#4-data-model)

 ## Visualizations
- [Shareholder Dashboard](Data_Model_and_Visualisation.md#1-shareholder-dashboard-overview)
- [Sales and Operations Dashboard](Data_Model_and_Visualisation.md#sales--operations-dashboard)
- [Customer and Quantity Dashboard](Data_Model_and_Visualisation.md#3-customer-quantity-dashboard)


## Key Insights
### Overall Performance
- **Total sales:** $105M | **Units sold:** 6M | **Customers:** 9K.  
- **International markets dominate:** $92M (87%) of sales; domestic sales underperform ($13M, 13%).  
- **Top products dominate revenue:** Five products generate ~42% of total sales, highlighting product concentration risk.  
- **Top regions dominate revenue:** Dhaka leads with $23M, more than double Chittagong ($7M) and Khulna ($4M), posing a geographic concentration risk.

### Revenue & Customer Trends
- **Stagnant growth (2014–2020):** Sales revenue, quantity, and customer numbers remained flat (~$14–15M/year).  
- **AOV stagnation:** Remains $368K–$387K, indicating limited upselling or cross-selling.  
- **Regional imbalances:** China underperforms ($152K AOV) despite high potential, while Bangladesh and India outperform.

### Product & Market Dependencies
- **Revenue vs. Quantity:** Premium products (Energy/Protein Beverages) generate high revenue per unit; mass-market products (Chips) rely on high volume at lower margins.  
- **Market concentration risk:** Top five countries account for ~60% of international sales.  
- **Payment dependency:** Card transactions dominate ($95M, 90%), while mobile (8%) and cash (3%) lag, indicating potential risk if card systems fail.

## Problems Identified
- Flat revenue, sales, and customer growth.  
- Overreliance on top products and key regions (Dhaka, top 5 countries).  
- Underperforming domestic market and China market.  
- Heavy dependency on card payments.  
- Limited diversification in international markets.  



## Recommendations
1. **Revenue Optimization:** Use bundling, personalized promotions, and tiered pricing to lift AOV by 8–10%.  
2. **Break Stagnation:** Launch targeted customer acquisition campaigns; focus on upselling and cross-selling.  
3. **Market Diversification:** Strengthen domestic channels and expand to underperforming regions (Rajshahi, Sylhet).  
4. **Regional Risk Mitigation:** Reduce Dhaka and Chittagong dependency by developing new growth hubs.  
5. **China Market Revamp:** Localize pricing, product mix, and payment options to raise AOV closer to regional averages ($280K–$330K).  
6. **Payment & Supply Resilience:** Encourage mobile wallet adoption (goal ≥20%) and diversify suppliers for top SKUs.  
7. **Customer Growth Acceleration:** Focus growth on high-value regions to build strongholds and sustainable momentum.


## Conclusion
The company demonstrates strong international sales and robust top-line performance but is vulnerable due to flat growth, product/market concentration, and regional imbalances. Sustainable growth requires expanding the customer base, improving AOV, diversifying products and markets, addressing underperforming regions, and strategically strengthening operational and payment resilience.

---

For the **full report with dashboards and detailed analysis**, you can read it on [Medium](YOUR_MEDIUM_LINK_HERE).

