# Loan Repayment Dynamics and Overdue Behavior Analysis
More information: [ipynb](https://github.com/naumovakotya/loan-repayment-analysis/blob/main/tt_devim_da_NaumovaE.ipynb)

This project analyzes loan payment and delay behavior using real transactional data up to **December 8, 2022**. It explores trends in overdue payments, identifies behavioral patterns among borrowers, and derives insights for risk scoring and customer segmentation.

## 📌 Goals
- Understand how overdue behavior evolves over time
- Identify early warning signs of late payments
- Evaluate overall payment discipline across loans
- Suggest ideas for improving risk models and retention strategies

## 📊 Dataset Overview
The project uses three datasets:
- `orders.csv` — issued loans (one row per loan)
- `plan.csv` — scheduled payments
- `payments.csv` — actual payments

## 🛠 Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (PostgreSQL)
- Jupyter Notebook

## 🔍 Key Findings
- 50%+ of loans experience at least one overdue payment
- Most loans are eventually closed, but often with short delays (1–10 days)
- Clients with frequent partial payments tend to be more disciplined
- Metrics like `overdue_share`, `days_lag`, and `payment_count_between` are strong indicators of risk

## 🧩 Next Steps
- Add customer-level data (demographics, acquisition channel)
- Build predictive models for overdue risk
- Segment customers based on payment stability
- Test nudging strategies to improve on-time payments
