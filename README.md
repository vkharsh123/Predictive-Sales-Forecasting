# Predictive-Sales-Forecasting
Business Objective
This project deploys an advanced machine learning pipeline to analyze historical transaction datasets, identify recurring sales patterns, and forecast future demand. By accurately predicting item-level sales across multiple restaurant branches, this model provides actionable insights to optimize inventory workflows, reduce operational bottlenecks, and tighten budget forecasting.

Data Architecture & Processing
The analysis aggregates disparate business data into a single, high-fidelity tracking model:
Data Ingestion: Imported and processed raw CSV datasets containing daily sales, item specifications (including kcal and cost), and restaurant branch details.
Data Cleaning: Standardized date formats into datetime objects for rigorous time-series evaluation.
Data Merging: Engineered a unified operational dataset by merging sales data with item and restaurant identifiers to seamlessly map prices, item counts, item names, and store names.
Feature Engineering: Extracted granular time-based features, such as specific weekdays, to analyze day-to-day operational fluctuations.

Exploratory Data Analysis (EDA)
Conducted comprehensive EDA to isolate key business trends:
Examined overall date-wise sales to establish baseline operational patterns.
Analyzed sales fluctuations across different days of the week, months, and averaged quarters to identify seasonal variance.
Benchmarked the financial performance of different restaurant branches, tracking high-volume sales locations across varying timeframes.
<img width="1527" height="859" alt="sales co wise" src="https://github.com/user-attachments/assets/bf10539d-bb5f-479e-8dfb-2307a7e22314" />
<img width="1555" height="578" alt="sales trend" src="https://github.com/user-attachments/assets/b845de64-9b41-4722-b899-c5d2b3f961ce" />



Technical & Machine Learning Stack
Data Management: Python, Pandas, NumPy.
Data Visualization: Seaborn, Matplotlib.
Predictive Modeling: Scikit-Learn (Linear Regression, Random Forest), XGBoost.
Deep Learning (Time-Series): TensorFlow / Keras (LSTM networks, Sequential models).
Evaluation Metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared (R2), Mean Absolute Percentage Error (MAPE).
