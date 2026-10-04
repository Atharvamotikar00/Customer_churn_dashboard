# Customer Churn Analysis using XGBoost

Predictive model that identifies customers likely to discontinue a service.

## Structure
- `notebooks/customer_churn_xgboost.ipynb` – full analysis and XGBoost model
- `data/` – `customer_data.csv`, `churn_data.csv`, `historical_price_data.csv` (joined on `id`)
- `public/index.html` – "Which customers might leave?" report (deployed on Vercel)
- `vercel.json` – serves `public/` as a static site (data and notebook are not exposed)

