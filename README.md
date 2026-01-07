# Insurance Analytics with Sentiment

## Project Overview

This project combines ***insurance data analysis*** with ***customer feedback sentiment analysis*** to provide actionable insights.

- Insurance data gives an overview of claims, policies, premiums, and customer information.

- Customer feedback is analyzed for sentiment using ***Google Sheets***, and the results are visualized in ***Power BI Desktop***.

- The goal is to understand both operational metrics and customer satisfaction.

## Datasets

### Insurance Data

| **Column Name**       | **Data Type**     | **Description** |
|------------------|---------------|-------------|
| **Active/Inactive**   | Text          | Status of the policy |
| **Age**               | Number        | Customer's age |
| **Age Groups**        | Text          | Derived column grouping ages (e.g., 20-30, 31-40) |
| **Claim Date**        | Date          | Date of claim submission |
| **Claim Amount**      | Number        | Amount claimed by the customer |
| **Claim Number**      | Text   | Unique identifier for claims |
| **Claim Status**      | Text          | Status of claim (Approved, Pending, etc.) |
| **Coverage Amount**   | Number        | Total coverage of the policy |
| **Customer ID**       | Text   | Unique identifier for customers |
| **Gender**            | Text          | Customer gender |
| **Policy End Date**   | Date          | Policy expiration date |
| **Policy Number**     | Text   | Unique policy identifier |
| **Policy Start Date** | Date          | Policy start date |
| **Policy Type**       | Text          | Type of insurance policy |
| **Premium Amount**    | Number        | Premium paid for the policy |


### Feedback Dataset Table (Sentiment Analysis)

***The sentiment analysis converts qualitative feedback into quantitative insights, helping to identify trends in customer satisfaction and correlate feedback with policies or claims.***

| **Column Name**       | **Data Type**   | **Description** |
|------------------|------------|-------------|
| **Customer Name**     | Text       | Name of the customer providing feedback |
| **Feedback**          | Text       | Customer feedback text |
| **Sentiment Score**   | Number     | Sentiment score (0–1) obtained via Google Sheets |
| **Sentiment Label**   | Text       | Categorized sentiment based on score (Positive, Neutral, Negative) |

## Power BI Report

### Page 1 – Insurance Analysis

- Visuals:

  - Number of claims by claim status

  - Premium amount by policy type

  - Count of active/inactive policies

- Card visuals 
   - Claim Amount
   - Coverage Amount
   - Premium Amount
- Slicers:

  - Policy Number

  - Customer ID

  - Claim Number

### Page 2 – Feedback Sentiment Analysis

- Visuals:

  - Count of customers by Sentiment Label

  - Table showing Feedback, Sentiment Score, and Sentiment Label

- Slicers:

  - Sentiment Label

  - Sentiment Score

- Insights:

  - Enables filtering feedback by sentiment

  - Highlights patterns in customer satisfaction

  - Supports data-driven decision-making

## conclusion 

This project demonstrates how ***insurance data*** and ***customer feedback sentiment analysis*** can be combined to gain actionable insights. The Power BI report provides an interactive and visual way to explore claims, policies, and customer satisfaction, helping organizations make ***data-driven decisions*** and improve overall customer experience.
