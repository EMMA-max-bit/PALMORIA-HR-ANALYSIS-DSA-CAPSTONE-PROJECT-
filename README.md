## PALMORIA-HR-ANALYSIS-DSA-CAPSTONE-PROJECT

### 1.0 Executive Summary
This report presents a comprehensive HR analytics study for the Palmoria Group, a manufacturing company based in Nigeria. The primary objective of this analysis is to address concerns regarding gender inequality across its three regions in Abuja, Kaduna and Lagos. Leveraging the provided HR data, this study focuses on key areas such as gender distribution, performance ratings, salary structure, and compliance with minimum wage regulations. The insights derived from this analysis aim to provide actionable recommendations to the Palmoria Group's management for fostering a more equitable and inclusive workplace.
### 1. Introduction
The Palmoria Group has recently faced public scrutiny due to allegations of gender inequality within its operations. This situation poses a significant threat to the company's reputation and its strategic ambition for expansion. In response, Mr. Yunus Shofoluwe, the CHRO, has initiated an HR analytics project to thoroughly investigate the extent of these issues and propose effective solutions. This report serves as the outcome of that investigation, providing a data-driven decision on the current state of gender equality within the organization.
### 2.0 Data Source
The analysis was conducted using dataset sent by DSA capstone project, which contains various HR-related information for employees across Palmoria Group's three regions: Abuja, Kaduna, and Lagos. The dataset includes information on employee names, gender, department, location, bonus rates, salary, bonus amount, and performance ratings.
### 2.1 Data Preparation and Cleaning
Prior to analysis, the raw dataset underwent several cleaning and preparation steps to ensure data quality and consistency, as per the requirements outlined in Case Study 3 of the DSA capstone project. Below are the cleaning processes;
Handling Undisclosed Gender: Employees who did not disclose their gender were assigned a generic status of 'Undisclosed' to ensure all records were accounted for in gender-related analyses.
Removing Inactive Employees: Records of employees without a salary (indicating they are no longer with the company) were removed from the dataset to focus on the active workforce.
Addressing NULL Departments: Entries where the department was listed as 'NULL' were excluded from the analysis to maintain data integrity and relevance.
These steps were performed using a Power BI Query, ensuring a robust and clean dataset for subsequent analysis.

### 2.2 Analytical Approach
The analysis focused on addressing the specific pointers provided by Mr. Gamma, an insider, to uncover gender-related disparities and salary insights. The following key areas were investigated:
Gender Distribution: Examination of gender representation across the entire organization, and then broken down by regions and departments.
Performance Ratings: Analysis of employee performance ratings stratified by gender to identify any potential biases.
Salary Structure and Gender Pay Gap: A detailed investigation into the average salaries across genders, departments, and regions to pinpoint areas with significant pay disparities.
Minimum Wage Compliance: Assessment of the company's adherence to a newly adopted regulation requiring a minimum salary of 90,000, including a distribution analysis of salaries in 90,000 bands.
Bonus Pay Analysis: Calculation and visualization of total compensation (salary inclusive of bonus) by region and company-wide.
### 2.3 Analytical Tool Used
This analysis was performed using Power BI for the analytical framework and visualization types were designed with Power BI's capabilities in mind, providing a blueprint for implementation.
3. Findings and Analysis
This section presents the key findings from the HR data analysis, supported by visual representations generated using Power BI. These visualizations aim to provide clear and actionable insights into the state of gender equality and salary practices within the Palmoria Group.

### 3.1 Gender Distribution
### 3.1.1 Overall Gender Distribution
The overall gender distribution within the Palmoria Group reveals the proportion of male and female employees across the entire organization. This initial view provides a high-level understanding of the workforce composition.[Download here](https://github.com/EMMA-max-bit/PALMORIA-HR-ANALYSIS-DSA-CAPSTONE-PROJECT-/blob/main/Overall%20gender%20employee.gif)
 
### 3.1.2 Gender Distribution by Region
Further breakdown of gender distribution by region highlights how male and female employees are represented in Abuja, Kaduna, and Lagos. This regional perspective is crucial for identifying localized imbalances[Download here](https://github.com/EMMA-max-bit/PALMORIA-HR-ANALYSIS-DSA-CAPSTONE-PROJECT-/blob/main/Gender%20distribution%20by%20dept.gif)

### 3.1.3 Gender Distribution by Department
An in-depth look at gender distribution across various departments provides granular insights into which specific areas might be predominantly male or female, indicating potential areas for targeted intervention.[Download here](https://github.com/EMMA-max-bit/PALMORIA-HR-ANALYSIS-DSA-CAPSTONE-PROJECT-/blob/main/Gender%20distribution%20by%20dept.gif)

### 3.2 Employee Ratings by Gender
Analyzing performance ratings by gender helps to ascertain if there are any systemic biases in how employees are evaluated. This is a critical step in addressing potential inequalities beyond just representation.[Download here](https://github.com/EMMA-max-bit/PALMORIA-HR-ANALYSIS-DSA-CAPSTONE-PROJECT-/blob/main/Empoyee%20rating%20by%20gender.gif)

### 3.3 Salary Structure and Gender Pay Gap
### 3.3.1 Average Salary by Gender
This analysis directly addresses the presence of a gender pay gap by comparing the average salaries of male and female employees across the entire Palmoria Group.

### 3.3.2 Average Salary by Department and Gender
To identify specific departments where a gender pay gap might be more pronounced, average salaries are further broken down by department and gender. This helps in pinpointing areas that require immediate attention.
### 3.3.3 Average Salary by Region and Gender
Similarly, examining average salaries by region and gender helps to understand if geographical location plays a role in salary disparities between male and female employees.

### 3.4 Salary Distribution and Minimum Wage Compliance
### 3.4.1 Compliance with $90,000 Minimum Salary
An important aspect of this analysis is to determine if the Palmoria Group complies with the new regulation requiring a minimum salary of $90,000. The number of employees falling below this threshold is a key indicator.

### 3.4.2 Salary Distribution by $10,000 Bands
To provide a clearer picture of the salary landscape, employee salaries are grouped into $10,000 bands. This visualization helps in understanding the concentration of employees at different income levels.

### 3.4.3 Salary Distribution by $10,000 Bands and Region
Further segmenting the salary bands by region allows for the identification of regional variations in salary distribution, which can inform localized policy adjustments.

### 3.5 Total Compensation Analysis
### 3.5.1 Total Amount Paid (Salary + Bonus) by Region
This analysis provides an overview of the total financial outlay for employees, including both salary and bonus, across different regions. This can be useful for budget planning and understanding regional compensation trends

### 4. Recommendations Analytical Insights
Based on the findings presented in this analysis, the following recommendations are proposed to the Palmoria Group management to address the identified issues and foster a more equitable and compliant HR environment:
#### 1.Conduct a Deeper Dive into Gender Pay Gaps:
While overall average salaries might show a gap, a more granular analysis within specific departments and roles is necessary to understand the root causes. Investigate if the pay gap is due to differences in roles, experience, or actual discriminatory practices. Implement a transparent salary review process.
### 2.Review Performance Rating System for Bias:
The analysis of ratings by gender should prompt a review of the performance appraisal system. Training for managers on unconscious bias and standardized rating criteria can help ensure fairness at Palmoria industry.
### 3.Develop Targeted Recruitment and Promotion Strategies:
If certain departments or regions show significant gender imbalances, the management should implement strategies to attract and promote underrepresented genders in those areas. This could include setting diversity targets and reviewing promotion criteria.
### 4.Ensure Compliance with Minimum Wage Regulation:
The management should Immediately address the cases where employees are paid below the $90,000 minimum salary. Develop a clear plan for salary adjustments and communicate it transparently to affected employees.
### 5. Implement Diversity and Inclusion Training:
The mangement shud roll out comprehensive diversity and inclusion training programs for all employees, especially leadership and HR personnel, to raise awareness and promote an inclusive culture to the industry.
### 6.Regular HR Data Audits:
The management should establish a routine for auditing HR data to proactively identify and address potential issues related to gender inequality, pay disparities, and compliance.

### 5.0 Conclusion
This capstone project report has provided a data-driven analysis of the Palmoria Group's HR data, specifically focusing on gender equality and salary structure. The findings highlight areas where disparities exist, offering the management a clear picture of the challenges at hand. By implementing the proposed recommendations, the Palmoria Group industry can take significant steps towards building a more equitable, transparent, and compliant workplace, ultimately enhancing its reputation and supporting its long-term growth ambitions. The future of gender equality at Palmoria indeed lies in the proactive and informed actions taken by its leadership team.
