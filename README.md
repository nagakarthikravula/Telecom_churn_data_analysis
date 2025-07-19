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

Step4:(Visualization based on Questions)
--> 1.Churn_Rate by Record_Count(Table)
--> 2.Churn_Rate and Retention_Rate by Churn(Used stacked bar chart)
--> 3.Churn_Rate by Payment Method(Bar chart)
--> 4.Churn_Rate by Senior_Citizen(Pie chart)
--> 5.Churn_Rate by Internet_Service(Pie Chart)
--> 6.Churn_Rate by Monthly_Charges($)(Bar Chart)
--> 7.Churn_Rate by Techinical_Support
--> 8.Churn and Retention Rate By Tenure(Line Chart)



