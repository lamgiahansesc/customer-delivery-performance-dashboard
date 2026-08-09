# Customer Delivery Performance & OTDS/OTDC Dashboard

## Objective
Portfolio project aligned to a Supply Chain internship focused on customer-delivery reporting, daily operational reporting, and on-time performance.

## Business questions
- Are shipments meeting the OTDS target of 96.5%?
- Are customer deliveries meeting the OTDC target of 98%?
- Which regions, products, and delay reasons drive service failures?
- Which late orders require planner follow-up?

## Files
- `Customer_Delivery_Performance_Dashboard.xlsx`: raw data, KPI dashboard, exception report, and data dictionary.
- `customer_delivery_orders.csv`: Power BI-ready synthetic source data.
- `DAX_Measures.txt`: recommended measures for a Power BI version.

## KPI definitions used in this simulation
- **OTDS** = orders where Actual Ship Date <= Scheduled Ship Date / total orders.
- **OTDC** = orders where Actual Delivery Date <= Requested Delivery Date / total orders.

These definitions are a portfolio simulation based on the wording of the supplied job description. Real company definitions can differ and should be confirmed in an interview/onboarding context.

## Recommended Power BI pages
1. Executive Delivery Performance — OTDS, OTDC, total orders, late deliveries, trend vs target.
2. Root-Cause Analysis — performance by product/region/customer and delay reason.
3. Exception Management — late/at-risk order table for planner follow-up.

## CV bullets
- Built a customer-delivery performance dashboard using 3,000 simulated orders, calculating OTDS and OTDC against 96.5% and 98% targets and highlighting service gaps by region, product, and delay reason.
- Developed an exception-management report identifying late customer deliveries and prioritizing orders for planner follow-up, converting order-level data into actionable daily reporting.
