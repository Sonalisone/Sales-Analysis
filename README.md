Created an interactive dashboard to track and analyze Sales Overview and Customer Details based upon Sales data. 

# SALES OVERVIEW DASHBOARD

### Dashboard Link : https://app.powerbi.com/groups/me/reports/93e60038-927d-46a3-bcc5-ef2c3679ffef/84ac31328aa088db5471?experience=power-bi

Here are some key highlights:

• Developed an interactive dashboard with advanced drill-down capabilities using complex parameters.

• Customized visualizations with filters and slicers for better data insights.

• Utilized various visualization types including Line Chart, Donut chart, Stacked Bar chart, Funnel, Map and Matrix to showcase data effectively.

• Connected and joined new tables, performed calculations to manipulate data, and enabled user-driven parameters.

📌DATA PREPARATION
To ensure the quality of the data, an essential step involved meticulous data cleaning procedures performed within Power BI's Power Query Editor. Corrections were made to erroneous data types, while the creation of calculated columns and measures facilitated the derivation of pertinent KPIs required for the analysis.

 Following Measures was written to find Budget Amount
 
         Budget Amount = SUM(FACT_Budgets[Budget])

    
Following Measures was written to find Sales


      Sales = SUM(FACT_InternetSales[SalesAmount])

Following Measures was written to find Sales - Budget
   
      Sales - Budget = [Sales] - [Budget Amount]

Following Measures was written to find  Sales / Budget Amount
  
    Sales / Budget Amount = DIVIDE( [Sales] , [Budget Amount] )

# Snapshot of Dashboard (Power BI Service)

![dashboard_snap- SALES OVERVIEW] ![SA Img1](https://github.com/user-attachments/assets/137b7315-54e6-418c-9b14-2ca68308f378)

![dashboard_snap - CUSTOMER DETAILS](https://github.com/user-attachments/assets/cb956107-3473-459e-9f9a-733183a1bb21)

