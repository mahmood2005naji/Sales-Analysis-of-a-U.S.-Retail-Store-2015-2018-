[README.md](https://github.com/user-attachments/files/34317771/README.md)
# Sales Analysis of a U.S. Retail Store (2015–2018)

A three-page Tableau dashboard and case study analysing four years of sales for a U.S. retail store.

**Live dashboard:** [View on Tableau Public](https://public.tableau.com/shared/P8DW87C4M?:display_count=n&:origin=viz_share_link)

## Dashboard preview

### Data description
![Data description](<Data description.png>)

### Sales Overview
![Sales Overview](<Sales Oveerview.png>)

### Profitability & Customers
![Profitability & Customers](<Profitability&Customers.png>)

## Summary

Sales grew 50% between 2015 and 2018, from $480K to $722K a year, but through more orders of lower value while new-customer acquisition almost stopped.

The dashboard helps the store's owner or sales manager decide where to put inventory, marketing and attention next year.

## Data

| Item | Value |
|---|---|
| Period | January 2015 – December 2018 |
| Order lines | 9,800 |
| Orders | 4,922 |
| Customers | 793 |
| States | 49 |
| Total sales | $2.26M |

The only metric is **Sales**, so every chart shows revenue, not profit. The data is clean (no duplicate rows, valid dates), apart from 32 product IDs with more than one name.

## Dashboard pages

1. **Data description:** scale, data quality, limits and the conclusion, before any chart.
2. **Sales Overview:** how much, when and where: sales by year, monthly sales, a state map and year / region / category filters.
3. **Profitability & Customers:** what and who drive sales: category, sub-category, region, segment and the top 10 customers.

## Key findings

- **Growth with a seasonal peak:** sales fell 4.3% in 2016, then rose 31% and 20% to $722K. The last quarter brings 38.5% of sales and February is the weakest month.
- **Volume, not value:** orders rose 75% (947 to 1,661) while the average order value fell 14% ($507 to $435).
- **Acquisition has stalled:** new customers fell from 589 in 2015 to 11 in 2018. The top 10% of customers make 30.9% of sales.
- **Products:** Technology leads with 36.6% of sales. Phones and Chairs make 28.8%. Office supplies are 60% of order lines at $119 each.
- **Regions and segments:** the West leads (31.4%) and the South lags (17.2%, down 32% in 2016). Consumers contribute 50.8%.

## Recommendations

1. Win new customers: set an acquisition target and track new customers per year.
2. Raise order value with bundles and offers that pair office supplies with higher-value items.
3. Investigate the South's low share and its 2016 drop.
4. Plan stock and campaigns around September, November and December, which bring 43% of sales.
5. Add profit and discount data to confirm the offers pay off.

## Limitations

- Sales is the only metric, so the names "Profit by Category" and "Profitability & Customers" promise more than the data holds.
- Four years give a thin base for forecasting.
- The 11 Burlington, VT rows carry a North Carolina postal code, so only state-level views are safe.

## Repository contents

| File | Description |
|---|---|
| `Sales Anlysis(2015-2018).twbx` | Tableau packaged workbook (open with Tableau Desktop or Tableau Public) |
| `Data description.png` | Dashboard page 1: data description |
| `Sales Oveerview.png` | Dashboard page 2: sales overview |
| `Profitability&Customers.png` | Dashboard page 3: profitability and customers |
| `train.csv` | Source dataset (9,800 order lines, 2015–2018) |
| `README.md` | This file |

## How to open

Download the `.twbx` file and open it with [Tableau Public](https://public.tableau.com/app/discover) (free) or Tableau Desktop.

## Tools

Tableau Public
