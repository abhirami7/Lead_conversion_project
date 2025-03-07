# Lead Conversion Analysis
This project focuses on analyzing lead conversion data and visualizing key metrics to understand the effectiveness of the lead conversion funnel. The dataset used in this analysis contains detailed information about leads, such as their demographic data, monthly income, loan amounts, and whether they were contacted or approved. The primary goal of this analysis is to evaluate the stages of lead conversion from leads created to those contacted and finally approved.

## Project Structure
### Data Preprocessing:

- Loaded the dataset using Pandas.
- Checked for missing values, duplicates, and data inconsistencies.
- Converted the Lead_Creation_Date and DOB columns into the appropriate date format.
- Calculated the total number of leads created, leads contacted, and leads approved.

### Data Visualization:

Created visualizations in Looker Studio:
- Funnel Chart: Displays the progression of leads through the conversion funnel.
- Stacked Column Chart: Shows additional insights into lead sources and their corresponding categories.

## Key Findings/Insights
- Leads Created: 69,713 total leads were created.
- Contacted Leads: Out of the total, 45,275 leads were contacted.
- Approved Leads: Only 1,020 leads were approved, indicating a high dropout rate in the lead funnel.

## Tools & Technologies
- Pandas: For data manipulation and cleaning.
- Looker Studio: For data visualization, including the creation of funnel charts and stacked column charts.
