# E-commerce Profit Leakage Analysis (Power BI)
> The Power BI file (.pbix) is available on request. The dashboard is shown in the screenshots below and in `docs/Profit-Leakage-Dashboard.pdf`.

## Business problem
Where does an online marketplace lose revenue, and how much can it recover?
Analysed 100k orders to find three leaks: late deliveries, freight cost, weak sellers.

## Key findings
1. **Late deliveries wreck ratings, not retention.** 6.8% of orders arrive late. Average review falls from ~4.3 (early) to ~1.7 (8+ days late). Repeat-purchase loss is small (~R$9.7K, 0.07% of revenue) because most customers buy once.
2. **Freight is the largest quantifiable leak.** Freight is 16.6% of revenue (R$2.25M). About R$272K is above the marketplace average rate, concentrated in furniture_decor, housewares and bed_bath_table. Remote states (RR, MA) pay 26–28% of revenue in freight.
3. **Seller risk is concentrated.** 57 weak sellers account for R$751K (5.5% of revenue), and 23% of revenue comes from sellers with fewer than 30 orders.

## Dashboard preview
![Executive summary](https://github.com/Singhtanusree/ecommerce-profit-leakage-powerbi/blob/main/docs/exec-summary.png.png)
![Delivery leak](https://github.com/Singhtanusree/ecommerce-profit-leakage-powerbi/blob/main/docs/delivery-leak.png.png)
![Freight leak](https://github.com/Singhtanusree/ecommerce-profit-leakage-powerbi/blob/main/docs/freight-leak.png.png)
![Seller leak](https://github.com/Singhtanusree/ecommerce-profit-leakage-powerbi/blob/main/docs/seller-leak.png.png)
![Recommendations](https://github.com/Singhtanusree/ecommerce-profit-leakage-powerbi/blob/main/docs/recommendations.png.png)

## Data model
![Model](https://github.com/Singhtanusree/ecommerce-profit-leakage-powerbi/blob/main/docs/data-model.png.png)

## Technical highlights
- Power Query: type fixes, merges, one-row-per-order reviews and payments
- Star schema: order_items fact + orders, customers, products, sellers, date dimension
- 30+ DAX measures, calculated columns (delay bucket, seller tier), what-if parameter

## Data
Olist Brazilian E-Commerce Public Dataset (Kaggle), currency R$.

## Author
Tanushree Singh | https://www.linkedin.com/in/tanushree-singh-17835b36b/?isSelfProfile=true | singhtanushree.10@gmail.com

> The Power BI file (.pbix) is available on request. The dashboard is shown in the screenshots below and in `docs/Profit-Leakage-Dashboard.pdf`.
