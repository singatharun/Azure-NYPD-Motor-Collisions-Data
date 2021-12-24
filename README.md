# This project is aimed at developing power Bi report by using data from Azure synapse analytics.


Initially, Data is downloaded from New York Open Data Website: https://opendata.cityofnewyork.us/. into local computer in CSV form.

Step 1:
Using SQL Server Management Studio data is upload from local computer to Azure SQL database which was already created in azure. 
Step 2:
Data pipeline is created using Azure Data Factory to copy data from Azure SQL database to Azure synapse analytics. Here, Azure Data Lake storage Gen2 is used as an linked service storage. 

Step 3:
After successfuly completion of data copying from Azure sql database to Azure synapse analytics, Power Bi and synapse analytics are linked through azure synapse analytics connector in power Bi.
Step 4:
Visualizations are data made using the dataset that contains more than 1.6 Millions rows. 

Below is the link for the visualization:
https://app.powerbi.com/links/vFTGWVoOTU?ctid=96464a8a-f8ed-40b1-99e2-5f6b50a20250&pbi_source=linkShare

Dataset Link:
NYPD Motor Vehicle Collisions: https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95
