# E-commerce Profit Leakage Analysis (Power BI)
> The Power BI file (.pbix) is available on request. The dashboard is shown in the screenshots below and in `docs/Profit-Leakage-Dashboard.pdf`.

## Business problem
(your paragraph)

## Key findings
(3 findings from the earlier message)

## Dashboard preview
![Executive summary](docs/exec-summary.png)
![Delivery leak](docs/delivery-leak.png)
![Freight leak](docs/freight-leak.png)
![Seller leak](docs/seller-leak.png)
![Recommendations](docs/recommendations.png)

## Data model
![Model](docs/data-model.png)

## Technical highlights
- Power Query: type fixes, merges, one-row-per-order reviews and payments
- Star schema: order_items fact + orders, customers, products, sellers, date dimension
- 30+ DAX measures, calculated columns (delay bucket, seller tier), what-if parameter

## Recommendations
(table)

## Assumptions and limitations
(bullets)

## Data
Olist Brazilian E-Commerce Public Dataset (Kaggle), currency R$.

## Author
Tanushree Singh | LinkedIn | email

> The Power BI file (.pbix) is available on request. The dashboard is shown in the screenshots below and in `docs/Profit-Leakage-Dashboard.pdf`.
