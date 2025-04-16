# E-COMMERCE CUSTOMER INSIGHT DASHBOARD
---

## Project Overview
An international e-commerce company specializing in electronic products seeks to gain valuable insights from their customer database. The company aims to assess delivery performance, customer satisfaction, and operational efficiency.
The dataset used for this analysis includes 10.999 obervatiions across 12 variables such as shipment mode, warehouse blocks, customer ratings, product cost, discount, gender, and delivery timeliness.

### Project Objective
This project aims to:
- Evaluate delivery and shipping performance.
- Analyze customer satisfaction and engagement.
- Investigate the impact of discounts, cost, and product importance.
- Determine the effectiveness of warehouses and shipment modes.
- Provide actionable insights for operational improvement.

 ### Tools Used
 - Power BI, Excel
 - Datasets 10,999 x 12 Variables
 - Target Variable: Reached on Time (1 = Not on time, 0 = On time)

### Key Performance Indicator
KPI	Metric	Value: 

![Screenshot 2025-04-14 134211](https://github.com/user-attachments/assets/cd2ec486-7376-47b7-9cf5-f2d26eec122f)
![Screenshot 2025-04-14 133950](https://github.com/user-attachments/assets/e77e326f-1e9d-414b-99b1-9045ea0b5a85)

- Total Orders - 11,000
- On Time Delivery Rate - 40.3%
- Late Delivery Rate - 59.7%
- Average Customer Rating -	2.99
- Customer Complaint Rate -	53.5%
- High Customer Care Calls - 5,885
- Average Cost per Product - 210.20
- Average Discount Offered - 13.37
- Total Product Cost - $2M


### Key Analysis/Insights


#### Average of Customer Rating by Purchase Group:

![Screenshot 2025-04-14 134552](https://github.com/user-attachments/assets/885d7447-2720-4159-bd57-c3d8e406e322)

Insight - The purchase group are divided in 3 using their prior purchases
- High Very loyal - Average Ratings 3.03
- Medium Loyal - Average Ratigs 3.00
- Low Not loyal - Average Ratings 2.96

  #### Average Product Cost by Level of Importance
![Screenshot 2025-04-14 134605](https://github.com/user-attachments/assets/279c73c0-fbef-4aa8-a0c1-9f7e4d1cb61d)
  
  
Average Costs:
- Low: $212.06
- Medium: $209.38
- High: $203.87

Insight: Surprisingly, high importance products cost less on average — possibly due to discounts or streamlined inventory.

#### Prior Purchase By Product Importance
![Screenshot 2025-04-14 134620](https://github.com/user-attachments/assets/faac5972-d9d0-4103-8440-71d12982cf8f)

- Products marked Low had the highest repeat purchases 19K
- High importance products had the lowest repeat count 3K
- While medium importance product had over repeat purchase count 17k

Insight: Low importance items drive volume; high importance products may be niche or high cost.


#### Impact of Warehouse Block on Shipping Duration 
![Screenshot 2025-04-14 134646](https://github.com/user-attachments/assets/6c4a134e-9758-4f78-afca-81e254524400)

- Warehouse F and D had the most late deliveries
- Warehouse C showed better performance (more on time deliveries)
- Insight: Operational inefficiency may exist in specific warehouses.

#### Shipment Mode by Product weight

![Screenshot 2025-04-14 134658](https://github.com/user-attachments/assets/8f2e15bc-5915-4b1a-9cf8-28b314f3f5e0)

Weight in Grams by Shipping Mode
- Ship carries significantly heavier loads (27M grams)
- Flight and Road carry 6M grams each
Despite handling the heaviest shipments (27M grams), the Ship mode shows better delivery performance compared to Flight and Road. This suggests that shipping heavier products via Ship is more reliable, possibly due to bulk logistics optimization. In contrast, Flight and Road, though used for lighter loads, have higher delay rates indicating that delays may be due to operational inefficiencies rather than product weight.

#### Shipment Mode vs Delivery Timeliness
![Screenshot 2025-04-14 134708](https://github.com/user-attachments/assets/5d5a0f03-ffec-4687-ab85-cd036416c1e3)

- Road had the highest percentage of late deliveries
- Ship performed better but still had delays
 Insight: Shipment method strongly influences delivery performance, Flight is not significantly faster.

 #### Customer Call by Resolution Status
![Screenshot 2025-04-14 134721](https://github.com/user-attachments/assets/b008a089-5172-493f-8ac8-055581dd1394)

 Resolved vs Unresolved Calls
- Calls are split 50/50 between resolved and unresolved
- Insight: Equal distribution suggests a need for better resolution handling.

#### Order Distribution by Shipping Mode
![Screenshot 2025-04-14 134741](https://github.com/user-attachments/assets/6ab1a233-da1d-4f18-b9ee-fe7bc5b3904e)

Insight: The majority of orders (67.84%) were delivered via Ship, making it the most preferred shipping method. Interestingly, despite handling the highest volume and heaviest products, Ship has better on-time performance compared to Flight and Road, each accounting for 16% of orders but showing higher delay rates.
This suggests that volume alone isn't the main cause of delays — operational efficiency plays a more critical role.


#### Discount Offered by Customer Ratings

![Screenshot 2025-04-14 134754](https://github.com/user-attachments/assets/3d7cee65-60b7-4386-8a40-e9fb1b70ebc7)

Discount by Rating Category
Discount values are fairly uniform across rating levels ( $29K–$30K)
Insight: Discounts do not strongly influence customer satisfaction, customer service and delivery might be more important.

#### Customer Call vs Satisfaction Rating
![Screenshot 2025-04-14 134805](https://github.com/user-attachments/assets/2b150737-cec2-4a90-9d83-e5ae34bdb424)

- Ratings like "Best" and "Good" are tied to fewer complaints
- "Worst" and "Poor" ratings from customers had high call volumes
 Insight: Poor ratings are linked to more service inquiries expected, but confirms dissatisfaction.


#### Complaint Rate by Purcchase Group
 ![Screenshot 2025-04-14 134820](https://github.com/user-attachments/assets/b4280097-4271-4b87-bf2a-5f47ec9cdf7a)

The purchase group are divided into 3 using their prior purchases
- Complaint Rate by Purchase Group
- High (Very Loyal) - 59.9% Complaint Rate
- Medium (Loyal) - 53.5%
- Low (Not Loyal) - 52.6%

Insight - The very loyal customers tend to complain the most, yet they continue making purchases and remain loyal. This could indicate that while they are dissatisfied with certain aspects of the service, they highly value the product and may not have found a suitable alternative.

#### Total Orders by Gender
![Screenshot 2025-04-14 134902](https://github.com/user-attachments/assets/a8a82331-2d54-4e9a-b05e-c5f2e99d97a3)

Fairly even split: 50.41% Female, 49.59% Male
Insight: The business has a balanced customer base, useful for targeting promotions equally.


#### Count of Purchase Group
![Screenshot 2025-04-14 134832](https://github.com/user-attachments/assets/99fd046e-e79b-43c1-865c-13db7c877afd)

The purchase group are divided into 3 using their prior purchases
-The medium (Loyal) Customers have the most population, count of 7.4k, while the Low (Not Loyal) count is 2.6k

Insight - The High (High Prior Purchases) very loyal customers ranked the lowest, this might be because customers do not want to stay loyal to a company that does not satisfy them.

### Recommendation 
Improve Warehousing:
- Prioritize operational review of Warehouse F and D
- Introduce better inventory flow and staff performance KPIs

Optimize Shipping Strategy:
- Reduce road shipments for time sensitive items
- Consider hybrid models using flight + local delivery

Customer Support Enhancements:
- Train staff to improve resolution rate (currently 50%)
- Automate simple query resolution using chatbots

Product Strategy:
- Reprice high importance products to better reflect perceived value
- Encourage repeat purchases through loyalty rewards

Discount Personalization:
- Instead of flat discounts, use rating and behavior-based offers
- Measure impact of targeted discounts on satisfaction
