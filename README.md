# Telecom Customer Churn Analysis 📊

This notebook explores the relationship between customer churn and various service-related features such as `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, and more.

## 📈 Visual Analysis

We created grouped countplots (using Seaborn) to visualize churn behavior across multiple service features. Each subplot represents the count of customers who churned (`Yes`) vs those who did not (`No`) for a specific service feature.

### Key Observations:
- **Higher churn** is observed among customers with:
  - **Fiber optic** internet service.
  - No **OnlineSecurity**, **TechSupport**, or **DeviceProtection**.
- **Lower churn** is seen in customers who:
  - Have multiple active services.
  - Do not use internet-based services at all (e.g., labeled as "No internet service").

These insights help identify the customer segments most at risk of churning, aiding in better retention strategies.

## 📁 Files
- `EDA.ipynb`: Jupyter Notebook with data visualization code.

## 🔧 Tools Used
- Python 🐍
- Pandas
- Seaborn
- Matplotlib
