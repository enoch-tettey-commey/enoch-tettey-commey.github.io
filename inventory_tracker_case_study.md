# Inventory and Stock Movement Tracker

**Status:** Completed portfolio demonstration using fictional data. This is not a record from a former employer.

## Business question
How can a small operations team track receipts, issues, returns, and closing stock consistently?

## Workbook
- `sample_inventory_stock_tracker.xlsx` contains a Stock Movements sheet and a formula-driven Stock Summary.
- Closing quantity is calculated as opening quantity + receipts − issues + returns.
- Closing stock value is closing quantity × unit cost.
- Filters and frozen headers support review of movement records.

## Quality checks to apply
1. Confirm every movement has a date, SKU, type, quantity, and reference.
2. Investigate negative closing balances or unexpected variances.
3. Compare the calculated balance with a physical count before making stock adjustments.
4. Keep source documents and approvals for audit trail.

## Limitations
All rows are synthetic examples for demonstration. The workbook is a starter template; adapt movement types and controls to the actual business process before operational use.
