# Predictive Maintenance: BA476_Final_Project

## Overview
This project implements predictive maintenance strategies using machine learning to prevent machinery failures and optimize operations. By leveraging data-driven insights, the project demonstrates the potential to minimize downtime and improve reliability.

---

## Key Features
- **Dataset:**
  - Synthetic dataset with 10,000 data points and 14 features.
  - Features include air temperature, process temperature, rotational speed, torque, and tool wear.
- **Targets:**
  - **Binary Classification:** Predict machine failure (Yes/No).
  - **Multiclass Classification:** Identify failure types.
- **Techniques:**
  - Feature engineering to identify critical factors leading to failures.
  - Model evaluation to assess feature importance and prediction accuracy.

---

## Methodology

### Data Analysis
- Analyzed patterns and correlations in machine parameters related to failures.
- Visualized the relationships between features and machine conditions using tools like `matplotlib` and `seaborn`.

### Model Development
- Built and tested multiple machine learning models for binary and multiclass classification, including:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- Evaluated models using metrics such as:
  - Accuracy
  - Precision
  - Recall
  - F1-score

### Key Insights
- Identified specific features (e.g., tool wear and torque) as significant contributors to machine failures.
- Highlighted the value of predictive maintenance in reducing downtime and increasing operational efficiency.

---

## Results
- Achieved high accuracy in predicting machine failures and identifying failure types.
- Delivered actionable insights for improving machinery reliability and efficiency.

---

## Future Directions
- Integrate real-time sensor data for continuous monitoring and prediction.
- Explore advanced techniques such as deep learning (e.g., LSTMs) for enhanced predictive performance.
- Extend analysis to other industrial datasets for broader applicability.

---

## Tools and Technologies
- **Programming Language:** Python
- **Libraries and Frameworks:** Scikit-learn, Pandas, Matplotlib, Seaborn
- **Data Preprocessing:** NumPy, Scikit-learn
- **Model Evaluation:** Scikit-learn's metrics library

---
