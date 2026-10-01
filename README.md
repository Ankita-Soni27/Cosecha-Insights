# Olive Oil Sales & Supply Chain Analytics

A Power BI portfolio project exploring sales, purchasing, inventory, supplier relationships, and batch-level outcomes for an olive-oil business.

## Dashboard

Open `dashboard/Sales_Dashboard.pbix` in Power BI Desktop. Add dashboard screenshots or a compressed GIF under `images/` or `demo/` before publishing.

## Business questions

- How do sales and revenue vary across products and categories?
- What purchase costs and supplier relationships support each product?
- How much product is sold, lost, or wasted at batch level?
- Which products or batches may need inventory or operational attention?
- How do sales outcomes compare with purchase costs?

## Repository contents

- `data/batch_outcomes.csv` — batch quantities, status, waste, revenue, and cost outcomes
- `data/products.csv` — product attributes, pricing, and current stock indicators
- `data/purchases.csv` — purchase transactions, suppliers, quantities, and costs
- `data/suppliers.csv` — supplier reference information
- `data/supply_links.csv` — product-supplier links, prices, and lead times
- `dashboard/Sales_Dashboard.pbix` — Power BI report
- `data/DATA_DICTIONARY.md` — row counts and column inventory

## Tools

- Microsoft Power BI
- CSV datasets
- SQL (queries can be added under `sql/`)

## How to explore

1. Download or clone this repository.
2. Open `dashboard/Sales_Dashboard.pbix` in Power BI Desktop.
3. If prompted, update source paths to the CSV files in `data/`.
4. Refresh the model and explore the report.

## Before publishing publicly

Review the supplier reference data for personal or confidential information. The original animated demo was not included because its source file exceeds GitHub's standard 100 MB individual-file limit; add a compressed preview or use Git LFS / a GitHub Release for large media.
