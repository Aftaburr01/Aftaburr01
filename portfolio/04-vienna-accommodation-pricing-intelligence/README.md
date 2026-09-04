# Vienna Accommodation Pricing Intelligence

## Business Problem

How can accommodation pricing be evaluated in relation to **location and property characteristics** to support better pricing intelligence and market decisions?

This project analyzes accommodation observations using statistical modeling and visualization to explore how pricing varies with distance, property characteristics, and neighborhood grouping.

## Data & Approach

The project uses a Python analytics workflow built around:

- pandas and NumPy for data preparation and analysis
- statistical modeling with statsmodels
- geographic/location variables
- neighborhood grouping
- property star ratings
- interactive visualization with Plotly
- model evaluation and interpretation

The analysis includes nonlinear distance effects by incorporating both distance and squared distance terms.

## Modeling

The primary statistical model evaluates log-transformed price as a function of:

- distance
- distance squared
- property stars
- grouped neighborhood

The model achieved an **adjusted R² of 55.6%** with an **RMSE of €32.18** within the project analysis.

The project also examines actual-versus-expected pricing to identify observations that may warrant additional investigation.

## Business Interpretation

The analysis demonstrates how statistical modeling can move a pricing discussion beyond simple averages by separating the influence of:

- location
- property characteristics
- neighborhood effects
- nonlinear distance relationships

This type of analysis can support pricing review, market benchmarking, exception identification, and further investigation of potentially under- or over-priced properties.

## Visualization

The project uses Plotly for interactive analysis and geographic/map-oriented exploration where applicable.

## Technology

**Python · pandas · NumPy · statsmodels · Plotly · statistical modeling · data visualization**

## Important Data Note

Any location values generated or supplemented for analysis should be clearly treated as **synthetic/illustrative** rather than representing verified real-world coordinates. The project does not claim that synthetic coordinates are actual property locations.

## Limitations & Next Steps

Potential improvements include:

- additional property attributes
- richer time-series pricing data
- seasonal effects
- demand/occupancy variables
- larger geographic coverage
- external market benchmarks
- validation against out-of-sample observations

## Portfolio Relevance

This project demonstrates my ability to combine **Python, statistical analysis, visualization, and business interpretation**. It complements my operations and supply-chain analytics work by showing that the same analytical discipline can be applied to pricing and market intelligence.

---

*Analytics project documented as part of my professional portfolio.*
