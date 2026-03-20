# KONE ML Platform — Composable ML Platform

Enterprise Analytics and Forecasting | Dwarakanath K Dinesh | MSc Big Data Analytics | AIMIT

## Deploy to Vercel in 5 minutes

### Step 1 — Upload to GitHub
1. Create new GitHub repository: `kone-ml-platform`
2. Upload all these files to the repository

### Step 2 — Deploy to Vercel
1. Go to vercel.com → Sign up free with GitHub
2. Click "New Project"
3. Import your `kone-ml-platform` repository
4. Click Deploy

### Step 3 — Add Databricks credentials
In Vercel dashboard → Settings → Environment Variables, add:

| Variable | Value |
|---|---|
| REACT_APP_DATABRICKS_HOST | https://dbc-ff69c8c1-012b.cloud.databricks.com |
| REACT_APP_DATABRICKS_TOKEN | your_token_here |
| REACT_APP_WAREHOUSE_ID | your_warehouse_id |

### Step 4 — Redeploy
After adding environment variables → Deployments → Redeploy

Your app will be live at: https://kone-ml-platform.vercel.app

## How to get SQL Warehouse ID
1. Databricks → SQL Warehouses
2. Click your warehouse
3. Copy the ID from the URL or Connection Details

## Features
- Drag and drop pipeline builder
- Real-time Databricks Delta table data
- 7 ML algorithms: LSTM, XGBoost, Random Forest, One-Class SVM, Isolation Forest, Linear Regression, ARIMA
- Algorithm mismatch suggestions
- Charts: Line, Bar, Comparison
- Conclusions per algorithm
- Download results as CSV
- Works in demo mode without Databricks credentials
