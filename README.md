# customer-churn-analysis
Customer churn prediction using machine learning on Telco dataset

# Customer Churn Analysis 🧠📉

Predicting customer churn using machine learning models and exploratory data analysis (EDA).  
This project helps businesses identify customers who are likely to leave and take action.

---

## 📁 Project Structure

customer-churn-analysis/
├── data/ # Dataset CSV
├── notebooks/ # Jupyter notebook with EDA & modeling
├── outputs/ # Charts, models (optional)
├── README.md # This file
├── requirements.txt # Python dependencies
└── config.yaml # (optional) Settings for models or data paths


---

## 📊 Dataset

- Source: [Telco Churn Dataset on Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)
- Features: Contract type, tenure, billing method, charges, and more
- Target: `Churn` (Yes/No)

---

## 🔍 Process

1. **Exploratory Data Analysis**
2. **Preprocessing**
3. **Model Building** — Logistic Regression, Decision Tree, XGBoost
4. **Model Evaluation** — Accuracy, AUC Score, F1-Score
5. **Feature Importance & Business Insights**

---

## 🧠 Key Findings

- Month-to-month contracts strongly drive churn
- Low tenure (new customers) are more likely to churn
- Higher charges correlate with churn

---

## 🧠 Business Recommendations

- Encourage longer contracts (1 or 2-year deals)
- Improve onboarding to retain early-stage customers
- Offer loyalty discounts or support bundles for high-charge users

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/SaiGundapaneni-Dev/customer-churn-analysis.git

# Create a virtual environment
python -m venv venv
source venv/Scripts/activate  # Windows
# or
source venv/bin/activate      # Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Start Jupyter Notebook
jupyter notebook

