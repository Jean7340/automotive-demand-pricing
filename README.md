# 🚗 Automotive Demand & Pricing Strategy

> Estimating demand and translating pricing analytics into pricing decisions using panel data from the European automotive market.

---

![Workflow](figures/workflow.png)

---

# Project Overview

Pricing decisions are among the most important strategic levers in the automotive industry.

However, increasing prices does not always increase revenue. Manufacturers must understand:

- How sensitive customers are to price
- Which product attributes drive demand
- How competitors influence purchasing decisions
- What pricing strategy maximizes revenue

This project develops an end-to-end pricing analytics workflow using panel data covering the European automobile market.

---

# Business Questions

This project answers five business questions.

1. What factors drive vehicle demand?

2. How price-sensitive is the market?

3. How does competition affect demand?

4. What happens if prices change?

5. What pricing strategy should management adopt?

---

# Dataset

European Automobile Market

Observation level

Vehicle × Market × Year

11,431 observations

54 variables

Main information includes

- Product attributes
- Vehicle prices
- Competitor information
- Macroeconomic indicators
- Vehicle sales

---

# Analytical Workflow

Business Understanding

↓

Market Understanding

↓

Demand Estimation

↓

Elasticity Analysis

↓

Pricing Simulation

↓

Management Recommendation

---

# Executive Dashboard

(这里放最终Dashboard图片)

---

# Key Findings

## Finding 1

Vehicle demand is price elastic.

Estimated price elasticity:

**-1.37**

This implies that a 1% increase in price is associated with approximately a 1.37% decrease in demand.

---

## Finding 2

Broad price increases reduce revenue.

Pricing simulation suggests that:

| Price Change | Revenue Change |
|--------------|---------------|
| -10% | +2.3% |
| -5% | +1.5% |
| +5% | -2.2% |
| +10% | -5.1% |

---

## Finding 3

Competition matters.

Relative competitive positioning significantly influences demand, while simply having more competitors does not necessarily reduce sales after controlling for other factors.

---

# Business Recommendations

Based on the estimated demand model,

✓ Avoid broad portfolio-wide price increases.

✓ Evaluate targeted promotional pricing.

✓ Continuously monitor competitor pricing.

✓ Differentiate pricing across market segments.

---

# Repository Structure

```
notebooks/

01_data_audit

02_market_understanding

03_demand_estimation

04_pricing_analysis

05_competition_analysis

06_executive_summary
```

---

# Skills Demonstrated

- Pricing Analytics

- Econometrics

- Panel Data Modeling

- Demand Estimation

- Business Analytics

- Pricing Strategy

- Executive Communication

---

# Tech Stack

Python

Pandas

Statsmodels

NumPy

Matplotlib

Jupyter Notebook

---

# Future Improvements

- Customer-level discrete choice model

- Profit optimization

- Dynamic pricing

- Interactive dashboard
