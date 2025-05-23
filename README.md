# **📊 Customer Churn Analysis in Telecom: A Comprehensive Study**

## 📌 **Project Overview**
This repository contains **five** detailed analyses on **customer churn** in the telecommunications industry, covering **demographics, service usage, financial impact, service retention strategies, and predictive modeling**. Each study provides key insights into churn behavior and offers actionable recommendations for improving customer retention.

## 🔍 **Projects Included**
### **1️⃣ Demographic Analysis of Customer Churn**
- **Objective:** Identify key customer groups prone to churn based on age, relationship status, and dependents.
- **Key Findings:**
  - **Older customers** (particularly single ones without dependents) exhibit the highest churn rates.
  - **Young, single customers** contribute significantly to overall churn due to their large customer base.
  - **Young, partnered customers with dependents** show **lowest churn rates**, providing a stable segment for retention.
- **Business Implications:** Retention strategies must **target older and young single customers**, while leveraging upsell opportunities for stable segments.

### **2️⃣ Service-Based Churn Analysis**
- **Objective:** Examine which telecom services are most associated with churn.
- **Key Findings:**
  - **Internet Service has the highest churn rate** (31.83%), followed by **Streaming TV & Movies**.
  - **Customers without Online Security and Tech Support** are significantly more likely to churn.
  - **Phone Line services contribute heavily to overall losses, despite moderate churn rates**.
- **Business Implications:** Improving **Internet Service reliability**, enhancing streaming **value propositions**, and **encouraging security service adoption** could drive retention.

### **3️⃣ Financial Impact of Customer Churn**
- **Objective:** Assess how different contract types affect churn rates and revenue loss.
- **Key Findings:**
  - **Monthly contracts dominate** in popularity (55% of customers) but suffer **highest churn rate** (42.71%).
  - **Two-year contracts retain customers best**, with the **lowest churn rate (2.83%)**.
  - **Churned customers tend to pay higher monthly fees** than the average, suggesting pricing adjustments may be needed.
  - **Revenue loss due to churn is substantial**, with monthly revenue dropping from **€456,116.6 to €316,985.75**.
- **Business Implications:** Retention strategies must **focus on monthly contract users** to prevent revenue loss, while optimizing long-term pricing structures.

### **4️⃣ Demographic & Service-Based Financial Analysis**
- **Objective:** Investigate the **financial impact of churn** across various customer segments and service consumption.
- **Key Findings:**
  - **Young, single males and females** generate the most revenue but also **have high churn rates**.
  - **Older, single females without dependents** experience **severe revenue loss (66%)** due to churn.
  - **Customers subscribed to Tech Support and Online Security churn less** than those who don’t use these services.
- **Business Implications:** Strategies should **target high-churn revenue-driving segments** (young singles & older females) while **promoting retention-focused services**.

### **5️⃣ Predictive Modeling of Customer Churn**
- **Objective:** Build a **machine learning model** to predict future churn risk.
- **Key Findings:**
  - **Tenure, Fibre Optic Internet, Two-Year Contracts, and Electronic Check Payments** are **key churn indicators**.
  - **Optimized KNN model achieved 78.66% accuracy** using feature selection and hyperparameter tuning.
  - **False negatives remain a concern**, requiring improvements through **class balancing & alternative modeling techniques**.
- **Business Implications:** This model **can help companies proactively identify and retain at-risk customers** before churn occurs.

---

## 📊 **Technologies & Tools Used**
- **Python** for data analysis & modeling
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for visualization
- **Scikit-Learn** for machine learning (KNN classification)
- **Jupyter Notebook** for exploratory data analysis (EDA)
