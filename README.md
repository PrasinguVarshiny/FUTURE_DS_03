# Future Interns – Data Science & Analytics Task 3
## Marketing Funnel & Conversion Performance Analysis

### 📌 Project Overview

This project is part of the **Future Interns Data Science & Analytics Internship – Task 3**.

The objective of this project is to analyze marketing campaign data and understand customer conversion patterns, campaign performance, drop-offs, and factors that influence successful conversions.

The analysis was performed using **Python, Pandas, Plotly, and Jupyter Notebook**, with an interactive dashboard created to present the key findings.

---

## 🎯 Objectives

- Analyze the overall marketing conversion rate.
- Understand the marketing funnel and customer drop-offs.
- Compare conversion performance across contact channels.
- Identify customer groups with higher conversion rates.
- Analyze conversion performance by job and education.
- Study monthly campaign performance.
- Understand how previous campaign outcomes affect conversions.
- Provide data-driven business recommendations.

---

## 📂 Dataset

The project uses the **UCI Bank Marketing Dataset**.

The dataset contains information about customers contacted during marketing campaigns, including:

- Age
- Job
- Education
- Contact method
- Campaign month
- Previous campaign outcome
- Campaign-related information
- Final subscription/conversion result

The target variable is:

- `y = yes` → Converted
- `y = no` → Not Converted

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – Data cleaning and analysis
- **NumPy** – Numerical operations
- **Plotly** – Interactive visualizations
- **Jupyter Notebook**
- **HTML** – Interactive dashboard export
- **CSV** – Analysis outputs

---

## 📊 Key Analysis

### 1. Marketing Funnel

The funnel analysis represents:

**Total Contacts → Converted Customers → Drop-offs**

This helps understand the overall campaign performance and identify the gap between customer outreach and successful conversions.

### 2. Contact Channel Analysis

Conversion rates are compared across different contact channels to identify which communication method performs better.

### 3. Age Group Analysis

Customers are grouped into different age categories to identify which age groups have stronger conversion performance.

### 4. Job & Education Analysis

Conversion rates are analyzed across different customer job categories and education levels.

### 5. Monthly Performance

Monthly campaign performance is analyzed to identify periods with relatively higher or lower conversion rates.

### 6. Previous Campaign Outcome

Previous campaign results are analyzed to understand whether a customer's past interaction influences their likelihood of conversion.

---

## 📈 Dashboard

The interactive dashboard includes:

- KPI Cards
- Marketing Funnel
- Contact Channel Conversion
- Age Group Conversion
- Job-wise Conversion
- Education-wise Conversion
- Monthly Conversion Trend
- Previous Campaign Outcome
- Converted vs Not Converted comparison

The dashboard allows users to explore the campaign performance interactively through Plotly visualizations.

---

## 💡 Key Business Insights

The analysis helps identify:

- Overall campaign conversion and drop-off levels.
- Better-performing customer segments.
- More effective contact channels.
- Customer groups with stronger conversion potential.
- Monthly variations in campaign performance.
- The impact of previous campaign interactions on conversion.

---

## 📌 Business Recommendations

Based on the analysis:

1. Focus marketing efforts on customer segments with higher conversion rates.
2. Prioritize communication channels that demonstrate stronger performance.
3. Use previous campaign outcomes to improve customer targeting.
4. Optimize campaign timing based on monthly conversion patterns.
5. Reduce customer drop-offs by improving targeting and communication strategies.
6. Use data-driven segmentation instead of applying the same marketing approach to every customer.

---

## 📁 Project Files

```text
Future-Interns-Task-3/
│
├── Future_Interns_Task_3.ipynb
├── Future_Interns_Task_3_Dashboard.html
├── bank-full.csv
│
├── task3_cleaned_data.csv
├── task3_contact_analysis.csv
├── task3_age_analysis.csv
├── task3_job_analysis.csv
├── task3_education_analysis.csv
├── task3_month_analysis.csv
└── task3_previous_campaign_analysis.csv
