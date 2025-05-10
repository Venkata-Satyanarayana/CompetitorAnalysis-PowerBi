# Competitor Analysis
Welcome to the Competitor Performance Analysis Dashboard, designed to provide a comparative view of the key performance indicators across three companies in the industry. This dashboard leverages Power BI to deliver insightful, data-driven visualizations that help identify:

📈 Which company is performing better overall

💰 Sales distribution and trends across the companies

👥 Customer base comparison (number of customers per company)

🌍 Regional performance
## Data Source Overview  [[Data Source]](https://1drv.ms/x/c/7a000c983cf15c01/EYy_DPurywVJgcHYeCIS7yYBb2GYWS0hvRXvzarAFQoAmA?e=p5sayy)
  This data set is generated randomly by using the Python code.
### •	Company Information 
  This module consists of basic details of company such as company name, company id.
### •	Customer information 
  This module consists of information of customers such as customer id, customer name, gender, age and country.
### •	Product Table 
  Product table consists of attributes like Product id, product name, category.
### •	Sales Table – Fact table 
  Sales table gives the information about the transaction id, company id, region, customer id, order date, product id, quantity, price.
### •	Date Table – Created by using DAX
  This entity contains the attributes such as Month, Date, Order date.
### •	Budget Table – Fact Table
This entity contains the attributes such as Budget , company_id , product_id, year and sales amount
### •	Year table 
This entity contains three years which was created by DAX.
## Metrics and Dimensions List(KPI's):
These are scenarios which we are going to visualize in our dashboard i.e. KPIs

•	Total customers for every company, product, year, country.

•	Highest number of customers for every company, product, year.

•	Best performing company for every product, year, country.

•	Sales of every country by company, product, year.

•	Sales of all companies and products for every year and country.

•	Percentage of Profit or loss for every company, product and year.

•	Average of profit or loss for every company, product and year.

•	Profit and loss of each product in company based on product and year.

•	Comparing sales, budget, profit of all companies by product and year.

•	Ranking of companies by profit of companies.

## Reporting Data Model Design
![Alt text](https://github.com/Venkata-Satyanarayana/CompetitorAnalysis-PowerBi/blob/6ed35e20d19618b240e88c3b7e05994f00316c78/Screenshot%202025-05-10%20222604.png)
## ✅ Conclusion
This Competitor Analysis Dashboard provides a comprehensive overview of how each of the three companies is performing across critical business metrics—Sales, Customer Count, and Profitability versus Budget. Through dynamic slicers and visual comparisons, stakeholders can easily identify:

Which company is leading in overall performance

Where sales and customer engagement are strongest

How each company is managing profit targets compared to budget expectations

The interactive features of the dashboard allow for customized analysis by time period, region, and product, enabling deeper insights for strategic planning and decision-making.

📂 For further insights and detailed breakdowns, please refer to the attached Power BI (.pbix) file, which contains all visualizations and data models used in this analysis.




