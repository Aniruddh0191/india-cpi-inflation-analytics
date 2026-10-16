# Methodology

## Data preparation
- Audited sectors, years, months, types and missing values.
- Standardized month labels and created a monthly date field.
- Converted `NA`, `-` and invalid numeric entries to nulls rather than zero.
- Preserved structurally missing observations and documented the missing-value audit.

## Data modelling
- Created a calendar table and linked it to the cleaned CPI date.
- Used Power Pivot measures for reusable time-based comparisons.

## Analysis plan
- **Q1:** May 2023 broad-category comparison using normalized analytical shares.
- **Q2:** YoY CPI trend from 2017 through the available 2023 period.
- **Q3:** Food CPI monthly trend for June 2022–May 2023 and category-level changes.
- **Q4:** Inflation-rate movement around the March 2020 COVID onset milestone, comparing February–March and March–June changes in percentage points.
- **Q5:** Monthly imported Indian Basket crude-oil price changes compared with CPI category monthly movements.

## Limitations
Normalized shares are not official expenditure weights; 2023 is partial; Essential Services is an analytical unweighted composite; correlation does not establish causation.
