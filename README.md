# FUTURE_DS_03
Future Interns Data Science & Analytics Task 3 Repository
# Bank Marketing Campaign - Funnel & Conversion Analysis

## Marketing Funnel Performance | Lead Conversion Analysis | Campaign Optimization

![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange) ![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Pandas](https://img.shields.io/badge/Pandas-2.x-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Viz-blue)

## 📋 Project Overview

This project analyzes a "Bank Marketing Campaign" dataset to understand customer conversion behavior for a "term deposit" product. The goal was to identify drop-off points in the marketing funnel, evaluate channel performance, and provide actionable recommendations to improve lead-to-customer conversion rates.

## Data Source
I downloaded the Dataset From: https://archive.ics.uci.edu/dataset/222/bank+marketing
I used the dataset bank-full.csv from the zipped files

### Business Questions Addressed:
- Where are customers dropping off in the campaign funnel?
- Which channels and customer segments perform best?
- What factors most influence subscription decisions?
- How can the bank improve overall conversion rates?

---

## 📁 Repository Contents

- `Task3.ipynb` → Complete Jupyter Notebook
- `bank-full.csv` → Original dataset (45,211 records)
- `/Task3Screenshots/` → Folder containing all chart screenshots
- `README.md` → This file

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy)
- Data Visualization: Matplotlib & Seaborn
- Jupyter Notebook

---

## 📊 Key Insights

- "verall Conversion Rate": 11.7% (5,289 successful term deposit subscriptions)
- "Best performing segments": Students (28.7%), Retirees (22.8%), and customers aged 60+ (42.3%)
- Channel Performance: Cellular contact outperforms others (14.9% conversion)
- "Previous Success" is a very strong predictor (64.7% conversion on re-contact)
- Longer "call duration" strongly correlates with success (avg. 537s vs 221s)
- Customers "without housing loans" convert at nearly double the rate
- Conversion rate decreases significantly with repeated campaign contacts

---

## 🎯 Actionable Recommendations

1. Prioritize targeting "retirees, students, and senior customers"
2. Focus on "cellular outreach" and ensure quality phone contact data
3. Invest in "re-targeting" customers with previous positive responses
4. Train sales teams to have "deeper, longer conversations"
5. Run major campaigns during high-performing months (March, September–December)
6. Develop tailored messaging for customers without existing loans

---

## 📈 Visualizations Included

- Conversion by Job, Age Group, and Marital Status
- Channel (Contact Method) performance
- Call Duration analysis
- Account Balance comparison
- Impact of Housing & Personal Loans
- Campaign intensity and Monthly seasonality
- Previous campaign outcome effectiveness

*(All charts available in the `/Task3Screenshots/` folder)*

---

## 🚀 How to Run the Notebook

1. Clone the repository:
   ```bash
   git clone <https://github.com/Collins3-cpu/FUTURE_DS_03>
   cd bank-marketing-analysis
