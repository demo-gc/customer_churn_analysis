# 📊 Customer Churn Analysis

Customer churn analysis using the [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn).  
This project focuses on **exploratory data analysis (EDA)** to identify key drivers of churn and translate findings into **business recommendations**.  

---

## 🚀 Project Overview
Customer churn directly impacts recurring revenue, making it a critical metric for subscription-based businesses.  
This project analyzes ~7,000 telecom customers to answer:  

- What factors drive customer churn?  
- How do contract type, payment methods, and services affect retention?  
- Which customer segments should be prioritized for retention efforts?  

---

## 📂 Project Structure
customer_churn_analysis/
│
├── README.md # Project overview
├── requirements.txt # Dependencies
├── notebooks/
│ └── churn_analysis.ipynb # Jupyter notebook with EDA
├── data/
│ └── raw/
│ └── README.md # Instructions to download dataset
└── visuals/ # (Optional) Saved plots as PNGs

---

## 📊 Key Findings
- **Overall churn rate: 26.5%.**  
- Customers on **month-to-month contracts churn at 42.7%**, vs 11.3% (1-year) and 2.8% (2-year).  
- **Electronic check users churn at 45.3%**, much higher than other payment methods (15–19%).  
- Customers with **tenure <1 year churn at 47.7%**, while tenure >4 years churn <10%.  
- Customers with **Tech Support (15.2%) or Online Security (14.6%)** churn far less than those without (~42%).  

---

## 💡 Recommendations
- Incentivize **month-to-month customers** to switch to longer-term contracts.  
- Encourage **electronic check users** to adopt automatic payments.  
- Prioritize **first-year customers** for retention campaigns.  
- Bundle and promote **Tech Support + Online Security** services.  

---

## 🛠️ How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/demo_gc/customer_churn_analysis.git
   cd customer_churn_analysis
2. Install dependencies
   - pip install -r requirements.txt
3. Launch Jupyter Notebook
   - jupyter notebook
4. Open `notebooks/01-analysis.ipynb` and run all cells.

**Data: ** Download from Kaggle link and place in `data/raw/`.


## 📈 Sample Visuals

### Churn by Payment type
<img width="779" height="576" alt="payment method vs churn" src="https://github.com/user-attachments/assets/daf99c95-7af9-42cd-9fdc-87b17a95e50b" />

### Churn by Contract Type
<img width="791" height="525" alt="contract type vs churn" src="https://github.com/user-attachments/assets/cc1a7c4a-06e5-4f91-a06c-cd7d3a2ffa0b" />

### Churn by Tenure
<img width="730" height="461" alt="tenure vs churn" src="https://github.com/user-attachments/assets/fd2e3583-bd62-4e7a-b5f7-f5c36a472387" />
<img width="753" height="474" alt="tenure vs churn average plot" src="https://github.com/user-attachments/assets/6d4a2e2c-65de-45a6-8459-b44c8474b8b2" />



Additional charts and analysis available in the notebook.
