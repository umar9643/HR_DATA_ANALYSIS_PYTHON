HR Data Analysis
📌 Overview

This project focuses on analyzing HR data to explore workforce demographics, salary trends, employee performance, and organizational structure. By addressing a series of well-defined HR business questions, the analysis provides actionable insights that can guide management in hiring, retention, performance evaluation, and strategic planning.

📂 Dataset

Source: HR_Data_MNC_Data Science Lovers.csv

Shape: Employee records with multiple attributes such as:

Employee Status (Active, Resigned, Retired, Terminated)

Work Mode (On-site, Remote)

Department

Job Title

Salary

Performance Rating

Experience (Years)

Country

Hire Year

✅ No missing values were found, ensuring reliable and consistent analysis.

❓ Research Questions

This analysis answers the following 15 business-critical HR questions:

What is the distribution of employee status (Active, Resigned, Retired, Terminated)?

How many employees are there in each department?

What is the average salary by department?

What is the distribution of work modes (On-site, Remote)?

Which job title has the highest average salary?

What is the average salary in different departments based on job title?

How many employees Resigned & Terminated in each department?

How does salary vary with years of experience?

What is the average performance rating by department?

Which country has the highest concentration of employees?

Is there a correlation between performance rating and salary?

How has the number of hires changed over time (per year)?

Compare salaries of Remote vs. On-site employees – is there a significant difference?

Find the top 10 employees with the highest salary in each department.

Identify departments with the highest attrition rate (Resigned %).

⚙️ Tools & Technologies

Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Jupyter Notebook for analysis & visualization

📈 Analysis & Methodology

Data Preprocessing

Imported CSV data

Checked for missing values (none found)

Performed descriptive statistics

Exploratory Data Analysis (EDA)

Count plots, bar plots, and distribution plots for categorical & numerical variables

Salary & performance trends across experience and departments

Correlation analysis between performance rating and salary

Trend analysis for yearly hires

Advanced HR Analytics

Attrition analysis (Resigned % by department)

Salary benchmarking (job title & department wise)

Remote vs On-site salary comparison

Identification of top-paid employees

🔑 Key Insights

Workforce Composition: Majority employees are active, with notable attrition in specific departments.

Salary Distribution: Certain departments and job titles command higher salaries.

Experience vs Salary: Clear positive trend—higher experience leads to higher pay.

Performance vs Salary: Moderate correlation—high performers tend to earn more.

Remote vs On-site: Remote employees showed competitive salaries, with slight differences.

Attrition: Some departments have significantly higher resignation rates, pointing to dissatisfaction or poor engagement.

Hiring Trends: Number of hires has fluctuated yearly, highlighting shifts in workforce demand.

✅ Conclusion

The HR analysis reveals:

Unbalanced department structures, requiring better workforce allocation.

Attrition hotspots in certain departments demand urgent HR intervention.

Work mode flexibility plays a role in retention and salary distribution.

Salary fairness and performance alignment is essential to improve motivation.

💡 Recommendations

Strategic Hiring: Focus on underrepresented departments to balance workload.

Attrition Management: Conduct exit interviews and improve engagement in high-attrition departments.

Performance-linked Pay: Strengthen salary-performance alignment to encourage excellence.

Flexible Work Models: Expand hybrid/remote work opportunities to enhance retention.

Talent Retention: Offer mentorship programs by senior/experienced employees.

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/hr-data-analysis.git


Navigate to the project folder:

cd hr-data-analysis


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook "HR DATA ANALYSIS.ipynb"

📊 Sample Visualizations

(Add screenshots of your plots here, e.g. employee status distribution, salary by department, attrition rates, etc.)

🙌 Acknowledgements

Dataset inspired by HR analytics case studies and shared by Data Science Lovers community.
