# Coffee Shop Sales Analysis — Business Insights

## 1. Overview

This document summarizes the main findings reported in the project's README for coffee shop sales from **January 1 to June 30, 2023**. The dataset contains **149,116 rows**, 11 columns, 3 stores, 80 products, 9 product categories, and 29 product types.

## 2. Key Findings

### Store performance

- **Hell's Kitchen** is identified as the highest-revenue store.
- Hell's Kitchen recorded **50,735 transactions** and an average transaction value of **$4.66**.
- **Lower Manhattan** had the highest average transaction value at **$4.81**, despite having fewer transactions (47,782) than Hell's Kitchen and Astoria.

| Store | Transactions | Average transaction value |
|---|---:|---:|
| Hell's Kitchen | 50,735 | $4.66 |
| Astoria | 50,599 | $4.59 |
| Lower Manhattan | 47,782 | $4.81 |

**Interpretation:** Store rankings can differ depending on whether performance is measured by transaction volume or average transaction value. These metrics should be considered together.

### Product category performance

- **Coffee** is the largest revenue-generating category.
- Reported coffee revenue is **$269,950**, approximately **89,000 units** sold, and **38.63%** of total revenue.
- Reported average revenue per unit is **$3.02**.

**Interpretation:** Coffee is a major contributor to revenue. Further analysis could break its performance down by product, store, and time of day.

### Highest-revenue products


| Rank | Product | Revenue | Quantity | Average unit price |
|---:|---|---:|---:|---:|
| 1 | Sustainably Grown Organic Lg | $21,151.75 | 4,453 | $4.75 |
| 2 | Dark Chocolate Lg | $21,006.00 | 4,668 | $4.50 |
| 3 | Latte Rg | $19,112.25 | 4,497 | $4.25 |
| 4 | Cappuccino Lg | $17,641.75 | 4,151 | $4.25 |
| 5 | Morning Sunrise Chai Lg | $17,384.00 | 4,346 | $4.00 |
| 6 | Latte | $17,257.50 | 4,602 | $3.75 |
| 7 | Jamaican Coffee River Lg | $16,481.25 | 4,395 | $3.75 |
| 8 | Sustainably Grown Organic Rg | $16,233.75 | 4,329 | $3.75 |
| 9 | Cappuccino | $15,997.50 | 4,266 | $3.75 |
| 10 | Brazilian Lg | $15,109.50 | 4,317 | $3.50 |

**Interpretation:** The highest-revenue product is not necessarily the highest-volume product. Comparing revenue, quantity, and unit price helps distinguish high-value products from products that sell more units.

### Hourly sales

- **10 AM** is reported as the peak revenue hour, with **$88,673.39** in revenue.
- The README also identifies 10 AM as the peak transaction hour, with **18,545 transactions**.

**Interpretation:** The morning period merits closer operational review. Before changing staffing or stock levels, compare hourly demand across stores and days and confirm how transactions are counted.

### Day-of-week performance

- **Monday** generated the highest reported revenue: **$101,677.28**.
- **Friday** recorded the highest reported transaction volume: **21,701 transactions**.

**Interpretation:** The day with the most transactions is not necessarily the day with the highest revenue. Average transaction value and product mix may help explain the difference, but the current figures alone do not establish the cause.

### Store-specific weekday patterns

| Store | Highest-transaction day | Highest transactions | Highest-revenue day | Highest revenue |
|---|---|---:|---|---:|
| Hell's Kitchen | Friday | 7,489 | Tuesday | $34,846.47 |
| Astoria | Thursday | 7,427 | Wednesday | $34,244.63 |
| Lower Manhattan | Monday | 7,136 | Monday | $34,359.48 |

**Interpretation:** The stores have different reported peak days. Planning should therefore be informed by each store's own weekday and hourly patterns rather than relying only on chain-wide averages.

## 3. Recommended Actions

These are **areas to investigate**, not proven interventions or guaranteed outcomes.

1. **Review the 10 AM peak.** Compare demand by store and weekday, then assess whether staffing and product availability align with observed activity.
2. **Investigate coffee category drivers.** Identify which coffee products and stores contribute most to the category's 38.63% revenue share.
3. **Plan at store level.** Examine each store's peak transaction and revenue days before standardizing staffing, inventory, or promotions.
4. **Use multiple performance measures.** Track revenue, transaction count, quantity sold, and average transaction value together.
5. **Review leading products.** Compare the top products' revenue and quantity across stores and periods to understand where their performance is strongest.
6. **Add cost data before making profit decisions.** Product costs, waste, labor, rent, and other operating expenses would be needed to evaluate profitability or the financial impact of changes.

## 4. Limitations

- The dataset covers six months, so it does not support a complete year-over-year comparison.
- Revenue is not profit; product costs and operating expenses are not included.
- Individual customer retention and lifetime value cannot be assessed reliably from the described fields.
- Descriptive patterns show what happened in the observed data; they do not establish why it happened.

## 5. Summary

The documented analysis identifies Hell's Kitchen as the leading store by revenue, Coffee as the leading category, Sustainably Grown Organic Lg as the highest-revenue product, and 10 AM as the peak revenue hour. Monday leads in revenue while Friday leads in transaction volume.

