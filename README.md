# Tata-GenAI-Powered-Data-Analytics-Virtual-Job-Simulation-
by FORAGE
<br><br>

![tata](https://github.com/ManishSharma-11/Tata-GenAI-Powered-Data-Analytics-Virtual-Job-Simulation-/blob/main/tata.png)

<br><br>

## Objective
This project focused on designing a responsible, scalable, and autonomous AI-powered collections system for Geldium Finance. The goal was to move from predictive insights to real-time, adaptive decision-making — enabling personalized customer outreach while maintaining fairness, transparency, and regulatory compliance. The project simulated a real-world AI transformation workflow, progressing through data analysis, business reporting, ethical strategy, and executive presentation.

<br>

## Tools used
- **MS EXCEL**
- **MICROSOFT COPILOT**
- **MS WORD**
- **MS POWERPOINT**

<br>

## Assigned Tasks

- Task 1. To do Predictive Modeling & Risk Segmentation
- Task 2. To make Business Summary Report
- Task 3. To design an Autonomous System 
- Task 4. Responsible AI & Compliance Strategy

<br>

## Task 1. To do Predictive Modeling & Risk Segmentation

Its objective was to identify customer segments at risk of credit card delinquency using structured data analysis, enabling targeted interventions and forming the foundation for the autonomous collections system.
And following are the steps that i have performed one by one to complete this task

### Step 1. Used the provided Excel file to explore customer repayment data
- Opened the Excel sheet containing anonymized customer-level data.
- Reviewed key columns such as [Credit Utilization , Missed Payments , Debt-to-Income Ratio , Age Group and Income Level ]
- Ensured data was clean and structured for segmentation (no missing values, consistent formats).

### Step 2. Then  i Segmented customers based on behavioral and demographic traits
- Created filters and pivot tables to group customers by:
- Age group (e.g., Gen Z, Millennials, Seniors)
- Credit utilization levels (Low, Medium, High)
- Number of missed payments
- Identified patterns such as:
- Gen Z customers with high utilization and multiple missed payments
- Mid-income earners with rising debt-to-income ratios
- And then Flagged these segments as high-risk candidates for delinquency.

### Step 3. Manually assigned risk tiers based on observed patterns
- Created three risk categories:
- High Risk – High utilization + 2+ missed payments
- Medium Risk – Moderate utilization + occasional delays
- Low Risk – Low utilization + consistent payment history
- Used conditional formatting and sorting to visualize risk tiers in Excel.

### Step 4: Interpreted feature importance conceptually
- Identified which features were most indicative of delinquency:
- Credit utilization had the strongest correlation with missed payments
- Debt-to-income ratio was a secondary driver

### Step 5: Converted technical findings into business insights
- Drafted a summary of key observations:
- “Gen Z customers with high utilization are 3× more likely to default”
- “Customers with rising debt-to-income ratios show early signs of stress”

Below is the attached doc of this task
<br>
![summary report](https://github.com/ManishSharma-11/Tata-GenAI-Powered-Data-Analytics-Virtual-Job-Simulation-/blob/main/EDA_SummaryReport_Template.docx)

<br>

## Task 2. Predictive Modeling Plan
To conceptualize a predictive modeling approach that forecasts which customers are most at risk of credit card delinquency. The goal is to use GenAI tools to outline model logic, justify the modeling choice, and plan an evaluation strategy — without writing actual code — while aligning with Geldium’s business and compliance needs.

### Step 1. Used GenAI to generate model logic based on Task 1 insights
- Selected Logistic Regression for binary classification
- Defined workflow: data → features → model → risk score → tier
- Chose top 5 features:[Credit Utilization, Missed Payments,Debt-to-Income Ratio,Age Group ,Income Level, Used GenAI to scaffold model structure and pseudocode]

### Step 2: Justified Model Choice
- Picked logistic regression for interpretability and compliance
- Easy to deploy, audit, and explain to stakeholders
- Compared with decision trees and neural nets — chose transparency over complexity
- Aligned with Geldium’s goals: fairness, trust, and regulatory fit

### Step 3: Planned Evaluation Strategy
- Key metrics: Accuracy, F1 Score, AUC-ROC, Fairness Checks
- Use confusion matrix and **SHAP** for interpretability
- Audit bias across age, income, and other sensitive groups
- Retrain if fairness thresholds are breached

Below is the attached doc of this task
<br>
![Model 2 plan](https://github.com/ManishSharma-11/Tata-GenAI-Powered-Data-Analytics-Virtual-Job-Simulation-/blob/main/Task%202_ModelPlan_Template.docx)

## Task 3. Stakeholder Report — Predictive Insights & Recommendation
To translate predictive findings into a clear, stakeholder-ready report that informs Geldium’s collections strategy and guides responsible use of AI insights.

### Step 1: Summarized predictive insights from Tasks 1 & 2
- Identified high-risk segments: Gen Z with high utilization and missed payments
- Highlighted top predictors: credit utilization, missed payments, debt-to-income ratio
- Created a 3-point summary for easy stakeholder communication

### Step 2: Converted key insight into a SMART recommendation
- Chose “high credit utilization” as the actionable insight
- Drafted a SMART goal targeting Gen Z with utilization >80%
- Proposed SMS/email outreach to reduce delinquency by 15% in 30 days
- Framed rationale in business-friendly language

### Step 3: Addressed ethical and responsible AI concerns
- Flagged fairness risks: age bias and income bias
- Suggested mitigation: SHAP-based transparency and human-in-the-loop review
- Explained model logic in plain language for non-technical stakeholders

Below is the attached doc of this task
<br>
![Geldium finance](https://github.com/ManishSharma-11/Tata-GenAI-Powered-Data-Analytics-Virtual-Job-Simulation-/blob/main/Geldium%20Finance.docx)

## Task 4. Final Presentation Deck

### Step 1: Designed the end-to-end system workflow
• 	Mapped the full lifecycle:
1. 	Customer Data Ingestion – real-time inputs like credit score, missed payments
2. 	Risk Scoring & Decision Engine – combines model outputs with business rules
3. 	Automated Outreach Actions – triggers SMS, support offers, or escalation
4. 	Outcome Monitoring & Learning Loop – tracks responses and refines strategy

### Step 2: Defined autonomy vs. human oversight
- Split system actions into:
- Autonomous Tasks – risk prediction, outreach selection, timing adjustments
- Human Oversight – hardship reviews, legal escalations, fairness audits
- Ensured ethical balance between automation and manual control

### Step 3: Embedded responsible AI safeguards
- Highlighted 4 key safeguards:
- Bias Detection – regular audits across demographics
- Explainability – SHAP-based plain-language explanations
- Human-in-the-Loop – manual review for high-impact cases
- Regulatory Alignment – compliance with ECOA, GDPR, FCRA, etc.

### Step 4: Quantified business and customer impact
- Projected KPIs for Geldium:
- 15–20% reduction in 30+ day delinquency
- 25% lower outreach cost
- Faster resolution of high-risk accounts
- Customer benefits:
- Personalized, empathetic outreach
- Fairer treatment and clearer communication
<br><br>
Below is the presentation that i have prepared in this task
<br>

![presentation](https://github.com/ManishSharma-11/Tata-GenAI-Powered-Data-Analytics-Virtual-Job-Simulation-/blob/main/Presentation1.pptx)


  <br><br><br><br>


# Achievement
<br>

![screenshot](https://github.com/ManishSharma-11/Tata-GenAI-Powered-Data-Analytics-Virtual-Job-Simulation-/blob/main/Screenshot%202025-09-10%20153608.png)
