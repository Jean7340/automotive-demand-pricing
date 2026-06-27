# 🚗 Automotive Demand, Pricing & Competitive Strategy

> A business analytics project that estimates vehicle demand, evaluates price elasticity, analyzes competitive dynamics, and develops executive pricing recommendations for the European automotive market.

---

## Business Problem

Pricing is one of the most important strategic decisions in the automotive industry.

This project addresses three key business questions:

- How sensitive is vehicle demand to price?
- How do competitors influence pricing power?
- What pricing strategy should management adopt?

Using econometric demand modeling and business analytics, this project translates data into actionable pricing recommendations.

---

# Analytical Workflow

```text
Raw Vehicle Data
        │
        ▼
01 Data Audit
        │
        ▼
02 Market Overview
        │
        ▼
03 Demand Estimation
        │
        ▼
04 Price Elasticity Analysis
        │
        ▼
05 Competitive Dynamics
        │
        ▼
06 Executive Pricing Strategy
```

---

# Key Findings

### Demand

- Estimated price elasticity ≈ **-1.37**
- Vehicle demand is highly price-sensitive.

### Competition

- Higher competitor prices are associated with higher expected demand.
- Competition intensity influences pricing power, although the number of competitors alone has limited explanatory power after controlling for product and market characteristics.

### Revenue

- Broad price increases are unlikely to maximize revenue.
- Moderate price reductions may improve revenue under the estimated elasticity.

### Executive Recommendation

Rather than applying a uniform pricing strategy across the portfolio:

- Maintain prices in highly competitive segments.
- Consider selective price increases for differentiated or premium products.
- Use demand elasticity and competitive positioning together when making pricing decisions.

---

# Repository Structure

```text
automotive-demand-pricing-strategy/

│
├── data/
│   ├── cars.csv
│   └── variables.xlsx
│
├── notebooks/
│   ├── 01_data_audit.ipynb
│   ├── 02_market_overview.ipynb
│   ├── 03_demand_estimation.ipynb
│   ├── 04_price_elasticity.ipynb
│   ├── 05_competitive_dynamics.ipynb
│   └── 06_executive_pricing_strategy.ipynb
│
├── images/
│
└── README.md
```

---

# Project Overview

| Notebook | Business Question |
|----------|-------------------|
| **01 Data Audit** | Can the dataset support pricing analysis? |
| **02 Market Overview** | How is the European automotive market structured? |
| **03 Demand Estimation** | How sensitive is demand to vehicle prices? |
| **04 Price Elasticity Analysis** | What are the revenue implications of different pricing decisions? |
| **05 Competitive Dynamics** | How do competitors affect pricing power and demand? |
| **06 Executive Pricing Strategy** | What pricing strategy should management adopt? |

---

# Methods

This project combines business analytics with econometric modeling.

Analytical techniques include:

- Exploratory Data Analysis (EDA)
- Demand Estimation (Log-Log OLS)
- Fixed Effects Modeling
- Price Elasticity Analysis
- Competitive Analysis
- Scenario Simulation
- Executive Decision Support

---

# Business Recommendations

Based on the analytical results:

- Avoid broad portfolio-wide price increases.
- Maintain prices in highly competitive markets.
- Implement selective price increases where competitive pressure is weaker.
- Estimate segment-level elasticities before introducing dynamic pricing strategies.

---

# Tools

- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Jupyter Notebook

---

# Skills Demonstrated

- Business Analytics
- Pricing Analytics
- Revenue Optimization
- Demand Modeling
- Competitive Analysis
- Econometric Modeling
- Executive Communication
- Data Visualization
- Strategic Decision Support
