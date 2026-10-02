# ReportFlow-AI-Automated-Monthly-Business-Reporting-AI-Insights
## Monthly Business Report Automation

*All company names, customer names, and numbers shown in the visuals are replaced with sample values. The actual data and source code are not shared because of client confidentiality.*

## Problem

A small manufacturing business was preparing its monthly report manually.

Every month, the data had to be updated, charts had to be refreshed, the numbers had to be reviewed, and observations had to be written about things like profit, raw material costs, product performance, and customer payments.

The final report also had to be formatted and sent to the client by email.

This involved a lot of repetitive work every month.

I wanted to automate the whole process so that once the monthly data was available, one script could generate and send the complete report.

## Data

The project uses real transactional data from the business, including:

Sales data by product and month
Expense data by category
Raw material costs
Customer outstanding balances

The actual data is not included in this repository for privacy reasons.

## What I Built
### 1. Automated data refresh and charts

The monthly data is processed and the existing report charts are refreshed automatically.

The report includes five main visuals:

* Cash flow summary
* Expense breakdown with month-over-month changes
* Raw material cost trend
* Top and bottom performing products
* Customer outstanding balances

The charts do not need to be recreated manually every month. The script refreshes them using the latest data.

Sample visuals below use illustrative data.
<img width="1654" height="713" alt="sample_product_performance" src="https://github.com/user-attachments/assets/58323edd-99ac-481b-9bba-4e0c1b42a1d7" />

### 2. AI-generated monthly narrative

The numbers from the monthly report are passed to an LLM, which generates a short narrative to help the client understand the report.

The narrative covers things like:

* Profit and overall performance
* Raw material cost changes
* Product performance
* Customer payments and cash flow

The goal is not to replace the charts. The charts show the actual numbers, while the AI-generated narrative gives the client a quick summary of what changed and what may need attention.

### 3. Automated PDF report

The refreshed charts and the report content are combined into a single PDF.

The PDF is generated automatically using the latest monthly data, so there is no manual copy-paste or formatting work.

Sample report below uses illustrative data.
<img width="1654" height="1111" alt="sample_report_assembly" src="https://github.com/user-attachments/assets/00d237d4-fd95-492c-b99e-bd3ae29b43eb" />

### 4. Automated email

Once the report is ready, the script sends an email to the client automatically.

The email contains:

A short AI-generated summary of the month's report
The completed PDF report as an attachment

This gives the client a quick summary in the email while also allowing them to open the detailed report and review the charts.

## Results

The main goal was to remove the repetitive manual work involved in preparing the monthly report.

With the automated workflow:

* The latest data is processed automatically
* Existing charts are refreshed automatically
* The monthly narrative is generated using AI
* The PDF report is created automatically
* The client email is sent automatically with the narrative and PDF attached

The complete process can now be started with a single script instead of manually preparing each part of the report every month.

## What I Learned

This project helped me understand that using an LLM in a reporting workflow is more than just generating a summary.

The input given to the LLM needs to be structured properly, the output needs to follow a consistent format, and the generated narrative needs to be evaluated before it becomes part of an automated business process.

I also learned how to connect the different parts of the workflow right from data processing, chart generation, LLM output, PDF creation, evaluation, to email delivery into one end-to-end process.
