# Customer Satisfaction Analysis - Call Centre Dataset

## Project Overview

This project focuses on analyzing a call center dataset to derive meaningful insights and generate a comprehensive report using Power BI. The primary objective is to evaluate the performance of call center agents based on various metrics such as call resolution, speed of answer, and customer satisfaction. The analysis will help the company identify key areas of improvement and recognize top-performing agents.

## Dataset Description

The dataset consists of the following columns:

- **CALLER ID**: Unique identification number for each caller.
- **AGENT**: Names of the agents handling the calls.
- **DATE**: Date when each call was received.
- **TIME**: Time of each call in hh:mm:ss format.
- **TOPIC**: Subject/topic of the calls received.
- **ANSWERED**: Indicates whether the call was answered or abandoned (Y/N).
- **RESOLVED**: Indicates whether the issue was resolved by the agent (Y/N).
- **SPEED OF ANSWER IN SECOND**: The time taken to answer each call.
- **AVG. TALK DURATION**: Average duration spent on each call by the agent.
- **SATISFACTION RATE**: Rating of each agent based on customer satisfaction.

## Preprocessing Steps

Before conducting the analysis, the following preprocessing steps were performed:

1. **Handling Missing Data**:
   - Replaced all null/blank values with `0` to maintain data consistency.
   
2. **Data Type Conversion**:
   - Changed data types where necessary to ensure accurate calculations and visualizations.
   
3. **Feature Engineering**:
   - Extracted seconds and minutes from the `AVG. TALK DURATION` column.
   - Created a new column named `Duration on Calls` to represent the duration of each call.

## Analysis Objectives

The goal of this analysis is to generate insights that will help the company improve customer service quality and agent performance. The following KPIs and requirements were defined by the client:

1. **Total Number of Calls**:
   - Calculate the total number of calls received by the call center.

2. **Answered and Rejected Calls**:
   - Create new columns to calculate the total number of calls answered and rejected.

3. **Percentage of Answered and Rejected Calls**:
   - Calculate the percentage of calls answered and rejected.

4. **Resolved and Unresolved Calls**:
   - Create new columns to calculate the total number of calls resolved and unresolved.

5. **Top Performing Agents**:
   - Identify the agent who answered the maximum number of calls.
   - Identify the agent with the highest satisfaction rate.

6. **Calls by Topic**:
   - Use a chart to display the total number of calls by topic.

7. **Duration on Calls**:
   - Analyze the duration of calls handled by each agent.

8. **Calls by Date**:
   - Visualize the total number of calls received by days and months for the year 2021.

9. **Interactive Filters**:
   - Use slicers to create interactive reports by month and day.

10. **Overall Performance Ratings**:
    - Provide a comprehensive performance rating for the year 2021.

11. **Custom Visualization**:
    - Use a suitable custom chart to display the overall satisfaction rating for 2021.

## Steps to Create the Power BI Dashboard

1. **Load the Dataset**:
   - Import the call center dataset into Power BI.

2. **Data Cleaning and Transformation**:
   - Replace null values with `0`.
   - Change data types where needed (e.g., convert `DATE` to date type, `TIME` to time type).
   - Create the `Duration on Calls` column from `AVG. TALK DURATION`.

3. **Create Calculated Columns**:
   - Add columns to calculate the total number of calls answered, rejected, resolved, and unresolved.
   - Create percentage calculations for answered and rejected calls.

4. **Build Visualizations**:
   - **Bar Chart**: Display the total number of calls by topic.
   - **Line Chart**: Show the total calls by day and month for 2021.
   - **Pie Chart/Donut Chart**: Visualize the distribution of resolved vs. unresolved calls.
   - **Slicer**: Enable interactive filtering by month and day.
   - **Custom Chart**: Display the overall 2021 satisfaction rating.

5. **Analyze Top Agents**:
   - Use DAX functions to find the agent with the maximum calls answered and the highest satisfaction rate.

6. **Interactive Dashboard**:
   - Combine all the visualizations into a single interactive dashboard.
   - Ensure that the slicers affect all relevant charts and metrics.

7. **Review and Adjust**:
   - Review the dashboard for accuracy.
   - Adjust the visuals for better clarity and insight.

8. **Publish the Report**:
   - Publish the Power BI report to the Power BI service for sharing and further analysis.

## Conclusion

This project demonstrates how to effectively use Power BI to analyze customer satisfaction data in a call center environment. By following the steps outlined above, you can create a comprehensive dashboard that provides actionable insights into agent performance and customer satisfaction.
