# Retail Market Basket Analysis

## Executive summary

An association-rule mining project designed to identify products that frequently appear together in customer transactions and translate those relationships into merchandising, bundling, and promotional opportunities.

## Business problem

Retailers can use transaction-level purchasing behavior to understand product affinity. The objective was to identify meaningful product relationships and prioritize rules with strong association and business relevance.

## Data & analysis

- **7,501 transactions** analyzed
- **119 unique products/items**
- **160 association rules** evaluated
- Apriori algorithm used for frequent-itemset and rule generation
- Minimum support: **1%**
- Minimum confidence: **20%**
- Rules ranked using **lift**

## Key finding

The strongest identified rule was **herb & pepper → ground beef**, with a **3.29 lift** in the analysis.

Lift was used to distinguish meaningful product affinity from relationships that could occur simply because individual products are popular.

## Business recommendations

### 1. Build targeted bundles
Test complementary-product bundles around high-lift relationships rather than relying only on broad promotions.

### 2. Improve shelf placement
Evaluate adjacent or strategically positioned placement for products with strong purchasing affinity.

### 3. Personalize promotions
Use high-confidence/high-lift relationships to inform targeted offers where customer-level data and appropriate controls are available.

### 4. Pilot before scaling
Test recommendations in **2–3 stores** first, measure incremental performance, and expand only when results support the business case.

## Decision framework

**Transaction data → frequent itemsets → association rules → support/confidence/lift → merchandising hypothesis → controlled pilot → measured business impact**

## Technology

Python · pandas · Apriori · association-rule mining · support · confidence · lift · data visualization

## Portfolio value

This project demonstrates the ability to translate machine-learning/data-mining techniques into practical retail decisions rather than treating analytics as a purely technical exercise.

## Limitations & next steps

Association does not establish causation. Recommended next steps include controlled experiments, margin analysis, inventory availability checks, and customer-segment testing before operational rollout.
