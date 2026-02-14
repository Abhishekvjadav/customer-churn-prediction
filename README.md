# Customer Churn Prediction using Machine Learning

## Project Overview
Built a machine learning model to predict customer churn with **79.84% accuracy**, 
analyzing 7,043 telecom customers to identify at-risk users and provide actionable 
retention strategies.

## Business Problem
- **26.5% churn rate** costing company revenue
- Need to identify at-risk customers proactively
- Reduce 1,869 annual customer losses

## Technical Approach
- **Language:** Python (Google Colab)
- **Libraries:** Pandas, Scikit-learn, Matplotlib, Seaborn
- **Model:** Random Forest Classifier
- **Metrics:** Accuracy, Precision, Recall, F1-score

## Key Findings

### Model Performance
- **Accuracy:** 79.84%
- **Precision (Churned):** 66%
- **Recall (Churned):** 49%

### Top Churn Predictors
1. **MonthlyCharges** (0.177 importance) - Higher bills = higher risk
2. **Tenure** (0.175 importance) - New customers churn 2x more
3. **TotalCharges** (0.168 importance) - Customer lifetime value indicator

### Critical Business Insights
- Churned customers avg **18 months** tenure vs **37.6 months** for retained
- **Month-to-month contracts** have highest churn risk
- **First 18 months** are critical retention period

## Business Recommendations
1. **Contract Strategy:** Incentivize longer-term contracts
2. **Onboarding Program:** Focus on first 18 months
3. **Proactive Monitoring:** Track high MonthlyCharges + low tenure customers
4. **Targeted Campaigns:** Use model to predict 1,869 at-risk customers

## Files
- `churn_prediction.ipynb` - Full analysis notebook
- `churn_distribution.png` - Churn overview
- `feature_importance.png` - ML feature rankings
- `churn_by_contract.png` - Contract analysis

## Connect
- Email: abhishekjadav668@gmail.com
