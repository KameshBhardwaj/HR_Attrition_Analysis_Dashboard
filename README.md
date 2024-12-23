# Employee Attrition Analysis Project

## Problem Statement:
The goal of this project was to analyze employee attrition rates across various factors, identify trends and patterns, and provide recommendations to reduce attrition. By leveraging data cleaning techniques, SQL queries, and Power BI for visualization, this project seeks to uncover insights into the causes of employee turnover and offer actionable solutions.

## Approach:

### 1. **Data Collection and Cleaning in Excel:**
   - **Data Sources:** Employee attrition data was collected from the organization’s HR management system.
   - **Data Cleaning:** The initial data was cleaned in Excel by handling missing values, correcting data inconsistencies, and formatting the data for analysis. Key columns included employee demographic information, job roles, performance ratings, and details regarding attrition.

### 2. **Data Import to SQL:**
   - After cleaning the data in Excel, it was imported into MySQL for deeper analysis using SQL queries.
   - SQL was used to calculate attrition rates across various dimensions like department, job role, age group, marital status, income range, years at company, and more.

### 3. **SQL Queries for Analysis:**
   Several queries were run to calculate attrition rates for different variables:

   - **Overall Attrition Rate:** 16.20%
   - **Attrition by Department:** Highest attrition was observed in Human Resources (29.79%).
   - **Attrition by Job Role:** Research Directors (23.95%) and Research Scientists (18.42%) had the highest attrition rates.
   - **Attrition by Age Group:** The 18-25 age group showed the highest attrition (35.89%).
   - **Attrition by Income Range:** Employees in the 40K-80K income range had the highest attrition rate (17.40%).
   - **Attrition by Work-Life Balance and Job Satisfaction:** Those with a rating of 1 on work-life balance and job satisfaction had the highest attrition rates (25.45% and 22.91% respectively).
   - **Attrition Based on Years Since Last Promotion:** Employees who hadn't received a promotion in the past 5 years showed a significantly higher attrition rate (24%).

### 4. **Data Visualization in Power BI:**
   After analyzing the data in SQL, the data was exported to Power BI to create interactive dashboards and gain visual insights. The key findings from the Power BI dashboard included:

   - **Attrition Rate by Department:** 
     - Research & Development had 447 employees leave (15.06% attrition rate).
     - Sales had 198 employees leave (16.89% attrition rate).
     - Human Resources had 56 employees leave (29.79% attrition rate).

   - **Attrition Rate by Income Range:**
     - 40K-80K range had the highest attrition (17.40%).
     - The 10K-30K range had a slightly lower attrition rate (16.79%).

   - **Attrition Rate by Job Role:**
     - Sales Executive had the highest number of leavers (162), with an attrition rate of 16.89%.
     - Research Directors and Managers had significantly lower attrition rates.

   - **Attrition by Age Group and Gender:**
     - The 31-40 age group had the highest attrition (16.70%).
     - The 21-30 age group had 246 employees leave with a higher attrition rate (23.29%).

   - **Work-Life Balance and Job Satisfaction:**
     - Employees rating their work-life balance as 1 had the highest attrition rate (25.45%).
     - Employees with low job satisfaction (rating of 1 or 2) also had high attrition rates.

### 5. **Key Performance Indicators (KPIs):**
   - **Total number of employees:** 4327
   - **Average performance rating:** 3.15
   - **Overall Attrition Rate:** 16.20%

### 6. **Recommendations to Reduce Attrition:**

   Based on the analysis, the following recommendations can be made to reduce employee attrition:
   - **Target High Attrition Departments:** Human Resources, Sales, and Research & Development departments have the highest attrition rates. It would be beneficial to focus on employee satisfaction and retention strategies in these departments.
   - **Improve Job Satisfaction:** Employees in roles like Sales Executive, Research Scientists, and Managers are more likely to leave. Conducting regular feedback sessions, offering career advancement opportunities, and enhancing job satisfaction through incentives or flexible work conditions can help reduce attrition.
   - **Address Work-Life Balance:** Employees who rate their work-life balance poorly are more likely to leave. Providing flexible work arrangements, wellness programs, and creating a supportive work environment can improve retention.
   - **Monitor Employees in the First 5 Years:** Employees with less than 5 years of tenure, especially those who have not received promotions recently, exhibit a higher tendency to leave. Offering career growth opportunities, mentorship, and training programs during the early years can help in reducing turnover.
   - **Focus on Income Ranges with High Attrition:** Employees earning between 30K and 60K have a higher attrition rate. Reviewing compensation packages, providing additional incentives, or aligning salaries with industry standards may help in reducing attrition.
   - **Promote Training and Development:** Employees who had little or no training showed higher attrition rates. Offering ongoing training and professional development can improve job satisfaction and retention.

## Conclusion:

In conclusion, this project provided insights into the factors influencing employee attrition within the organization. Through SQL analysis and Power BI visualization, we identified key trends such as high attrition among younger employees, departments like Human Resources, and roles like Sales Executive. By addressing the factors driving attrition, particularly job satisfaction, work-life balance, and career development, organizations can effectively reduce turnover and improve employee retention.

## Tools Used:
- **Excel** for data cleaning and preprocessing.
- **MySQL** for performing advanced data analysis and SQL queries.
- **Power BI** for creating interactive visualizations and dashboards.

### Future Recommendations:
- **Employee Engagement Programs:** Regular surveys and feedback mechanisms can be introduced to monitor employee satisfaction and take proactive steps.
- **Retention Strategies:** Organizations could implement tailored retention strategies based on data insights, such as improving work-life balance or offering higher promotion opportunities in high-risk departments.

---

## Files:

- **[Employee_Attrition.csv](./Employee_Attrition.csv)**: Dataset used for analysis.
- **[SQL Queries](./SQL)**: All SQL queries used for analysis.

---

Feel free to connect with me for further details or if you want to discuss any part of this project!

[Connect with me on LinkedIn](https://www.linkedin.com/in/kamesh-bhardwaj-270005321/)
