# 📊 Sales & Marketing Analytics Project
### IBM SkillsBuild — Data Analytics with AI Internship
**Author:** Prakash Maiti

---

## 📌 Project Overview

This project performs end-to-end **Sales & Marketing Data Analytics** on a real-world customer dataset containing **15,000+ records** and **30 features**. The goal is to uncover actionable business insights about customer behaviour, churn, revenue, marketing effectiveness, and product satisfaction using **Python**, **machine learning**, and **data visualisation**.

---

## 🗂️ Project Structure

```
IBM_PRAKASHMAITI/
│
├── sales.csv                                           # Raw dataset (15,000 records, 30 columns)
├── requirements.txt                                    # Python dependencies
├── README.md                                           # Project documentation (this file)
├── PrakashMaiti Sales & Marketing Analytics Project.ipynb   # Main Jupyter Notebook
└── PrakashMaitiProjectReport.docx                     # Professional project report
```

---

## 📂 Dataset Description

| Column | Description |
|---|---|
| `customer_id` | Unique customer identifier |
| `gender` | Customer gender |
| `age` | Customer age |
| `country` | Country of residence |
| `city` | City of residence |
| `signup_date` | Date of account registration |
| `last_purchase_date` | Date of most recent purchase |
| `acquisition_channel` | How the customer was acquired |
| `device_type` | Device used (Mobile/Desktop/Tablet) |
| `subscription_type` | Monthly or Annual subscription |
| `is_premium_user` | Premium membership flag (0/1) |
| `total_visits` | Total platform visits |
| `avg_session_time` | Average session duration (minutes) |
| `pages_per_session` | Average pages viewed per session |
| `email_open_rate` | Email open rate (0–1) |
| `email_click_rate` | Email click-through rate (0–1) |
| `total_spent` | Cumulative revenue from customer (USD) |
| `avg_order_value` | Average transaction value (USD) |
| `discount_used` | Whether a discount was used (0/1) |
| `coupon_code` | Coupon applied, if any |
| `support_tickets` | Number of support tickets raised |
| `refund_requested` | Refund flag (0/1) |
| `delivery_delay_days` | Average delivery delay (days) |
| `payment_method` | Preferred payment method |
| `satisfaction_score` | Customer satisfaction (1–5) |
| `nps_score` | Net Promoter Score (0–10) |
| `marketing_spend_per_user` | Marketing spend allocated per user (USD) |
| `lifetime_value` | Predicted customer lifetime value (USD) |
| `last_3_month_purchase_freq` | Purchase frequency in last 3 months |
| `churn` | Churn flag — 1 = churned, 0 = retained |

---

## 🔍 Key Analyses Performed

1. **Data Cleaning & Preprocessing** — Missing values, duplicates, data types
2. **Exploratory Data Analysis (EDA)** — Distributions, correlations, outliers
3. **Customer Demographics Analysis** — Age, gender, country segmentation
4. **Revenue & Spending Analysis** — Total spend, LTV, AOV breakdowns
5. **Marketing Channel Effectiveness** — ROI by acquisition channel
6. **Churn Analysis** — Churn rate by demographics and behaviour
7. **Satisfaction & NPS Analysis** — Drivers of customer happiness
8. **AI/ML — Churn Prediction Model** — Logistic Regression + Random Forest
9. **Business Insights & Recommendations**

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9 or higher
- pip package manager

### Installation

```bash
# 1. Clone or download the project folder
cd IBM_PRAKASHMAITI

# 2. Install required libraries
pip install -r requirements.txt

# 3. Launch Jupyter Notebook
jupyter notebook
```

### Running the Notebook

1. Open `PrakashMaiti Sales & Marketing Analytics Project.ipynb`
2. Run all cells from top to bottom: **Kernel → Restart & Run All**
3. Ensure `sales.csv` is in the same directory as the notebook
4. DATASET LINK [ https://www.kaggle.com/datasets/bhaskerpaul/sales-and-marketing-dataset?resource=download ]
---

## 🛠️ Technologies Used

| Tool / Library | Purpose |
|---|---|
| **Python 3.9+** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Static data visualisation |
| **Seaborn** | Statistical data visualisation |
| **Plotly** | Interactive charts |
| **Scikit-learn** | Machine learning models |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📈 Key Findings

- **Churn rate** is significantly higher among customers with low satisfaction scores and high support ticket volumes
- **Email** and **Referral** channels yield the highest lifetime value customers
- **Annual subscribers** generate ~2× more revenue than monthly subscribers
- **Premium users** have a 35% lower churn rate than non-premium users
- The **Random Forest** churn prediction model achieves **>85% accuracy**

---

## 👨‍💼 Author

**Prakash Maiti**
IBM SkillsBuild — Data Analytics with AI Internship

---

## 📄 License

This project is created for educational purposes as part of the IBM SkillsBuild internship programme.
