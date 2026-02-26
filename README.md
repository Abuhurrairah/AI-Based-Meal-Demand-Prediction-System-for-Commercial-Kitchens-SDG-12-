# AI-Based-Meal-Demand-Prediction-System-for-Commercial-Kitchens-SDG-12-

**Run the jupyter notebook first to create the model**

Goal: Reduce food waste by forecasting meal demand to support better production planning

Real-world Focus: Built for any restaurant to upload and use their own data (not limited to one Kaggle dataset)

Core Workflow: Upload data → Clean/Standardize → Train model → Predict demand → Plan production

Key Features

Dataset Template (CSV): Downloadable template showing the correct dataset structure

Dataset Generator + Quality Report:

Accepts messy raw POS/export CSV files

Maps columns automatically, fills missing values safely

Shows preview + report (mapped columns, missing columns added, warnings, assumptions)

Model Training & Evaluation:

Trains a forecasting model (Random Forest Regressor + preprocessing pipeline)

Automatically reports MAE, RMSE, R²

Shows Actual vs Predicted plot + feature importance (if available)

Single Prediction: Interactive web form for predicting demand for a specific item/week with production suggestion

Safety Buffer Recommendation: Suggests a buffer % based on demand variability to reduce stock-out risk

Batch Forecasting (CSV): Upload batch file → download output CSV with predicted orders + suggested production

Tech Stack

Python, Flask

Pandas, NumPy

Scikit-learn, Joblib

Matplotlib

HTML/CSS/Bootstrap (UI)

Impact

Supports SDG 12: Responsible Consumption & Production

Helps kitchens reduce overproduction, lower costs, and improve sustainability
