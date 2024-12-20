# Supply Chain Analysis and Forecasting in US Supply Chains

This project delves into the analysis and forecasting of supply chain performance within the United States, leveraging a robust dataset on regional sales. The goal is to extract actionable insights and predict critical outcomes, aiding businesses in optimizing their supply chain strategies.

## Features of the Project

### 1. Data Analysis and Visualization
- Comprehensive dataset overview, including structure and summary statistics.
- Insights into product performance, sales channels, and revenue distribution using visualizations such as boxplots, histograms, and line graphs.
- Analysis of time-series trends to understand business growth over time.

### 2. Data Preprocessing
- Cleaning and preparation of data for modeling.
- Handling of date columns and feature engineering to enhance model performance.

### 3. Predictive Modeling
- Implementation of machine learning models to classify and forecast supply chain outcomes:
  - **Random Forest Classifier**
  - **Logistic Regression**
  - **Support Vector Classifier**
- Comparative analysis of model performance using accuracy scores and visual plots.

### 4. Business Impacts
- **Enhanced Decision-Making**: Provides a data-driven approach to identify high-performing products and optimize sales strategies.
- **Revenue Optimization**: Insights into order quantities, discount strategies, and sales channel performance for increased profitability.
- **Trend Analysis**: Evaluates growth trends to inform strategic planning and resource allocation.
- **Risk Mitigation**: Predictive modeling aids in forecasting potential supply chain disruptions and managing risks effectively.

## Results

### Random Forest Classifier
```plaintext
               precision    recall  f1-score   support

           0       1.00      1.00      1.00       767
           1       1.00      1.00      1.00       832

    accuracy                           1.00      1599
   macro avg       1.00      1.00      1.00      1599
weighted avg       1.00      1.00      1.00      1599

Random Forest Accuracy: 1.00
