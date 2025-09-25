# E-commerce Dashboards & Data Model

This document contains all dashboards and the data model used in the E-commerce Sales Performance Analysis. It provides visual insights into sales performance, customer behavior, and product/market analysis.


## 1. Shareholder Dashboard (Overview)
![Shareholder Dashboard](https://github.com/odzainab/E-commerce-Analysis/blob/main/Images/Overview%20Dashboard.png?raw=true) 
*Figure 1: Shows total sales ($105M), total units sold (6M), total customers (9K), revenue by geography, and top products. Highlights concentration risk in Dhaka and top five products.*

**Key Insights:**  
- Total revenue of $105M generated mostly by international markets ($92M).  
- Top five products contribute ~42% of sales, creating product concentration risk.  
- Dhaka is the leading revenue generating district ($23M), more than double Chittagong and Khulna.


## 2. Sales & Operations Dashboard

![Sales Dashboard](https://github.com/odzainab/E-commerce-Analysis/blob/main/Images/Sales%20Dashboard.png?raw=true)  
*Figure 2: Analyzes sales channels, quarterly performance, payment types, and regional revenue distribution.*

**Key Insights:**  
- Heavy reliance on card payments ($95M, 90%).  
- Quarterly sales are stable: Q1 ($25M), Q2 ($26M), Q3 ($27M), Q4 ($27M).  
- International sales dominate (87%), with potential for domestic market growth.  
- Top five countries account for ~60% of international sales, indicating limited diversification.


## 3. Customer & Quantity Dashboard

![Customer Dashboard](https://github.com/odzainab/E-commerce-Analysis/blob/main/Images/Customer%20&%20Quantity%20Dashboard.png?raw=true)  
*Figure 3: Tracks customer growth, average order value (AOV), and sales quantity.*

**Key Insights:**  
- Stagnant AOV trend ($368K–$387K) over 2014–2020, showing limited upselling/cross-selling.  
- Customer distribution is fairly balanced across regions but with untapped growth potential.  
- China underperforms ($152K AOV) despite high population, indicating missed opportunity.  
- Domestic sales are low ($13M), suggesting opportunities for market expansion.


## 4. Data Model

![Data Model](https://github.com/odzainab/E-commerce-Analysis/blob/main/Images/Data%20Model.png?raw=true)  
*Figure 4: Shows relationships between the fact table and dimension tables, enabling DAX measures for analysis.*

**Notes:**  
- Fact table connects with Item_Dim, Customer_Dim, Store_Dim, Time_Dim, and Tran_Dim.  
- One-to-many relationships ensure accurate aggregation.  
- Measures such as Total Sales, Total Quantity, Customers, AOV, Domestic vs. International Sales, and YoY Growth are calculated based on this model.




