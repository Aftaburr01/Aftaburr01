# Multi-Echelon Inventory Optimization

## Executive summary

A supply-chain analytics project focused on balancing inventory availability, working capital, supplier performance, and replenishment policy across a multi-vendor environment.

## Business problem

Inventory decisions require tradeoffs between service level, carrying cost, lead-time uncertainty, and capital tied up in stock. The project applies segmentation and inventory-policy concepts to identify where differentiated controls can create the most value.

## Data scale

- **126 active vendors**
- **5,543 invoices**
- **33.6 million units**
- **$321.9 million supplier spend**

## Analytical approach

The framework combines:

- **ABC analysis** to prioritize inventory by economic importance
- **XYZ analysis** to distinguish demand variability
- **Economic Order Quantity (EOQ)** concepts for order-size decisions
- **Stochastic safety-stock logic** for uncertainty and service protection
- Supplier lead-time and SLA analysis
- Vendor-managed inventory (VMI) opportunities
- Postponement and replenishment controls

## Strategic targets modeled in the project

The analysis was designed around ambitious improvement targets, including:

| KPI | Current-state reference | Improvement direction |
|---|---:|---:|
| Inventory turnover | 3.5x | ≥ 7.5x |
| Days inventory outstanding | 104 days | ≤ 48 days |
| A-item stockout rate | 8.5% | ≤ 0.5% |
| Carrying cost rate | 26.5% | ≤ 18% |

The project modeled an opportunity for **more than $35M in working-capital release** if the recommended inventory policies and operating controls could be executed successfully.

## Business recommendations

1. Apply differentiated policies by ABC/XYZ segment instead of one replenishment rule for all items.
2. Protect service levels on critical A-items while reducing excess inventory elsewhere.
3. Use supplier lead-time performance and variability as inputs to safety-stock decisions.
4. Evaluate VMI where supplier capability and demand visibility support it.
5. Use postponement where delayed product differentiation can reduce inventory risk.
6. Establish KPI governance connecting inventory policy to cash, service, and supplier performance.

## Technology

Python · pandas · NumPy · supply-chain analytics · statistical inventory methods · business intelligence

## Portfolio value

This project demonstrates how analytics can connect operational policy to executive-level questions around **service, working capital, supplier performance, and inventory productivity**.

## Limitations & next steps

The modeled targets represent analytical improvement objectives rather than guaranteed realized savings. Future work would validate policies against additional demand history, supplier constraints, promotion effects, network-level dependencies, and scenario simulations.
