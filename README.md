# MTN Nigeria Customer Churn Analysis – Q1 2025

## Project Description

This project analyzes customer churn for **MTN Nigeria** in **Q1 2025** using **Power BI**. The goal is to identify patterns contributing to customer churn, evaluate churn drivers by gender, device type, and tenure, and recommend strategic actions to reduce churn and improve revenue retention.  

A combination of **Power BI**, **Power Query**, and **DAX** was used for data transformation, modeling, and interactive visualizations.

---

## 🔍 Key Insights

- **Total Customers**: 963  
- **Active Users**: 680 (70.61%)  
- **Churned Customers**: 283 (29.49%)  
- **Total Revenue**: ₦199M  
- **Revenue Lost Due to Churn**: ₦58M  
- **ARPU (Average Revenue Per User)**: ₦207K  
- **Average Customer Rating**: 2.95

---

## Gender-Based Analysis

| Gender | Total Customers | % of Customers | Revenue (₦M) | Revenue % | Revenue Lost (₦M) | Revenue Lost % | ARPU (₦K) | Avg. Rating |
|--------|------------------|----------------|---------------|------------|-------------------|----------------|-------------|--------------|
| Female | 487              | 51%            | 104           | 52.23%     | 32                | 31%            | 214         | 2.85         |
| Male   | 476              | 49%            | 95            | 47.77%     | 26                | 27%            | 199         | 3.05         |

> 🔹 **Insight**: Female users have **higher ARPU** but **lower satisfaction**, contributing more to revenue loss. Common complaints include **high call tariffs**, **poor network**, and **customer service**.

---

## 📱 Device Type-Based Churn & Revenue Analysis

| Device Type     | Total Users | Active % | Inactive % | Revenue Gained (₦M) | Revenue Lost (₦M) | Lost % (within Type) | ARPU (₦K) | Avg. Rating |
|------------------|-------------|----------|------------|----------------------|-------------------|------------------------|------------|--------------|
| 5G Broadband     | 229         | 72%      | 28%        | 101                  | 14                | 31%                    | 440        | 3.02         |
| 4G Router        | 216         | 70%      | 30%        | 37                   | 12                | 32%                    | 171        | 2.91         |
| Broadband MiFi   | 228         | 73%      | 27%        | 48                   | 12                | 24%                    | 222        | 3.20         |
| Mobile SIM Card  | 290         | 68%      | 32%        | 13                   | 4                 | 26%                    | 41         | 2.86         |

> 🔹 **Insight**: **5G Broadband** and **Broadband MiFi** have the highest ARPU and satisfaction.  
> 🔸 **Mobile SIM users** have **lowest ARPU and satisfaction** with **highest churn**.

---

## 🎯 Recommendations

### 1. **Retain High-Value Customers (5G Broadband & MiFi)**
- Launch **loyalty programs**, **priority support**, and **network upgrades**.
- Focus on user experience to retain ₦101M+ contributors.

### 2. **Improve 4G Router Experience**
- Investigate **speed drops**, **device performance**, and **tariff dissatisfaction**.
- Optimize plans to reduce ₦12M churn-related losses.

### 3. **Reevaluate Mobile SIM Card Strategy**
- Consider:
  - **Redesigning mobile offers** for higher value.
  - Or **deprioritizing** investment in this low-revenue, high-churn group.

### 4. **Segmented Churn Prediction & Campaigns**
- Build **churn prediction models** using device, age group, and rating.
- Deploy **targeted campaigns** to address pain points.

### 5. **Platinum (Long-Term) Customer Retention**
- Churn was **highest among customers with >18 months tenure**.
- Launch **retention benefits** for long-term customers.

---

## 🛠 Tools Used

- **Power BI** – for interactive dashboards
- **Power Query** – for data transformation
- **DAX** – for advanced measures and KPIs
- **Excel** – for initial data inspection

---

> ✅ This repository showcases the end-to-end churn analysis with actionable insights for business stakeholders and supports strategic retention planning at MTN Nigeria.
