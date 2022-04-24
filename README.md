# Unicorns-Insights
A static report that tells the story of Unicorns and the metrics that made them achieve the Unicorn status.

link for browser view of the report -- https://app.powerbi.com/view?r=eyJrIjoiNzFhNDJmMzQtYjg1NC00ZGVhLWJmZjMtNzRkYWMwZWQ5YTJmIiwidCI6ImQwMjViNjgwLWVmNjAtNDc4Zi1hNmZjLTIyMGU3Yzc0ODAzMCJ9&pageName=ReportSectioncd7fffefbfb03371a2e1


# Unicorns: Term coined by Aileen Lee to describe Organizations that reached a total Valuation of 1Billion Dollars.

# About the Dataset:
The dataset contains 1074 rows representing each Unicorn Organizations,the Year they were founded, the region they belonged to, the funding they initially received, the Investors and the Date they became Unicorns.

# Approach Taken:
## 1. Data Cleaning and Transformation:
The data was loaded on to notebook and performed Data Cleaning using Pandas. Adding additional columns like the Number of Investors, Number of Years that took for an Organization to reach Unicorn status, Spilliting Investors across different columns, extracting years from the Date they were founded, calculation the total number of Investors for each Organization and loading it back as a cleaned data.
## 2. Insight Chart:
The cleaned data was loaded onto Power BI and created a Static Report with a neat design that has information about their Journey from the start to current date.
The chart has Insights that shows the relations between the Nmber of Investors, Years taken to achieve Unicorn Status. While the normal approach would be to talk about the Profitable part, I made an attempt to look into Unicorns that incurred loss and turns out 44% of the total unicorns have incurred loss. This was done by calculating the metric of Networth (Valuation - Funding).

# File Uploads:
    1.This project has a Power BI report screenshot as a png.
    2.Notebook file used to clean data.
    3.Original Data
    4.Cleaned Data.
    5.Link to a Browser View of the Report. This link is avaliable on top of Readme under Unicorn Insights
