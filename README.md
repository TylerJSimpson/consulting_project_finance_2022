# Finance LLC Consulting Project (May 22 - Present)
### Overview:   
### Engineered a cloud data solution utilizing Azure and Power Platform including Azure SQL, Azure Blob Storage, Power BI, and Power Automate.
___
### Problem:  
#### The customer lacked analytics infrastructure and wanted to begin making data-driven business decisions while minimizing costs and utilizing the Microsoft platform.
### Solution:  
#### ARCHITECTURE:  
* **Short-term license requirements** - Admin access to the customer's existing 365 Enterprise license and purchasing of PowerBI licenses as minimum requirements for a solution. 
* **Short-term tools** - Power Automate for data extraction and serving, SharePoint Lists for data storage, PowerBI for data transformation, aggregation, and reporting.
* **Long-term license & tool requirements** - Azure AD, SQL, Data Factory.
#### STORAGE:
* **Short-term:** - Create SharePoint lists to house data.
* **Long-term:** - Create Azure SQL database to house data.
#### EXTRACTION & LOADING:
* **Short-term:** - Power Automate scripts created to pull from 2 internal data sources and update the data in SharePoint lists.
* **Long-term:** - Azure Data Factory and Azure SQL stored procedures. 
#### TRANSFORMATION:
* **Short-term:** - PowerBI star schema created from SharePoint list data with SCD-1 and SCD-2 tables supporting the primary fact table. PowerBI DAX transformations and aggregations.
* **Long-term:** - SQL stored procedures orchestrated by Data Factory.
#### VISUALIZING & SERVING:
* PowerBI published web app for near real-time analysis utilizing security levels for departments. Reports generated via DAX code in Power Automate pipelines and sent out via Email to key stakeholders.  
### Further future considerations:  
* Developing an API for external customer data source(s).  
* Implementing Azure Logic Apps to fill gaps once migration to Azure is complete.
___
### Tools:
#### * Programming: T-SQL, DAX
#### * Cloud: Azure, Power Platform
#### * Visualization: Power BI
