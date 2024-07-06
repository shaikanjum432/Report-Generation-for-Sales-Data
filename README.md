# Report Generation for Sales Data

## Project Overview

In this project, we focused on creating an automated system to generate daily, weekly, and monthly sales reports using Databricks notebooks. This system allows stakeholders to track their business performance by providing detailed sales reports at different time intervals.

## What Did I Do?

I developed a solution to automate the generation of sales reports on a daily, weekly, and monthly basis. The main objectives were to:

- Load sales data from a CSV file into a Databricks table.
- Create a dynamic reporting system using Databricks notebooks.
- Provide an interface for selecting the desired reporting period (daily, weekly, or monthly).
- Generate and display the sales reports based on the selected time period.

## How Did I Do?

### Step 1: Load Sales Data

- **Data Preparation**: I prepared the sales data in a CSV file, which includes fields like Id, date, sales amount, and city.
- **Data Upload**: I uploaded the CSV file to Databricks and created a table using the Databricks UI to make the data accessible for further processing.

### Step 2: Create Databricks Notebook

- **Notebook Setup**: I created a new Databricks notebook and set up a cluster for processing the data.
- **Data Loading**: I loaded the sales data from the CSV file into the notebook and created a temporary view for SQL queries.

### Step 3: Implementing Report Generation Logic

- **Dropdown Menu**: I added a dropdown menu to the notebook to allow users to select the report type (daily, weekly, or monthly).
- **Python and SQL Integration**: I wrote Python code to handle the date calculations for the selected time period and SQL queries to generate the reports.
- **Report Display**: I used Databricks' display functionality to present the generated reports in a readable format.

## Impact
- **Efficiency**: The automation of report generation saved significant time and effort, allowing stakeholders to receive up-to-date sales reports without manual intervention.
- **Accuracy**: Automated data processing reduced the risk of human errors, ensuring more accurate and reliable reports.
- **Flexibility**: The system provided flexibility to generate reports for different time periods (daily, weekly, monthly) based on the stakeholders' needs.
