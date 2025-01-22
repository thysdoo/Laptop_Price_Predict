# Laptop_Price_Predict


**Objective**:
Predict laptop prices (Price_euros) using the laptop_price_clean.csv dataset.

**Contributions**:
- Exploratory Data Analysis (EDA):
Libraries used: Pandas, NumPy, Matplotlib, Seaborn.
Insights:
Target variable (Price_euros) has a strong left skew and 2.20% outliers. High-priced laptops (above 6099 euros) were excluded to prevent model distortion.
Key factors influencing price: Ram, Cpu_brand, Gpu_brand, Screen PPI, and Weight.
Company, TypeName, and OpSys also affect pricing, with Gaming laptops and Core i7 CPUs being significantly more expensive.

- Data Preprocessing:
Removed 29 duplicates, handled categorical variables via one-hot encoding, and normalized numerical features (Weight, Screen PPI).
Selected relevant features based on their impact on the target variable.

- Model Building and Evaluation:
Trained and evaluated three regression models using RMSE, MAE, and R².
Best model: Gradient Boosting with an RMSE of 150 euros and an R² of 0.90.

- Evaluation and Insights:
Key price drivers: Ram, SSD, Screen PPI, Cpu_brand.
Provided insights for strategic pricing and inventory management based on model results.
 
- Visualization and Reporting:
Created visualizations in Jupyter Notebook for model performance and feature importance.
Delivered a concise report with methodology, findings, and recommendations.

**Tools Used**:
Python (Jupyter Notebook)
Machine Learning (Custom-built regression models)
