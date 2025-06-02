# RetailStore-Analysis
This project presents a comprehensive analysis of retail store data using Power BI. It explores key business metrics such as sales performance, customer segmentation, product trends, and geographic distribution. The goal is to derive actionable insights to support strategic decision-making in retail operations.


![image](https://github.com/user-attachments/assets/4379be6b-4bf7-4920-b116-b172faa6fd90)
  Overall Revenue Summary:
Revenue During Promo: 169.47M
Revenue During NonPromo: 285.84M
➤ Insight: NonPromo sales outperform Promo sales by a large margin (approx. 68% higher).


  Revenue by Region:
Highest Revenue Region: North (107M NonPromo, 63M Promo)
Others: East and West show similar trends, with all regions performing better in NonPromo.
➤ Insight: North region drives the most revenue in both Promo and NonPromo phases.

  Overall Discount Analysis:
Total Discount is highest in 0–10% group (18.42M), aligning with the highest revenue.
No Discount group still generates over 100M in revenue with no cost from discounts.
➤ Insight: Minimal or no discounts still contribute significantly to revenue, challenging the effectiveness of large-scale promotions.

            Summary of Actionable Insights:
NonPromo strategies outperform Promo across all dimensions (category, region, and discount group).
Smaller discounts (0–10%) offer the best revenue-to-discount ratio.
North region and Groceries category are key contributors and should be focal points for sales optimization.
Deep discounts (21–30%) yield poor ROI and should be reconsidered.

-------------------------------------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/38a50575-0fc0-4337-975a-bb3680bbc9e3)
  General Observations (Across All Regions) :
Inventory Levels remain consistently higher than both Demand and Units Sold throughout the year.
Demand and Units Sold are closely aligned, indicating relatively accurate fulfillment rates.
There's a dip in February for all metrics across regions — possibly due to seasonality (e.g., shorter month or reduced activity).

Actionable Insights
Inventory Optimization Needed in the North & West:
North has surplus inventory; optimize based on demand patterns.
West shows signs of excess inventory without matching demand — reduce or redistribute.

Forecasting Opportunities:
Demand and Units Sold tracking closely implies forecasting models are effective.
Use East and South as models for tighter inventory control in other regions.

February Dip Across Regions:
Anticipate seasonal dips early to avoid overstocking and adjust procurement schedules accordingly.

December Uptick:
All regions show a slight year-end rise in demand and inventory — likely holiday impact. Plan accordingly.

---------------------------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/f917788b-7a6a-45e5-8a65-750128e20aca)
Insights:
Groceries dominate total sales across both periods, but especially during non-epidemic times (90% share).
Electronics and Toys showed relatively resilient demand during epidemics compared to categories like Clothing.
Furniture and Toys maintained similar proportions in both conditions — possibly considered essential or home-focused during lockdown-like conditions.

Strategic Insights:
📌 1. Epidemic Impact is Uneven by Category
Essential categories (like Groceries) maintain high sales even during epidemics.
Non-essential/discretionary categories (Clothing) experience sharper drops.

📌 2. Epidemic Months Create Sharp Drops in Sales
On average, epidemic periods reduce total monthly sales by ~30–60%.
Epidemic impact was most severe in early 2022 and early 2023, less impactful in late 2023.

📌 3. Resilience Opportunities
Electronics and Furniture had relatively stable demand, showing potential for e-commerce adaptation during crises.
Planning for inventory resilience in Groceries and Electronics is key for epidemic preparedness.

------------------------------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/6bffefdd-4bdb-4435-a656-a2c571e77a71)
Insights:
Clothing, Electronics, Groceries, and Toys are overpriced compared to competitors, potentially affecting demand.
Interestingly, Furniture is actually underpriced, despite being marked “Yes” under “Is Overpriced” — may indicate a data labeling issue or missed price advantage opportunity.
This could lead to pricing optimization opportunities across the board.

Insights:
Groceries have the highest inventory and sales volume — aligned with them being essential and high-demand.
For Clothing, Furniture, and Electronics, inventory levels far exceed actual sales and orders, indicating:
          Possible overstocking issues.
          Demand forecasting errors.
Toys have the lowest inventory and activity overall — signaling either low demand or intentional supply constraints.

Strategic Recommendations
📌 1. Address Overpricing
Reassess pricing strategies for Clothing, Electronics, and Groceries where you're priced higher than competitors.
Furniture may offer an edge — explore promotions around it being competitively priced.

📌 2. Optimize Inventory
Use historical sales + forecast models to avoid overstocking, particularly for Electronics, Clothing, and Furniture.
Consider markdown strategies or bundling offers for slow-moving inventory.

📌 3. Push High-Revenue Categories
Maintain strong supply chains and marketing support for:
Groceries: Consistent top performer.
Furniture: High revenue, price competitive.
Clothing: Stable performer with scope for improvement.

---------------------------------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/6be3b3de-2d20-4591-bec1-87f9b49b33a6)
Total Revenue by Region and Category
🧥 Clothing
Best performance in West (₹29M), followed by South (₹24M) and North (₹19M).
East lags at ₹14M.

📱 Electronics
Strongest in East (₹22M) and North (₹20M).
Poor revenue from West (₹6M), suggesting either poor demand or distribution issues.

🪑 Furniture
Major revenue from North (₹46M) and West (₹43M).
East and South underperform significantly (₹17M and ₹6M respectively).

🛒 Groceries
North dominates (₹71M), followed by East (₹41M) and South (₹40M).
West is weak (₹17M), indicating a possible supply issue or low demand.


Demand vs. Sales vs. Inventory (by Region)
✅ Key Observations:
📍 East:
Demand, sales, and inventory are relatively balanced across most categories.
Electronics has excess inventory vs. demand — potential overstocking.

📍 North:
High inventory levels, especially for Furniture and Electronics, not matched by sales.
High demand seen in Groceries, but needs better inventory balancing in other categories.

📍 South:
Balanced trends overall.
Groceries have higher demand and sales, aligned with revenue performance.
Toys consistently low.

📍 West:
Inventory > Demand across Electronics, Furniture, and Clothing.
Groceries again perform best here in terms of balance.

Strategic Recommendations by Region
📦 Inventory Optimization
North: Drastically reduce excess inventory, particularly for Furniture and Electronics.
West: Similar actions needed, especially since revenue is low despite high stock.
South and East: Reasonable balance — can serve as benchmarks for demand forecasting.

💰 Revenue Opportunity Regions
Clothing: Focus on expanding in East, where revenue lags.
Electronics: Reassess or scale back in West, increase push in East/North.
Furniture: Scale up presence in East/South, already strong in North/West.
Groceries: Prioritize North for marketing and logistics — it’s a major revenue contributor.

------------------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/0cca1839-e428-457f-add8-8254d07dd32d)
Key Insights
📉 General 2024 Decline:
All categories and regions show drastic declines in 2024. This suggests a macro event like:
  Disruption in supply chain  
  Policy changes
  Market contraction or transition to new product lines

Recommendations
Investigate the 2024 Decline:
Could relate to the “Epidemic” slicer from your earlier dashboards.
Analyze production, logistics, and policy shifts during early 2024.

Capitalize on High Performing Regions:
Focus sales and inventory investment for:
Groceries in North and East
Furniture in North and West
Clothing in South and West

Improve Low Performing Regions:
Targeted marketing or logistics investment needed in:
Electronics in West
Furniture in South

Forecast with Scenario Planning:
Prepare for disruptive events in 2025 using these 2024 insights.
Simulate inventory and demand plans with epidemic sensitivity.

-------------------------------------------------------------------------------------------------------


              Key Insights from Sales Data
Sales Dropped Sharply in 2024
All product categories and regions saw a big fall in units sold—likely due to an epidemic or major disruption.

Groceries Lead the Market
Groceries had the highest sales, especially in the North, making it the top-selling category overall.

North Region Performs Best
The North region consistently had the highest sales across all product categories in 2022 and 2023.

Electronics and Furniture Struggle in Some Areas
Electronics sold the least in the West, and Furniture sales were low in the South, showing regional weaknesses.
