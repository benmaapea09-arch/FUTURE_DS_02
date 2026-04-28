# 📊 Customer Retention & Churn Analysis (SaaS)

## 🚀 Project Overview
This project analyzes customer churn and retention patterns in a SaaS subscription business.  
The goal is to understand **why customers leave, what drives retention, and how to reduce churn to improve revenue and growth**.

The analysis integrates multiple datasets to build a **Customer 360 view**, enabling deeper insights into customer behavior, engagement, support interactions, and subscription value.

---

## 🎯 Objectives
- Identify **churn patterns and trends**
- Analyze **customer engagement and product usage**
- Evaluate the impact of **support interactions on churn**
- Understand **customer lifetime and revenue contribution**
- Provide **actionable recommendations** to improve retention

---

## 🧠 Business Context
This project simulates a SaaS company where revenue depends heavily on customer retention.

Reducing churn improves:
- Customer Lifetime Value (CLV)
- Monthly Recurring Revenue (MRR)
- Long-term growth

---

## 📂 Datasets Used
The project integrates five datasets:

- **Accounts** – Customer profile and demographics  
- **Subscriptions** – Revenue, plans, and lifecycle data  
- **Feature Usage** – Product engagement and behavior  
- **Support Tickets** – Customer friction and service quality  
- **Churn Events** – Churn timing and reasons  

---

## 🛠️ Tools & Technologies
- Python (Pandas) – Data cleaning & feature engineering  
- Jupyter Notebook – Analysis workflow  
- Power BI – Dashboard and visualization  

---

## 🧱 Methodology

### 1. Data Cleaning
- Converted date fields to datetime  
- Handled missing values  
- Removed duplicates  
- Standardized numeric columns  

---

### 2. Feature Engineering

#### 📈 Subscription Features
- Tenure (customer lifetime)
- Average MRR
- Total estimated revenue
- Plan type and billing frequency

#### 🛠️ Support Features
- Ticket count
- Resolution time
- Response time
- Escalation rate
- Customer satisfaction score

#### ⚙️ Usage Features
- Total usage events
- Active days
- Feature diversity
- Error rates
- Engagement score

#### 🚨 Churn Features
- Churn flag (combined from multiple sources)
- Churn reason
- Churn timing

---

### 3. Customer 360 Dataset
All datasets were merged into a single dataset (one row per customer) to enable:
- Customer-level analysis  
- Cross-functional insights  
- Accurate churn modeling  

---

## 📊 Key Insights

- **Low engagement strongly correlates with churn**  
- **Support friction increases churn risk**  
- **Early-stage churn is significant (onboarding issue)**  
- **Higher-value customers tend to churn less**  

---

## 💡 Recommendations

- Improve onboarding to reduce early churn  
- Target low-engagement users with re-engagement strategies  
- Reduce support response and resolution times  
- Promote higher-value subscription plans  
- Monitor high-risk customer segments  

---

## 📊 Dashboard Features
The Power BI dashboard includes:
- Churn overview and KPIs  
- Engagement vs churn analysis  
- Support impact on churn  
- Revenue and lifetime insights  
- Churn reasons and segmentation  

---

## 📁 Project Structure
