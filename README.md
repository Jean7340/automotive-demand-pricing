# Automotive Demand Estimation & Pricing Strategy

> A business analytics project that estimates vehicle demand, evaluates price elasticity, analyzes competitive dynamics, and develops executive pricing recommendations for the European automotive market.
>
> <p align="center"> 
  <img src="images/Hero%20Figure.png" alt="Hero Figure" width="1000"> 
  </p> 
  
  --- 
  
  ## Business Context 
  
  Pricing decisions are among the most important strategic levers in the automotive industry. Setting prices too high may reduce demand and market share, while pricing too low sacrifices revenue and profitability. 
  
  Manufacturers must balance **consumer demand, competitive positioning, and product differentiation** when making pricing decisions. 
  
  This project applies demand estimation, price elasticity analysis, and competitive modeling to translate historical market data into actionable pricing recommendations. 
  
  The analysis focuses on three business questions: 
  
  - How price-sensitive is vehicle demand?
  - How do competitor prices influence demand?
  - Which pricing strategy is most likely to maximize revenue?

  --- 
  
  ### Key Findings

| Finding | Result | Business Impact |
|---------|--------|-----------------|
| **Own-price elasticity** | **−1.37** | Broad price increases are unlikely to maximize revenue. |
| **Competitor price effect** | **Positive** | Higher competitor prices increase expected demand, highlighting the need for competitive pricing strategies. |
| **Market heterogeneity** | **Significant** | Pricing strategies should be tailored by market segment rather than applied uniformly. |
| **Scenario simulation** | **Selective discounts perform best** | Avoid uniform pricing strategies; optimize pricing based on market conditions and demand response. |
  
  --- 
  
  ## Analytical Workflow

```text
         Raw Market Data
                │
                ▼
            Data Audit
                │
                ▼
    Market Structure Analysis
                │
                ▼
       Demand Estimation
                │
                ▼
   Price Elasticity Analysis
                │
                ▼
      Competition Analysis
                │
                ▼
       Pricing Simulation
                │
                ▼
   Executive Recommendation
```

| Step | Business Objective | Deliverable |
|------|--------------------|-------------|
| **[01 Data Audit](notebooks/01_data_audit.ipynb)** | Assess data quality, missing values, variable distributions, and modeling readiness. | Data Quality Report |
| **[02 Market Overview](notebooks/02_market_overview.ipynb)** | Understand market structure, pricing landscape, brand positioning, and vehicle segmentation. | Market Insights Dashboard |
| **[03 Demand Estimation](notebooks/03_demand_estimation.ipynb)** | Estimate vehicle demand using log-log regression while controlling for vehicle, brand, market, and year effects. | Demand Curve & Regression Results |
| **[04 Price Elasticity Analysis](notebooks/04_price_elasticity.ipynb)** | Estimate own-price elasticity and evaluate demand and revenue under alternative pricing scenarios. | Elasticity Estimates & Revenue Simulation |
| **[05 Competition Dynamics](notebooks/05_competition_dynamics.ipynb)** | Measure competitor price effects and assess how competitive intensity influences expected demand. | Competitive Response Analysis |
| **[06 Pricing Recommendations](notebooks/06_pricing_recommendations.ipynb)** | Translate analytical findings into pricing recommendations for business decision makers. | Pricing Decision Framework |

---

## Analytical Highlights

The figures below summarize the key analytical findings from the project.

<table>
<tr>
<td align="center" width="33%">

### Market Overview

<img src="images/Market%20Overview.png" width="320">

Brand positioning reveals clear differences in pricing and sales volume across manufacturers, highlighting the importance of segment-specific pricing strategies.

</td>

<td align="center" width="33%">

### Demand Elasticity

<img src="images/Elasticity%20%26%20Pricing%20Simulation.png" width="320">

Estimated own-price elasticity of **−1.37** indicates that vehicle demand is highly price-sensitive, making broad price increases unlikely to maximize revenue.

</td>

<td align="center" width="33%">

### Competition Dynamics

<img src="images/Competition%20Dynamics.png" width="320">

Higher competitor prices increase expected demand, suggesting meaningful substitution effects that should be incorporated into pricing decisions.

</td>

</tr>
</table>

---

## Methodology

**Tools**

Python · Pandas · NumPy · Statsmodels · Matplotlib

**Techniques**

- Data Quality Assessment
- Exploratory Data Analysis
- Demand Estimation
- Elasticity Analysis
- Competition Modeling
- Scenario Simulation

---

## Management Takeaways

Based on the estimated demand model and pricing simulations, the analysis suggests the following actions:

- **Avoid broad price increases.** The estimated price elasticity (−1.37) indicates that demand is highly price-sensitive, making across-the-board price increases likely to reduce revenue.

- **Evaluate targeted promotional pricing.** Revenue simulations suggest that moderate price reductions may improve revenue for price-sensitive vehicle segments.

- **Incorporate competitor pricing into pricing decisions.** Higher competitor prices increase expected demand, highlighting the importance of competitive positioning.

- **Adopt segment-specific pricing strategies.** Vehicle classes exhibit different demand responses, suggesting that pricing decisions should be tailored rather than uniformly applied.

---

## Repository Structure

```text
pricing-analytics/
├── data/
├── images/
├── notebooks/
│   ├── 01_data_audit.ipynb
│   ├── 02_market_overview.ipynb
│   ├── 03_demand_estimation.ipynb
│   ├── 04_price_elasticity.ipynb
│   ├── 05_competition_dynamics.ipynb
│   └── 06_pricing_recommendations.ipynb
└── README.md
```

