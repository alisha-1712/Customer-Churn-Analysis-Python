# Customer Churn Analysis (Python)

## PROJECT OVERVIEW
Customer churn is one of the biggest challenges for subscription-based and service-driven businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project performs a **business-focused exploratory data analysis (EDA)** to understand **why customers churn**, identify **early warning signals**, and translate insights into **actionable business recommendations**.

---

## BUSINESS PROBLEM
The objective of this analysis is to answer key business questions such as:

- Which customer groups are more likely to churn?
- What behavioral patterns appear before churn occurs?
- Do contracts, pricing, or engagement metrics meaningfully influence churn?
- Are there clear early warning signals businesses can act on?

The goal is not prediction, but **understanding churn drivers** from a business perspective.

---

## DATASET DESCRIPTION
- **Source:** Kaggle – [Customer Churn Prediction Business Dataset](https://www.kaggle.com/datasets/miadul/customer-churn-prediction-business-dataset)
- **Records:** 10,000 customers  
- **Features:** 32 variables covering:
  - Customer demographics
  - Usage behavior and engagement metrics
  - Pricing and billing information
  - Customer support interactions
  - Satisfaction and feedback scores  

- **Target Variable:**  
  - `churn`  
    - `0` → Retained  
    - `1` → Churned  

---

## TOOLS
- Python  
- pandas  
- NumPy  
- Seaborn & Matplotlib  
- Jupyter Notebook  

---

## ANALYSIS STRUCTURE
The analysis is organized into three notebooks:

1. **Setup & Data Validation**
   - Data loading and sanity checks
   - Basic cleaning and validation
   - Creation of readable churn labels

2. **Feature Engineering & Risk Analysis (NumPy)**
   - Customer tenure segmentation
   - Usage-based risk flags
   - Support experience risk indicators
   - Combined churn risk profiling

3. **Exploratory Data Analysis (Seaborn)**
   - Churn distribution analysis
   - Churn rate by tenure and contract type
   - Engagement behavior comparison
   - Distribution-based insights using boxplots

---

## KEY INSIGHTS
- **Churn is highly concentrated among new customers**, indicating early lifecycle risk.
- Engagement frequency (monthly logins) shows more churn separation than session duration.
- Contract type shows **minimal impact on churn**, challenging common assumptions.
- Single metrics rarely explain churn — **combined behavioral signals** are more effective.
- Usage and support-related disengagement patterns emerge before churn occurs.

---

## BUSINESS RECOMMENDATIONS
- Strengthen onboarding and engagement initiatives during the **first 3–6 months**.
- Use **combined risk indicators** instead of relying on single metrics.
- Prioritize retention efforts for disengaged customer segments rather than blanket campaigns.
- Monitor early behavioral signals to intervene before churn happens.

---

## KEY INSIGHTS
Customer churn is primarily a **behavioral and lifecycle-driven problem**, not a single-factor issue. Businesses that focus on early engagement and multi-signal monitoring are better positioned to reduce churn and improve long-term retention.

---

