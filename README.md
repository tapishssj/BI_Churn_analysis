# BI_Churn_analysis
Customer Churn analysis in banking domain using business intelligence tool


1. Requirement gathering: understanding business issues, problems client is facing, documenting them, questioning, creating BRDs
2. Data gathering and imported including xlsx and csv format. No direct query performed.
3. Data cleaning and Data transformation was done through inbuilt ETL tool Power query using M language and loaded on prem.
4. Data modelling was done through Power pivot with Star schema where there was only 1 fact table called "Bankchurn" and all the related dimension tables where connected.
5. A datemaster table was created from date of joining containing year,month, date separately.
6. A separate table "calculations" was created to store all the DAX measures for the analysis and building a clearer picture of exited and retained customers.
7. Used Report view to visualise all the new measures and created interactive infographics and chart to present the insights generated.
8. Enchanced and organised the UI for crisp understanding.
9. Implemented RLS according to the geographic regions.
10. Created workspace and provided the workspace access and published the report to the workspace.
