# Project 1: 

## Sales results for a reseller of luxury automobiles based in São Paulo.
 
### Business Problem: 

- The C-Board is evaluating whether or not to continue selling Jaguar-branded cars and would like to know how Jaguar car sales have evolved by year and by state.

### Tools: 

- Microsoft Power BI

- Libre Office Calc 

### Data source:

 - An Excel file with data collected from the company's sales and CRM system, with the following columns:

| Column      | Description         |
| ----------- | -----------         |
| Invoice Date | Invoice issue date |
| Manufaturer | Vehicle manufacturer |
| State | State where the sale took place |
| Sales Price |  Vehicle sales price|
| Pucharse Price | The price paid for the company by the vehicles|
| Total Discount| Total discount provided on the sale price |
| Cost Delivery | Cost of delivering the vehicle to the owner |
| Labor Costs | Labor Cost (sales personnel, mechanic, etc...)|
| Customer Name | Name of the customer who purchased the vehicle |
| Model | Vehicle model |
| Color | Vehicle color |
| Year | Vehicle manufacturing year |



![](https://github.com/AdrianoGilbert/Adriano_Portfolio/blob/main/Images/ColunasTabela.png?raw=true)


### Dashboard: 

![](https://github.com/AdrianoGilbert/Adriano_Portfolio/blob/main/Images/dashboard_carReseller.png?raw=true)




# Project 2:

## Acquire and Prepare Data from Web

![Data Science Workflow](ds-workflow.png)

 ### Goal of Project:

- Demonstrates how to prepare raw data acquired from the web that needs Data Wrangling. 

- Focus on acquiring and preparing steps of Data Science workflow.

### Tools:

- Jupyter Notebook

- pandas: Python library 

### Data source:

- [Wikipedia:Fundraising statistics](https://en.wikipedia.org/wiki/Wikipedia:Fundraising_statistics)

#### Step 1: Acquire

 - Import libraries

`import pandas as pd`

- Retrieve/Read the data

`url = 'https://en.wikipedia.org/wiki/Wikipedia:Fundraising_statistics'`

`table = pd.read_html(url)`

`table`

Assign variable url = "https://en.wikipedia.org/wiki/Wikipedia:Fundraising_statistics"
Retrieve the data tables = pd.read_html(url)
Assign the first DataFrame to a variable
HINT: tables is a list DataFrame containing all the data
Option 2: From csv file (if option 1 fails)
Use pd.read_csv() to read the file files/fundraising.csv
NOTE: Remember to assign the result to a variable (e.g., data)
Apply .head() on the data to see all is as expected
