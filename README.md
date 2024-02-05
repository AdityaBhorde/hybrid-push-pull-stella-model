# Hybrid Push Pull Model (Stella) - Supply Chain Optimization

The model is created on Stella software.
### Description : 
The model depicted in the Stella simulation software is a causal loop diagram, which is commonly used in system dynamics to represent the feedback structure of systems. It is specifically focused on supply chain management for a product distribution system. Here's a detailed description of the model components and their relationships: 
1. Central Components: 
Distributor Inventory & Dealer Inventory: These represent the stock levels at the distributor and dealer respectively. They are central to the model, indicating the flow of vehicles through the supply chain. 
Sales Rate: This indicates the rate at which vehicles are being sold to the end customers. 
 
2. Feedback Loops:- The diagram includes several balancing (B) and reinforcing (R) loops, which are key features of system dynamics models. 
Balancing Loops (B): These loops are designed to bring the system to a desired state or equilibrium. They include mechanisms that adjust the inventory based on various factors such as the desired inventory, the order fulfillment rates, and the sales rate. 
Reinforcing Loops (R): These loops can lead to exponential growth or decline within the system. In this model, reinforcing loops might represent scenarios where increasing sales lead to increased profits, which in turn might be reinvested to further increase the sales capacity. 

3. Inputs and Adjustments: 
Distributor Order Fulfilment Rate & Dealer Order Fulfilment Rate: These rates affect how quickly the distributor and dealer can fulfil orders, impacting inventory levels. 
Distributor Adjustment Time & Dealer Adjustment Time: These are delays in the system that represent the time taken for the distributor and dealer to adjust their inventory in response to changing conditions. 
 
4. Demand and Sales: 
Customer Demand Rate: This is an external input to the system, representing the rate at    which customers want to purchase vehicles. 
Desired Sales Rate: This is the target rate at which the company aims to sell vehicles. 
Max Sales Rate: This is the maximum rate at which the system can sell vehicles, likely limited by production or supply constraints. 
 
5. Costs and Financial Metrics: 
Unit Cost & Adjusted Unit Cost: These represent the cost to the company for each vehicle, with adjustments potentially accounting for volume discounts, transportation costs, etc. 
Inventory Carrying Cost: The cost associated with holding inventory, which could include storage, insurance, depreciation, and opportunity costs. 
Sales Price: The price at which vehicles are sold to customers. 
Cash Balance & Profit: These are financial outputs of the system, representing the company's financial health and performance. 
 
6. Inventory Policies: 
Safety Stock Coverage: This indicates the amount of extra inventory kept on hand to prevent stockouts. 
Desired Inventory & Desired Distributor Order: These are target levels for inventory and orders, aiming to ensure enough stock to meet customer demand without overstocking. 
 
7. Time Delays: 
Average Dwell Time: The average time that vehicles stay within the system before being sold. 
Dealer Order Fulfilment Cycle Time: The time it takes for the dealer to complete an order fulfilment cycle. 
Min Sales Processing Time: The minimum time it takes to process a sale, likely impacted by administrative tasks. 
 
8. Market Dynamics: 
Change in Expected Customer Demand & Time to Average Customer Demand: These variables represent how the company anticipates and reacts to changes in market demand over time. 
 
This causal loop diagram is a dynamic representation of the interconnected elements within the supply chain. Each variable and loop impact the system, and changes to one part can have ripple effects throughout the entire system. In analyzing such a model for supply chain efficiency, one would simulate various scenarios to understand the impact of different inputs on the outputs and identify leverage points for improving system performance.

### Analysis:
1. Inventory Levels: 
Safety Stock Coverage: At 3 weeks, reducing this to, say, 2 weeks could potentially decrease the Dealer Inventory by approximately 1/3 (assuming linear relation), which in this case could be around 2.02k units. This reduction would decrease the Inventory Carrying Cost by about 40.4k NGN/week (2.02k units * 20k NGN/unit). 
Desired Inventory and Order Fulfillment: Lowering the Dealer and Distributor Inventory could improve the Cash Balance by reducing the capital tied up in inventory. For instance, each 1k reduction in Distributor Inventory could free up 3.5 billion NGN (1k units * 3.5 million NGN/unit). 

2. Lead Time Reduction: 
By reducing the Dealer and Distributor Adjustment Time from 6 weeks to 4 weeks, the responsiveness to market changes improves. This could potentially increase the Expected Customer Demand fulfillment rate and reduce the Total Dwell Time, contributing to an increased Sales Rate and potentially higher Profit margins. The reduction in lead times can also decrease inventory levels due to more efficient turnover, impacting the holding costs. 

3. Demand Forecasting: 
Accurate forecasting that brings Expected Customer Demand closer to actual demand can reduce both overstock and stock outs. Even a 10% improvement in forecasting accuracy can lead to more effective inventory management, potentially increasing sales if demand is higher than expected or reducing Inventory Carrying Costs if demand is lower.


4. Cost Reduction: 
If the Adjusted Unit Cost of 3.5 million NGN could be reduced by even 5% through better negotiations or efficiency gains, this would result in savings of 175,000 NGN per vehicle. 
Across an expected demand of 2.02k units/week, this represents a potential cost saving of 353 million NGN/week. 

5. Process Optimization: 
Decreasing the Min Sales Processing Time from 2 weeks to 1 week could improve cash flow and responsiveness. Similarly, reducing the Dealer Order Fulfillment Cycle Time from 6 weeks to 4 weeks could enhance the Sales Fulfillment Ratio, potentially increasing the Sales Rate. 
This could shorten the cash-to-cash cycle time, potentially increasing the Cash Balance due to quicker returns on sold inventory. 
 
6. Price Optimization: 
If a price adjustment leads to a change in demand, a sensitivity analysis would be required. 
For instance, a 5% increase in Sales Price could lead to additional profit if the demand is inelastic. On a weekly basis, this could potentially increase the Sales Revenue by 415 million NGN (5% of 8.3 billion NGN). 
 
7. Dynamic Replenishment: 
A more responsive replenishment system could reduce the need for high levels of safety stock by more closely aligning inventory with actual sales. Even a 10% reduction in excess inventory due to better replenishment could significantly impact cash flow and carrying costs. 
 
8. Technology and Automation: 
An investment in technology could lead to long-term savings, though it's difficult to estimate without specific costs. Typically, automation can lead to a reduction in manual processes and errors, which could, for example, improve the Distributor Order Fulfillment Rate by 10-20%. 
 
9. Supplier Management: 
Better supplier terms could reduce the cost of goods sold. A 2% reduction in procurement costs due to improved supplier management could have a substantial impact on the Adjusted Unit Cost, leading to increased Profit margins. 
 
10. Customer Relationship Management: 
Understanding customer needs could lead to a more accurate demand forecast and a better match between production and sales, thereby reducing inventory carrying costs and improving the Sales Rate. 
 
11. Lean Practices: 
Implementing lean practices could lead to a 5-10% reduction in waste throughout the supply chain. This could lower Total Cost and improve Profit through increased efficiency. 

