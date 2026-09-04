# Food Delivery Time Prediction

## Executive summary

A predictive analytics project focused on understanding and forecasting delivery time so operations teams can improve ETA accuracy, fleet matching, order planning, and customer experience.

## Business problem

Delivery-time variation affects customer expectations, route planning, labor productivity, and service performance. The objective was to determine which operational and geographic factors were useful for prediction and compare multiple machine-learning approaches.

## Data & preparation

- **45,593 completed orders** analyzed
- Reviewed data quality and removed **3,640 records with zero coordinates** before geographic feature engineering
- Engineered distance using the Haversine method
- Added city/hub, order category, courier characteristics, and vehicle-modality features

## Modeling

Models compared:

- Linear Regression
- Random Forest
- Gradient Boosting
- Multi-Layer Perceptron (MLP)

### Best observed model

**Gradient Boosting** produced the strongest performance in the project:

| Metric | Result |
|---|---:|
| MAE | 5.65 minutes |
| RMSE | 7.20 minutes |
| R² | 0.406 |
| Inference latency | 3 ms |

## Business interpretation

The model was evaluated not only for predictive performance, but for how the output could support operating decisions. Recommended applications included:

1. **ETA buffering** — use predicted travel time to improve customer-facing delivery expectations.
2. **Fleet matching** — incorporate vehicle modality and operating context into dispatch decisions.
3. **Order stacking controls** — use predicted delivery impact when evaluating additional orders.
4. **Operational testing** — use A/B testing to validate changes before broad rollout.

## Decision framework

**Business question → data quality → feature engineering → model comparison → operational interpretation → controlled rollout**

## Technology

Python · pandas · NumPy · scikit-learn · machine learning · geospatial feature engineering · data visualization

## Portfolio value

This project demonstrates the ability to move beyond model building and connect predictive analytics to transportation and last-mile operating decisions.

## Limitations & next steps

The model explains a meaningful portion of delivery-time variation but does not capture every operational factor. Future work would include additional real-time dispatch variables, weather/traffic context where available, model monitoring, and production-style deployment.
