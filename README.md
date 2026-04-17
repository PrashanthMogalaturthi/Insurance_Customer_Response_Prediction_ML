📊 Insurance Customer Response Prediction
🚀 Project Overview

This project focuses on predicting whether a customer will respond to an insurance offer using machine learning techniques. It combines data analysis, feature engineering, predictive modeling, and dashboard visualization to generate actionable business insights.

The solution helps insurance companies:

Identify high-potential customers
Improve marketing campaign efficiency
Reduce acquisition costs

📁 Project Structure
├── code/
│   └── Insurance_Customer_Prediction.ipynb
├── data/
│   └── dataset.csv (or source link)
├── dashboard/
│   └── Insurance_dashboard.pbix
├── documentation/
│   └── Project_Report.pdf
└── README.md
📌 Problem Statement

Insurance companies often struggle to identify which customers are likely to respond to marketing campaigns. This project builds a classification model to predict customer responses and optimize targeting strategies.

🧠 Key Features of the Project
🔍 Exploratory Data Analysis (EDA)
Distribution analysis of customer demographics
Correlation heatmaps to identify important features
Insights into customer behavior patterns
🛠️ Data Preprocessing
Handling missing values
Encoding categorical variables
Feature scaling
Addressing class imbalance using SMOTE
🤖 Machine Learning Models

Implemented and compared multiple models:

Logistic Regression
Random Forest
XGBoost
LightGBM
⚙️ Model Optimization
Hyperparameter tuning using GridSearchCV
Evaluation using:
F1 Score
Precision & Recall
AUPRC (Area Under Precision-Recall Curve)

📈 Model Performance
Achieved approximately:
F1 Score: ~0.60
AUPRC: ~0.59
Focused on improving recall for better identification of positive responders

📊 Power BI Dashboard

The project includes an interactive dashboard built using Power BI to visualize:

Customer segmentation
Response trends
Feature impact on predictions
Business insights for decision-making

🧰 Tech Stack
Programming & Libraries
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Machine Learning
Random Forest
XGBoost
LightGBM
Visualization
Power BI
📷 Sample Insights
Customers with certain demographic patterns show higher response rates
Marketing efforts can be optimized by targeting specific segments
Model helps prioritize high-probability leads

🎯 Business Impact
Improves campaign ROI
Reduces unnecessary outreach costs
Enables data-driven decision making
🔮 Future Improvements
Improve recall score (>75%) using advanced techniques:
Threshold tuning
Ensemble stacking
Cost-sensitive learning
Deploy model using Flask/Streamlit
Integrate real-time prediction pipeline


👨‍💻 Author

Prashanth Mogalaturthi
Aspiring Data Scientist | Machine Learning Enthusiast
