# SaaS KPI Analysis by SQL: DELIVR Food Delivery Analytics

## Project Overview

DELIVR is an innovative food delivery startup that facilitates bulk meal orders from a variety of eateries, offering users the convenience of ordering from multiple establishments in a single transaction. This project aims to analyze DELIVR's data to extract actionable insights related to revenue, costs, user behavior, and overall business performance.

This README file outlines the key objectives and methodologies used in the analysis, providing a clear understanding of the project's scope and significance. The SQL code included in this repository serves as a practical demonstration of advanced data analysis techniques applied to a real-world business scenario.

## Project Structure

The provided SQL scripts are designed to perform a comprehensive analysis of DELIVR's business metrics. The analysis focuses on several key areas:

1. **[Revenue, Cost, and Profit Analysis](https://github.com/Sophie-XL/SaaS-KPI-Analysis/blob/811b204c902073b0943d647483791d8b0ff2d362/Revenue%2C%20cost%2C%20and%20profit%20analysis)**: Calculate revenue generated per customer, weekly and monthly revenue, meal costs, and overall profit margins.
Understanding the revenue streams and profit margins helps in identifying the most profitable eateries and meals, allowing for strategic inventory and marketing decisions. Tracking costs associated with stocking meals enables more efficient budget allocation and cost-saving measures.
3. **[User-Centric KPIs](https://github.com/Sophie-XL/SaaS-KPI-Analysis/blob/811b204c902073b0943d647483791d8b0ff2d362/User-centric%20KPIs%3A%20Registration%2C%20Active%20users%2C%20Retention%20%26%20Growth)**: Track user registrations, monthly active users (MAU), user retention rates, and growth metrics. By analyzing user registration trends, activity levels, and retention rates, DELIVR can develop targeted strategies to enhance user engagement and retention.
4. **[Unit Economics](https://github.com/Sophie-XL/SaaS-KPI-Analysis/blob/811b204c902073b0943d647483791d8b0ff2d362/Unit%20Economics%3A%20Average%20Revenue%20Per%20User%20(ARPU)%20and%20its%20distribution)**: Determine average revenue per user (ARPU) and its distribution, as well as segment users based on their spending patterns. Understading unit economy can help focus marketing efforts on high-revenue and high-order users for better ROI, creating personalized marketing campaigns, and turning low and mid-revenue users into high-value customers.
5. **[Executive Reports](https://github.com/Sophie-XL/SaaS-KPI-Analysis/blob/811b204c902073b0943d647483791d8b0ff2d362/Create%20Executive%20Reports%3A%20improving%20readability%20for%20non-technical%20users)**: Generate executive-level summaries and pivot tables to improve the readability of complex data for non-technical stakeholders. Executive reports and pivot tables provide a high-level overview of business performance, supporting informed decision-making by the management team.

## SQL Skills Used

The SQL code demonstrates a range of advanced SQL techniques and concepts, including:

- [x] **Aggregate Functions**: Used to calculate sums, averages, and counts for various metrics (e.g., revenue, costs, user counts).
- [x] **Common Table Expressions (CTEs)**: Employed to break down complex queries into manageable parts, improving readability and maintainability.
- [x] **Joins**: Utilized to combine data from multiple tables, enabling comprehensive analysis of related datasets (e.g., meals, orders, stock).
- [x] **Window Functions**: Applied to calculate running totals, growth rates, and rankings, providing deeper insights into trends and performance metrics.
- [x] **Date Truncation and Formatting**: Used to group data by specific time periods (e.g., weeks, months, quarters) for time-based analysis.
- [x] **Pivot Tables**: Created using the `tablefunc` extension to transform and summarize data in a more digestible format for executive reporting.
