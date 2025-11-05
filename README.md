# procurement-risk-predicton
### Overview
The dataset contains key procurement-related features for various products and suppliers. It is designed to facilitate the classification of procurement items into Kraljic categories (Strategic, Leverage, Bottleneck, Non-critical) based on risk and profit impact.
### Problem Statement
Manually classifying procurement items into Kraljic categories is time-consuming and error-prone. This project aims to automate the classification using machine learning based on features like supply risk, profit impact, cost, and lead time, enabling faster and data-driven procurement decisions.
### Dataset 
Product_Name: Name or ID of the procurement item.

Supplier_Region: Geographic region of the supplier.

Lead_Time_Days: Number of days for supplier delivery.

Order_Volume_Units: Quantity of units ordered.

Cost_per_Unit: Cost of each unit.

Supply_Risk_Score: Quantitative measure of supply risk.

Profit_Impact_Score: Potential impact of the item on overall profit.

Environmental_Impact: Numeric value representing environmental effects.

Single_Source_Risk: Indicates if the item depends on a single supplier.

Kraljic_Category: Target variable; the procurement classification based on supply risk and profit impact.
### Tools & Technologies
Programming Language: Python

Data Manipulation & Analysis: pandas, numpy

Data Visualization: seaborn, matplotlib

Machine Learning Models: Random Forest, XGBoost, K-Nearest Neighbors (KNN), Gradient Boosting, Support Vector Machine (SVM), Gaussian Naive Bayes

Model Persistence: joblib (for saving and loading trained models)

Web Application: Streamlit (for creating interactive dashboard and prediction page)
### Key insights
Supplier Distribution: Most suppliers are concentrated in a few regions, indicating potential geographic dependency.

Risk vs Profit Impact: Items with high supply risk and high profit impact are mostly classified as Strategic, while low-risk, low-impact items fall under Non-critical.

Lead Time & Cost: Longer lead times and higher costs correlate with higher supply risk scores.

Single Source Dependency: Items sourced from a single supplier tend to have higher risk and are often in Bottleneck or Strategic categories.

Model Performance: Random Forest and XGBoost classifiers performed best in predicting Kraljic categories, enabling accurate automated classification.

Environmental Impact: While mostly numeric, higher environmental impact items tend to align with Strategic or Leverage categories, highlighting sustainability considerations in procurement decisions.
### Conclusion
 The project demonstrates that machine learning can effectively classify procurement items into Kraljic categories using features like supply risk, profit impact, cost, and lead time. This enables organizations to make faster, data-driven procurement decisions and efficiently manage supply chain risks.
### Contributing
 Contributions to this project are welcome! If you have ideas for improvements or additional insights, please open an issue or a pull request. Your contributions will be greatly appreciated.
### 📬 Contact Information

LinkedIn: Harshal Patil

Email: patilharshal7891@gmail.com