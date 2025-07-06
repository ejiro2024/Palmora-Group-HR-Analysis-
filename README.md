## Palmora Group HR Aalysis
![Palmora-group](Palmora-group.jpg)

# Palmoria Company: Employee Data Analysis Report

## Table of Content

- [Introduction](#Introduction)
- [Project Overview](#Project-Overview)
- [Data source](#Data-source)
- [Tools used](#Tools-used)
- [Data Analysis](#Data-Analysis)
- [Visualisations](#Visualisations)
- [Key Insights](Key-Insights)
- [Recommendations](#Recommendations)
- [Conclusion](#Conclusion)

## Introduction
This report provides insights into the employee structure at **Palmoria**, with a primary focus on gender-based analysis across departments and locations. It also includes evaluations of salary distributions, regulatory compliance, and bonus allocation.

## Project Overview
Palmoria's management seeks to understand employee distribution, identify potential gender pay gaps, assess regulatory salary compliance, and allocate bonuses based on performance ratings. This analysis serves as a tool for improved decision-making and HR policy enhancements.

## Data Source
The dataset was extracted from Palmoria's internal employee records and includes the following fields:
- **Name**
- **Gender**
- **Department**
- **Salary**
- **Location**
- **Performance Rating**

## Data Cleaning
Steps taken to prepare the data:
1. **Removed** employees with missing salary (assumed no longer with the company).
2. **Removed** records with null departments.
3. **Assigned** "Undisclosed" gender status to missing gender values.
4. **Standardized** text fields (e.g., trimmed whitespace).

## Data Analysis & Visualizations

### 1. Gender Distribution in the Organization
- A bar chart shows the total number of employees by gender.
- Breakdown by **region** and **department** reveals localized trends in gender representation.

### 2. Rating Insights by Gender
- Count of employees by rating (e.g., "Very Good", "Poor") and gender.
- Highlights how different genders are performing or being evaluated across roles.

### 3. Salary Structure and Gender Pay Gap
- **Average salary** by gender reveals a slight male bias in pay.
- A breakdown by **department** and **location** shows departments where gaps are significant.
- Chart: Boxplot of salary by gender and department.

### 4. Regulatory Compliance Check
- Regulation: Employees must earn **minimum $90,000**.
- **Pass/Fail count** across the company.
- Identified departments and employees falling short of this benchmark.

### 5. Salary Band Distribution
- Salary distribution in **$10,000 bands** (e.g., $40k-$50k, $50k-$60k, etc.).
- Grouped by **region** to identify low and high earning zones.
- Chart: Histogram or bar chart showing distribution.

### 6. Bonus Allocation Based on Rating

| Rating       | Bonus % |
|--------------|----------|
| Very Good    | 15%     |
| Good         | 10%     |
| Average      | 5%      |
| Poor         | 2%      |
| Not Rated    | 0%      |

- **Calculated** bonus per employee.
- **Total Pay = Salary + Bonus**
- Aggregated total bonus payout by region and for the entire company.
- Charts: Bonus distribution by rating and region.

## Visualisations

## Insights Summary
- **Gender Imbalance** in Legal and Support departments where one gender dominates.
- **Undisclosed Gender** cases should be addressed through updated HR profiling.
- **Significant Pay Gap** in Engineering and Support departments in Kaduna.
- **Non-Compliance** with salary regulation for 3 employees in Legal and Support.
- **Bonus Payout**: Company to disburse a total of `$XX,XXX` as performance bonuses.

## Recommendations
- Enforce equal opportunity policies in gender-imbalanced departments.
- Reassess salary structures to address gaps, especially in Support roles.
- HR should re-profile staff with missing or outdated information.
- Conduct annual salary audits to remain compliant with regulations.
- Consider performance-linked incentive schemes for transparency.

## Conclusion
This analysis provides actionable intelligence to Palmoria’s leadership. Addressing the highlighted disparities and compliance issues will help foster a more equitable, transparent, and high-performing workplace.

### Back to top 
###### [Table of Content](#Table-of-Content)
