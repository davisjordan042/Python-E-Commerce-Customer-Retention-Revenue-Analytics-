# E-Commerce Customer Retention & Revenue Analytics (Python)

## Project Overview
This project analyzes an ecommerce dataset derived from the Olist platform to generate actionable business insights around customer behavior, revenue growth, retention, and churn. The analysis spans descriptive analytics, predictive modeling, and survival analysis using Python.

## Dataset Description
The project integrates multiple pre-aggregated and customer-level datasets, including:
- Customer RFM metrics
- Cohort retention data
- Revenue growth metrics
- Delivery performance and customer reviews
- Product category performance
- Executive KPIs

All datasets were processed with robust handling of nulls, blanks, and missing values.

## Key Analyses Performed
1. Executive KPI Analysis
  - Total revenue, orders, AOV, unique customers, repeat purchase rate
  - Business health snapshot for decision-makers

2. Revenue Growth & Trend Analysis
  - Month-over-month revenue growth
  - Seasonality detection and trend interpretation

3. Customer Acquisition Analysis
  - New customer growth over time
  - Identification of acquisition slowdowns and accelerations

4. Product Category Performance
  - Average Order Value (AOV) by category
  - Review score comparison to identify price–quality trade-offs

5. Delivery Performance vs Customer Satisfaction
  - Quantified relationship between delivery delays and review scores
  - Identified operational risks impacting customer experience

6. Cohort Retention Analysis
  - Repeat purchase rates by signup month
  - Identification of early churn periods

7. RFM Segmentation
  - Recency, Frequency, Monetary scoring
  - Identification of high-value, loyal, and at-risk customers

8. Advanced Customer Segmentation
  - Clustered customers using machine learning to uncover behavioral segments

9. Predictive Churn Modeling
  - Built churn classifiers using Logistic Regression and Random Forest
  - Predicted customers likely to stop purchasing

10. Survival Analysis (Time-to-Churn)
  - Kaplan–Meier survival curves
  - Cox regression to identify drivers of churn timing

11. VIP Customer Analysis
  - Identified top-spending and high-frequency customers
  - Revenue concentration and loyalty insights

12. Business Action Framework
  - Recommended retention, re-engagement, and VIP strategies based on model outputs

## Key Business Insights
- Customers with high recency and low frequency exhibit the highest churn risk.
- Delivery delays negatively correlate with customer review scores.
- A small segment of VIP customers contributes a disproportionate share of revenue.
- Certain product categories combine high AOV with low satisfaction, indicating pricing or quality risks.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-Learn
- Lifelines (Survival Analysis)
- Statsmodels
- Matplotlib / Seaborn / Plotly

 ## Skills Demonstrated
- Customer Analytics
- Churn & Retention Modeling
- Survival Analysis
- Time Series Analysis
- Business Insight Generation
- Data Cleaning & Feature Engineering

## Screenshots
<h3>Random Forest Churn Prediction Model</h3>

<p align="center">
 <img width="515" height="429" alt="Random Forest" src="https://github.com/user-attachments/assets/1ef0494b-0623-4a3e-86a1-9a89c4888957" />
  <br>
  <em>
    Random Forest classifier trained on RFM and customer value features to predict customer churn, capturing non-linear behavioral patterns.
  </em>
</p>

<h3>Churn Model Evaluation</h3>

<p align="center">
 <img width="512" height="325" alt="classification" src="https://github.com/user-attachments/assets/912b2061-8470-4b63-82c0-19338150517c" />
  <br>
  <em>
    Classification report evaluating churn prediction performance using precision, recall, F1-score, and overall model balance.
  </em>
</p>

<h3>Customer Survival Analysis</h3>

<p align="center">
 <img width="515" height="440" alt="Kaplan–Meier Survival Curve" src="https://github.com/user-attachments/assets/ff7e79d9-f5cf-4630-93c0-02a45eaebec3" />
  <br>
  <em>
    Kaplan–Meier survival curve estimating customer retention over time and highlighting periods where churn risk accelerates.
  </em>
</p>

<h3>Monthly Revenue Growth Analysis</h3>

<p align="center">
<img width="878" height="255" alt="Revenue Growth Trend" src="https://github.com/user-attachments/assets/8dabe3b8-e415-4a19-b469-a712875e7e1b" />
  <br>
  <em>
    Month-over-month revenue growth analysis used to identify business expansion, contraction periods, and potential seasonality effects.
  </em>
</p>

<h3>Customer Segmentation – Optimal Cluster Selection</h3>

<p align="center">
 <img width="662" height="358" alt="clusters" src="https://github.com/user-attachments/assets/d342493b-7911-4829-a5b2-d7e55c174dd0" />
  <br>
  <em>
    Elbow method visualization using inertia to determine the optimal number of customer clusters for behavioral segmentation.
  </em>
</p>

## How This Project Is Used
This project demonstrates the ability to:
- Translate raw ecommerce data into decision-ready insights
- Build predictive models for real business problems
- Communicate findings in a business-oriented manner






