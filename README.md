# Telecom_churn_data_analysis

Objective:Analysing the Telecom-Churn data and giving insights to the stakeholder for strategic decision making

Step-1:(Data Collection and Storing)
--> Collected the Telecom-Churn Data from kaggle and stored it in google bucket
-->Loaded the Dataset into the bigquery

Step-2:(Data Cleaning and standardizing)
--> Cleaned The Entire dataset
--> Made sure that no NULL Values present
--> No Duplicate Values Present
--> Standardized columns wise

Step-3:(Performed EDA process)
--> Wrote queries based on StakeHolder questions
-->Stakeholder Questions
    Overall churn measurement (business KPI)
    Demographic analysis (Senior Citizen)
    Contract and tenure analysis (service duration and type impact)
    Payment method analysis (payment friction)
    Service usage analysis (InternetService + add-ons)
    Monthly charges impact (pricing strategy)
    Add-on services influence (cross-selling and retention opportunities)
--> EDA Queries are in EDAqueries page

Step-4:(Visualization based on Questions)
--> 1.Churn_Rate by Record_Count(Table)
--> 2.Churn_Rate and Retention_Rate by Churn(Used stacked bar chart)
--> 3.Churn_Rate by Payment Method(Bar chart)
--> 4.Churn_Rate by Senior_Citizen(Pie chart)
--> 5.Churn_Rate by Internet_Service(Pie Chart)
--> 6.Churn_Rate by Monthly_Charges($)(Bar Chart)
--> 7.Churn_Rate by Techinical_Support
--> 8.Churn and Retention Rate By Tenure(Line Chart)

Step-5:(Dashboard)
[Dashboar_link](https://lookerstudio.google.com/reporting/aca1b378-af27-4014-8a31-4ce62b9abd38)

Step-6:(Key Insights & Recomendations)
**Contract Type:**
Month-to-Month contracts have the highest churn rate, showing that customers with shorter commitments are more likely to leave.
**Demographics:**
Senior citizens face higher churn rates compared to non-senior customers, indicating the need for age-focused retention strategies.
**Internet Service:**
Customers using Fiber Optic internet service show the highest churn rate, possibly due to higher costs or service dissatisfaction.
**Monthly Charges:**
Customers paying 78$ to 98$ monthly charges have the highest churn rate,suggesting that this pricing segment
needs improved value or service support.
**Payment Method:**
Payment methods like Credit Card and Bank Transfer (automatic payments) have lower churn rates, while Electronic 
Check (eCheck) users show higher churn rates, indicating these automatic payment users may have more stable payment
behaviour and loyalty.
**Support Services:**
Customers without Tech Support have significantly higher churn rates, highlighting the importance of providing 
reliable technical support services.
**Tenure:**
Customers with lower tenure (1-6 months) show high churn rates, indicating that newer customers are more 
likely to leave if not engaged properly.
Interestingly, even customers with long tenure (48+ months) also show high churn rates, possibly due to contract renewals, outdated plans, or market competition offering better alternatives.

**Recommendations**

**Change Subscription Plans**
Replace month-to-month plans with minimum 3-month plans to reduce churn.
**Support Senior Citizens**
Make plans easier for senior citizens and encourage them to take longer plans.
**Promote Internet Services**
Convince customers without internet service to take any internet plan.
**Give Offers on More Services**
Customers with charges between ₹78-₹98 often take some services. Giving them offers to take more services can reduce churn.
**Improve Tech Support**
Quick and good tech support helps reduce churn.

