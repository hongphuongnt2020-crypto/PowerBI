# Publish Power BI on GitHub

## Sales & Inventory Performance Dashboard

A 5-day Power BI portfolio project (October 13–17, 2026) demonstrating business analytics, Power Query, star-schema modeling, DAX, and interactive sales and inventory reports.

**Status:** In progress. Report files and synthetic data will be published as each milestone is completed.

### Business questions

- How are revenue, COGS, gross profit and gross margin changing over time?
- Which products and customers drive sales performance?
- How does sales growth compare year over year?
- What is current inventory value, turnover and days of inventory?
- Which items are slow-moving or require attention?

### Planned KPIs

| Sales | Inventory |
|---|---|
| Revenue | Stock Value |
| COGS | Inventory Turnover |
| Gross Profit | Days of Inventory |
| Gross Margin % | Stock Movement |
| YoY Revenue Growth % | Slow-moving Stock |

### Daily milestones

| Date | Workstream | GitHub Issue |
|---|---|---|
| Oct 13 | Project setup & sample data | [Day 1](../../issues/1) |
| Oct 14 | Power Query & data modeling | [Day 2](../../issues/2) |
| Oct 15 | DAX & sales dashboard | [Day 3](../../issues/3) |
| Oct 16 | Inventory dashboard & QA | [Day 4](../../issues/4) |
| Oct 17 | Publish and document portfolio | [Day 5](../../issues/5) |

### Planned repository structure

```text
PowerBI/
├── README.md
├── data/
│   ├── sales.csv
│   ├── inventory.csv
│   ├── products.csv
│   └── customers.csv
├── powerbi/
│   └── Sales_Inventory_Dashboard.pbix
├── dax/
│   └── measures.md
├── docs/
│   ├── data_dictionary.md
│   └── data_model.png
└── screenshots/
    ├── sales_dashboard.png
    └── inventory_dashboard.png
```

The folders and artifacts above are planned outputs, not all yet present.

### Data privacy

Only synthetic or properly anonymized datasets may be uploaded. Do not publish confidential company, customer, pricing or supplier information.

### Track progress

See the [GitHub Issues](../../issues) for detailed checklists, dates and completion criteria. Close each issue after validating its deliverable.
