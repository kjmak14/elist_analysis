# Siara Tech eCommerce Analysis

The goal of this analysis is to evaluate sales performance through the COVID-19 period (2019-2022), delivering insights on key revenue drivers and actionable recommendations for Operations, Sales, and Marketing leadership teams.

# Overview 
<p align="center">
  <img src="siara_tech_logo_small.png" alt="Siara Tech Logo" width="200"/>
</p
  
Siara Tech is a digital-first electronics retailer founded in 2015, focused on delivering premium consumer tech. Operating exclusively online, the company combines smart product curation, fast fulfillment, and a sleek, user-centric shopping experience.

A trusted destination for high-performance electronics, Siara Tech offers a curated experience that appeals to anyone seeking reliable, modern tech—without the noise of traditional retail.

<details>
  <summary><strong>Stakeholder Questions</strong></summary>
  <ul>
    <li>What were the overall trends in sales during this time?</li>
    <li>What were our monthly and yearly growth rates?</li>
    <li>How is the new loyalty program performing? Should we keep using it?</li>
    <li>What were our refund rates and average order value?</li>
  </ul>
</details>

# Executive Sumary
### Overview of Findings
<img width="1013" height="639" alt="image" src="https://github.com/user-attachments/assets/76218c6e-e5e2-4273-b9b4-c252e710eaaa" />
Siara Tech experienced explosive pandemic-driven growth peaking at $10M in 2020, but revenue has since declined 46% as market conditions normalized, highlighting the need for sustainable growth strategies beyond remote work trends. The loyalty program is counterproductive, with non-loyalty customers outperforming across all metrics, while APAC represents significant untapped growth potential with premium customer behavior. Quality challenges are eroding over $1M annually and require immediate attention to protect profitability.


### Key themes for leadership
1. Growth Strategy: Pandemic boom was unsustainable, but core products remain reliable drivers worth priortizing

2. Resource Reallocation: Loyalty program is underperforming, but APAC shows premium customer behavior worth scaling

3. Quality Challenges: High refund costs for the Macbook Air and Gaming Monitor threaten margins and require investigation

# Deep-Dive Insights
### Revenue Trends and Growth Analysis
Overall sales performance, monthly and yearly growth rates, and key inflection points.
<img width="1022" height="642" alt="image" src="https://github.com/user-attachments/assets/58418d3f-ce41-4be9-a4f6-9b66adf81c59" />
* **2020 was the best performing year over the 2019-2022 time period**, generating over $10M in revenue. The top selling products - Gaming Monitor, Apple Airpods, and Macbook Air - collectively drove over 80% of sales that year.

* **Revenue peaked in December 2020 at just over $1.2M**, representing our highest single-month performance during the analysis period.

* **Annual revenue growth peaked between 2019-2020 at 163%**, likely driven by pandemic-induced demand for remote work technology. Macbook Air and ThinkPad laptops experienced the highest individual product growth rates at 384% and 222% respectively.

* **The largest monthly growth spike was from February 2020 to March 2020**, coinciding with inital COVID lockdowns, with all products experiencing revenue increases during this period.

* **Revenue declined sharply from 2021-2022 with a 46% drop**, reaching an all-time low of $178K in October 2022, with the only exceptions being slight seasonal holiday upticks in November and December, suggesting market normalization post-pandemic.

### Loyalty Program Performance
Evaluation of the new loyalty program's impact on repeat purchases and revenue contribution.
<img width="1041" height="555" alt="image" src="https://github.com/user-attachments/assets/796602fd-82d6-41d2-a92d-727dfa68d5c6" />
<img width="1049" height="554" alt="image" src="https://github.com/user-attachments/assets/2114c709-8364-4004-9279-2a9f27c0f13e" />
* **Loyalty customer revenue continues to decline from its peak in Dec 2021**, generating less revenue than non-loyalty customers by the end of 2022.

* **Non-loyalty customers outperformed loyalty customers**, with 13% higher average order value and comprising 61% of total sales during the analysis period, suggesting the program may not be effectively incentivizing higher spending.

* **Loyalty revenue declined 83% while AOV only declined 17%** following Q4 2021, indicating an issue with loyalty customer retention.

* **Active loyalty customer participation is decreasing**, with non-loyalty customers placing more orders than loyalty customers in the past 4 months, raising questions about program engagement and value proposition.

* **The loyalty program is performing worse at driving repeat purchases**, with only 0.5% of loyalty customers making more than one purchase compared to 11% of non-loyalty customers

### Regional Performance Segmentation
Sales performance across regions, focusing on differences in revenue, AOV, and customer behavior
<img width="1041" height="550" alt="image" src="https://github.com/user-attachments/assets/fef5d5de-b5ab-4517-bd73-2ff176415c8b" />
* **All regions experienced similar revenue patterns**, peaking during 2020-2021 COVID period before declining, indicating global market forces drove performance more than regional factors

* **North America dominated revenue generation** with over $14M in sales and making up 50.8% of market share, representing our strongest market position and customer base

* **APAC customers show the highest spending per order at $280 AOV** but generated the second-lowest total revenue, suggesting limited market reach despite premium customer behavior

* **LATAM underperformed across both metrics** with the lowest revenue and AOV, indicating potential market entry challenges or pricing misalignment

### Refund Impact Analysis
Refund behavior across product categories, including refund rates, associated costs, and their effects on profitability
<img width="1000" height="524" alt="image" src="https://github.com/user-attachments/assets/a0805297-defa-452d-b644-409d0c9c9bee" />
* **Refund rates spiked in H1 2022 and have remained elevated**, indicating potential quality or customer satisfaction issues
  
* **Refund costs are projected to match 2022 levels** based on current trends through the first half of 2023
  
* **Laptops show the highest refund rates**, with both ThinkPads and Apple MacBooks experiencing significantly more returns than other product categories at 12% and 11% respectively
  
* **Gaming monitors and MacBook Air drive the highest refund costs** due to their premium price points, collectively reducing gross revenue by nearly $1.4M

# Recommendations
Based on the insights and findings above, I would recommend teams to consider the following:

* **Focus marketing spend and inventory investment on our top three core products, the Gaming Monitor, Apple Airpods, and MacBook Air**. These products have proven to be reliable market drivers during both growth and decline periods.

* **Evaluate Loyalty Program ROI and conduct customer interviews to evaluate what value, if any, we're offering to customers through this program**. Loyalty customers are generating less revenue and have lower AOV than non-loyalty customers, so it's important that this program is able to incentivize higher spending or encourage more repeat purchasing behavior in order to provide value for our business.

* **Consider reallocating resources from the Loyalty Program to focus on APAC expansion initiatives**, targeting customer acquisition in a market where customers already demonstrate 7% higher spending patterns.

* **Identify root cause issues leading to continued evelated refund costs**, since this suggests a potential systematic issue. Refund rates spiked in H1 2022 and has remained elevated, putting us on track to match 2022 refund costs by the end of this year.

* **Investigate potential issues with our laptop suppliers**, given that the refund rate for the MacBook Air and ThinkPad Laptops are 11-12% compared to 1-6% for other products.

# Data Structure & Initial Checks
The company's main database structure consists of the following four tables:

* **customers**: Details about the creation fo the customer's account
* **geo_lookup**: Reference of countries and their respective region
* **order_status**: Dates for the various statuses of each order
* **orders**: Product and price information for each order

![image](https://github.com/user-attachments/assets/b410c9bb-3296-4488-83f2-9d4f11fe9a19)

# Assumptions and Caveats
Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Orders with $0 transaction prices is missing data and not customers who received products for free

* Fluctuations in pricing within individual products were purchases made with coupons or special discounts and not changes in retail pricing

* Mismatches between currency and country per customer was due to customers purchasing items in a different currency than where they are located

* When calculating repeat purchases, customer loyalty status was determined based on their loaylty status for their most recent purchase

