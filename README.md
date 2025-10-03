# Banking_Analysis
# 🏦 Banking Analysis Project

## 📌 Overview
This project performs an in-depth **analysis of banking customer data** using **Python (EDA)** and **Power BI (Visualization)**.  
The goal is to uncover key insights into customer behavior, financial patterns, and risk profiles that can help banks improve decision-making, customer segmentation, and financial product targeting.

---

## 📂 Project Structure
- **Banking.csv** → Raw dataset (3,000 records, 25 columns)  
- **Banking.ipynb** → Jupyter Notebook (Data Cleaning, EDA, Feature Engineering, Insights)  
- **Banking analysis.pbix** → Power BI Dashboard (interactive reports and KPIs)  

---

## 🛠 Tech Stack
- **Python** → Pandas, NumPy, Matplotlib, Seaborn  
- **Power BI** → Dashboard, KPIs, Interactive Reports  
- **Jupyter Notebook** → EDA, preprocessing, insights  

---

## 📊 Dataset Description
The dataset contains **3,000 customers** with the following details:
- **Demographics** → Age, Gender, Nationality, Occupation  
- **Banking Data** → Deposits, Loans, Accounts, Credit Cards, Risk Weighting  
- **Customer Info** → Loyalty Classification, Fee Structure, Joined Bank date  

---

## 🔎 Exploratory Data Analysis (EDA)
Key steps performed in the notebook:
1. **Data Cleaning**
   - Converted `Joined Bank` to datetime → Calculated customer tenure  
   - Checked duplicates in `Client ID`  
   - Encoded categorical features (Gender, Branch, IAId)  

2. **Categorical Analysis**
   - Distribution of customers by Nationality, Gender, Occupation  
   - Loyalty Classification vs. Deposits  

3. **Numerical Analysis**
   - Histograms & boxplots for Age, Income, Deposits, Loans  
   - Correlation heatmap of financial metrics  

4. **Bivariate Analysis**
   - Deposits vs. Income  
   - Age vs. Loans (by Gender)  
   - Net Worth vs. Loyalty Classification  

5. **Feature Engineering**
   - Customer Tenure  
   - Net Worth = Deposits + Savings + Properties – Loans  
   - Loan-to-Income Ratio  

---

## 📈 Power BI Dashboard
The Power BI dashboard includes:
- **KPI Cards**: Total Deposits, Total Loans, Avg. Customer Income  
- **Visuals**:
  - Deposits vs. Age group  
  - Occupation vs. Loyalty Classification  
  - Loan-to-Income ratio by Fee Structure  
  - Risk Weighting by Nationality  

---

## 💡 Key Insights
- Platinum customers hold the **highest deposits and savings**.  
- Younger clients (20–35 years) take more loans compared to older customers.  
- Higher risk weighting is associated with lower deposits and higher loans.  
- Occupation strongly influences deposit levels (e.g., consultants & engineers have higher savings).  
- Loyalty classification can be predicted based on deposits and income patterns.  

---

## 🚀 Future Improvements
- Build a **predictive ML model** to classify customers into loyalty tiers.  
- Improve feature engineering (e.g., transaction frequency, tenure segmentation).  
- Enhance Power BI dashboard with drill-through and advanced filters.  

---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/banking-analysis.git
   cd banking-analysis
