# ChurnScope: Data-Driven Customer Retention Analytics in Telecom

## 📊 Overview

Customer churn is a major challenge in the telecom industry, directly impacting revenue and growth. **ChurnScope** focuses on exploratory data analysis **(EDA)** to understand customer behavior, service usage, and account patterns that influence churn. Using Python-based data analytics, this project uncovers key churn drivers and provides data-backed insights that can support customer retention strategies.

## 🎯 Problem Statement

Telecom companies experience significant revenue loss due to customers discontinuing services. The objective of this project is to:

- Analyze customer attributes and service usage patterns
- Identify factors strongly associated with customer churn
- Quantify churn behavior using **percentage-based insights**
- Support data-driven decision-making for retention strategies

*Note:* The analysis is **descriptive and diagnostic**, not predictive.

## 📁 Dataset

- *Source:* IBM Telco Customer Churn (Kaggle – public sample dataset)
- *Type:* Synthetic dataset designed to simulate real-world telecom behavior
- *Records:* 7,043 customers
- *Features:* 21 attributes
- *Target Variable:* Churn (Yes / No)

### Data Categories

| Category | Description |
|----------|-------------|
| *Customer Status* | Churn indicator |
| *Services* | Phone, Internet, Streaming, Security, Backup, Tech Support |
| *Account Details* | Contract type, tenure, billing method, charges |
| *Demographics* | Gender, senior citizen status, dependents, partners |

## 🛠️ Tools and Technologies

- *Python* - Core programming language
- *NumPy* - Numerical operations
- *Pandas* - Data manipulation and preprocessing
- *Matplotlib* - Data visualization
- *Seaborn* - Statistical and comparative visualizations
- *Jupyter Notebook* - Analysis environment

## 🔍 Methods

The project follows a structured EDA workflow:

**1.**  Data loading and structure inspection

**2.**  Data cleaning and type correction

**3.**  Separation of numerical and categorical features

**4.**  Univariate and bivariate analysis

**5.**  Percentage-based churn comparisons

**6.**  Visualization-driven interpretation

**7.**  Insight summarization

**Note:** This is a **purely exploratory analysis** project. No machine learning models or predictive algorithms are implemented.

## 💡 Key Insights

All insights are derived directly from dataset analysis:

### 🔹 Overall Churn
- ~26.5% of customers have churned *(approx.)*
- ~73.5% customers are retained

### 🔹 Contract Type Impact
- *Month-to-Month contracts:* ~42% churn rate
- *One-Year contracts:* ~11% churn rate
- *Two-Year contracts:* ~3% churn rate

*→ Longer contracts strongly correlate with lower churn.*

### 🔹 Tenure Behavior
- Customers with short tenure (0–12 months) show the highest churn percentage
- Churn rate consistently decreases as tenure increases

*→ Early customer lifecycle is the most critical retention phase.*

### 🔹 Payment Method
- Customers using *Electronic Check* show the highest churn (~45%)
- Customers using *Credit Card / Bank Transfer* have significantly lower churn rates

*→ Payment method choice influences customer stability.*

### 🔹 Internet Service
- Customers with *Fiber Optic Internet* churn more than DSL users
- Customers without internet service have the lowest churn percentage

### 🔹 Add-on Services
Customers *without* the following services show higher churn:
- Online Security
- Tech Support
- Device Protection

*→ Value-added services improve customer retention.*

## 📈 Dashboard / Output

Multiple bar plots, count plots, and comparative charts created using Matplotlib and Seaborn visualize:

- Churn vs Contract Type (percentage-based)
- Churn vs Tenure groups
- Churn vs Payment Methods
- Service-wise churn comparisons

These plots support visual storytelling and business interpretation.

## 🚀 How to Run this Project

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook

### Installation & Setup

**1.** Clone the repository

**2.** Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn
```

**3.** Open ```TCA.ipynb``` in Jupyter Notebook


**4.** Run cells sequentially to reproduce analysis and visualizations

## 📊 Results & Conclusion

The analysis reveals that customer churn is not random, but strongly influenced by:

- Contract duration
- Early tenure period
- Payment methods
- Internet service type
- Availability of support and security services

By targeting **high-risk customer segments** - especially new, month-to-month customers - telecom companies can design **focused retention strategies**.

This project demonstrates how **exploratory data analytics** can translate raw data into **actionable business insights**.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.



## 📬 Contact

### **Deorshi Nishant**
**Data Analyst | Business Intelligence Professional**

---

### 🔗 Connect with Me

<p align="left">
  <a href="https://www.linkedin.com/in/itsyournish/" target="_blank">
    <img 
      src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" 
      alt="LinkedIn Profile"
    />
  </a>
  <a href="mailto:itsyournish07@gmail.com">
    <img 
      src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" 
      alt="Email"
    />
  </a>
</p>

---

💼 **Open to opportunities and collaborations** in  
**Data Analytics | Business Intelligence | Data-Driven Roles**

⭐ If you found this project helpful, please consider **giving it a star**

---

**Made with 📊 data and 🐍 Python**
