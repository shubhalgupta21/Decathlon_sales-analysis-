
# Decathlon India: Sales Performance Analysis

An interactive Excel dashboard built from 30,000 synthetic retail orders (Jan 2024 - Dec 2026).

## Objective
Understand sales, profit, discount and return performance, find what is driving the 2026 decline, and give managers clear actions to improve profit.

The dashboard answers three questions:
1. **What is happening?** Overall performance
2. **Why is it happening?** Drivers by product, place, customer and practice
3. **What should we do?** Insights, targets and an action plan

## Files
| File | Purpose |
|---|---|
| `Decathlon_Dashboard_3Part.xlsx` | Final interactive dashboard |
| `Decathlon_Synthetic_Data_30000.xlsx` | Original source data (input) |

## Dashboard structure
| Part | Content |
|---|---|
| Part 1: Overview | 8 KPI cards, monthly trend, yearly and quarterly sales |
| Part 2: Drivers | 12 charts: category, state, discount, returns, customer, channel, time |
| Part 3: Actions | Key insights, targets vs actual, profit what-if, action tracker |

## Key findings
- Sales are **₹36.7 Cr** with a **30.7%** margin, but **Jun-Dec 2026 sales are -31.7%** versus 2025 (order volume fell, not order value).
- Discounts cost **₹5.35 Cr (12.7% of gross sales)** and do not raise units per order. High-discount orders earn about 22% less profit per order.
- **8.1% of orders are returned** (₹2.99 Cr sales, about ₹92 L profit). About 57% of returns come from fixable causes: wrong item, defective product, late delivery.
- **Cycling** is 22% of sales; **Maharashtra** is 17% of sales. The average rating is only 3.0 / 5.

## Main recommendations
1. Investigate the June-2026 order drop (traffic, stock, outages, data capture).
2. Cap or redesign high discounts; pilot first.
3. Reduce operational returns (pick-pack checks, supplier QC, delivery SLAs).
4. Protect Cycling stock; use Maharashtra as a playbook for weaker states.
5. Redesign membership benefits to lift Premium and Elite spend.

## Tools
Excel, with formulas (SUMIFS, COUNTIFS, INDEX/MATCH), Data Validation dropdowns, conditional formatting and native charts.

## Definitions
- **Sales** = Final_Amount (after discount); **Gross sales** = before discount.
- **Net profit** = profit minus profit on returned orders.
- **Return rate** = returned orders / total orders.
