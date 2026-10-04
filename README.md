# Cost Optimization & Profitability Analysis

## Objective
Compare an old period and a new period for 4 products and find out why profit fell.

## Data
A small simulated dataset: 4 products (A, B, C, D), two periods (Old, New), with revenue and cost for each. The New-period figures for Products B, C and D are the same as the actual figures in my Budget vs. Actual project, so the two projects overlap and are not independent datasets.

## Key Findings
- Revenue rose ₹50,000 (₹3,90,000 to ₹4,40,000), but costs rose ₹1,00,000 (₹2,70,000 to ₹3,70,000).
- Profit fell ₹50,000 (₹1,20,000 to ₹70,000). Margin fell from 30.8% to 15.9%.
- Products B and C caused ₹45,000 of the ₹50,000 decline (90%).
- Product B: cost rose 61% while revenue rose 25%. Margin fell from 25.0% to 3.3%.
- Product C: cost rose 42% while revenue rose 6%. Margin fell from 33.3% to 10.5%.
- Product D held its profit at ₹30,000 and has the highest margin (35%+).

| Product | Old profit | New profit | Change |
|---|---|---|---|
| A | 30,000 | 25,000 | −5,000 |
| B | 30,000 | 5,000 | −25,000 |
| C | 30,000 | 10,000 | −20,000 |
| D | 30,000 | 30,000 | 0 |

## Method
Excel pivot tables and charts. Margin % is calculated as total profit ÷ total revenue (not an average of row margins).

## Recommendation
Investigate why costs grew much faster than revenue for Products B and C.

## Limitations
Small simulated dataset, two periods. The analysis shows where costs rose, not why (for example price changes vs. volume).

## Dashboard

![Cost Optimization Dashboard](./Cost%20Optimisation%20Dashboard.png)

## Files

- `cost_optimization.xlsx`
- `Cost Optimisation Dashboard.png`
