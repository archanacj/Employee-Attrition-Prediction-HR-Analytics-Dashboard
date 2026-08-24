# Employee-Attrition-Prediction-HR-Analytics-Dashboard
Employee Attrition Prediction & HR Analytics Dashboard

📌 Project Overview

Employee attrition is an important challenge for organizations because frequent employee turnover can increase recruitment and training costs, affect productivity, and create workforce management difficulties.

This project analyzes an IBM HR Employee Attrition dataset using Python and Power BI to understand employee attrition patterns and identify factors associated with employee turnover.

The project follows an end-to-end data analytics workflow, including data cleaning, exploratory data analysis (EDA), data visualization, feature engineering, attrition analysis, and HR dashboard development.

⸻

🎯 Project Objectives

The main objectives of this project are:

* Understand the structure and quality of the HR dataset.
* Clean and preprocess employee data.
* Analyze the overall employee attrition pattern.
* Identify important factors associated with employee attrition.
* Compare employee attrition across departments and job levels.
* Analyze the relationship between attrition and:
    * Overtime
    * Monthly income
    * Job level
    * Job satisfaction
    * Age
    * Experience
    * Department
    * Work-related factors
* Perform univariate, bivariate, and multivariate EDA.
* Create meaningful data visualizations.
* Develop an HR Analytics Dashboard using Power BI.
* Provide data-driven recommendations to support employee retention.

⸻

📊 Dataset

The project uses an IBM HR Employee Attrition dataset containing employee-level HR information.

Dataset Details

* Initial records: 601
* Columns: 29
* Duplicate records identified: 7
* Records after duplicate removal: 594

The dataset contains information related to employee demographics, job characteristics, compensation, satisfaction, overtime, experience, and employment details.

Major Variables

* EmployeeID
* Age
* Attrition
* Department
* DistanceFromHome
* Education
* EducationField
* EnvironmentSatisfaction
* Gender
* JobInvolvement
* JobLevel
* JobRole
* JobSatisfaction
* MaritalStatus
* MonthlyIncome
* NumCompaniesWorked
* Overtime
* PercentSalaryHike
* PerformanceRating
* RelationshipSatisfaction
* StockOptionLevel
* TotalWorkingYears
* TrainingTimesLastYear
* WorkLifeBalance
* YearsAtCompany
* YearsInCurrentRole
* YearsSinceLastPromotion
* YearsWithCurrManage
* EmploymentType

⸻

🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

Missing Value Treatment

The dataset initially contained:

* 8 missing values in Age
* 7 missing values in EmploymentType

Missing Age values were replaced using the mean, while missing EmploymentType values were replaced using the mode.

Duplicate Removal

7 duplicate records were identified and removed to avoid repeated employee records affecting the analysis.

Column Standardization

The following columns were renamed for consistency:

* gender → Gender
* JOBROLE → JobRole
* overtime → Overtime

Data Type Verification

The data types of all columns were checked. No additional data type conversion was required.

Feature Engineering

A new feature called IncomeCategory was created using MonthlyIncome:

* Low: MonthlyIncome < 5,000
* Medium: MonthlyIncome ≥ 5,000
* High: MonthlyIncome ≥ 10,000

⸻

🔍 Exploratory Data Analysis

The project includes:

Univariate Analysis

* Employee Attrition Distribution
* Employee Age Distribution
* Employee Distribution by Department

Bivariate Analysis

* Attrition by Overtime
* Monthly Income vs Attrition
* Age vs Monthly Income
* Department-level analysis
* Other employee and job-related comparisons

Multivariate Analysis

* Overtime, Job Satisfaction and Attrition
* Correlation analysis of numerical variables
* Department and attrition comparisons

⸻

📈 Visualizations

The project uses Matplotlib, Seaborn, and Plotly for data visualization.

The analysis includes different visualization techniques such as:

* Count Plot
* Histogram
* Pie Chart
* Line Chart
* Box Plot
* Violin Plot
* Scatter Plot
* Grouped Bar Chart
* Correlation Heatmap

These visualizations are used to identify patterns and relationships between employee characteristics and attrition.

⸻

💡 Key Insights

The EDA identified several important patterns associated with employee attrition.

1. Attrition Distribution

Most employees in the dataset remained with the organization, while a smaller proportion experienced attrition.

2. Overtime and Attrition

Employees working overtime showed a comparatively higher representation of attrition.

This indicates that workload and overtime may be associated with employee turnover.

3. Job Level and Attrition

Attrition was more noticeable among employees at lower job levels compared with higher job levels.

This suggests that career development and job seniority may be relevant factors in employee retention.

4. Monthly Income and Attrition

Employees who left generally showed lower monthly income compared with employees who stayed.

This suggests that compensation may be associated with employee attrition.

5. Department-Level Differences

Attrition is not equally distributed across departments. Different departments show different patterns of employee turnover.

6. Job Satisfaction and Overtime

The analysis of overtime, job satisfaction, and attrition together provides additional insight into the relationship between workload, satisfaction, and employee turnover.

These findings represent associations observed in the dataset and should not be interpreted as proof of causation.

⸻

📌 Recommendations

Based on the EDA findings, the following strategies can support employee retention:

1. Monitor Overtime and Workload

Organizations can monitor employees with consistently high overtime and evaluate workload distribution.

2. Strengthen Career Development

Provide mentoring, training, career-development programs, and clear promotion opportunities, particularly for employees at lower job levels.

3. Review Compensation

Regularly review compensation structures and salary progression, especially for employee groups showing relatively higher attrition.

4. Develop Department-Specific Retention Strategies

Departments with relatively higher attrition can be analyzed separately to identify their specific workforce and job-related challenges.

5. Improve Employee Satisfaction

Regular employee feedback and satisfaction surveys can help identify dissatisfaction early and support timely HR intervention.

6. Implement Data-Driven Retention Strategies

Attrition-related factors can be combined to develop a retention-risk framework that helps HR teams identify employee groups requiring additional support.

⸻

🛠️ Tools & Technologies

Programming & Analysis

* Python
* Pandas
* NumPy
* Jupyter Notebook / Google Colab

Data Visualization

* Matplotlib
* Seaborn
* Plotly

⚠️ Project Limitations

* The analysis is based on the variables available in the dataset.
* The dataset represents a specific employee population and may not represent every organization.
* The analysis identifies associations rather than causal relationships.
* Department-level employee counts can be influenced by differences in department size.
* Additional factors such as organizational culture, management quality, and detailed employee feedback are not included.

⸻

🔮 Future Enhancements

Machine Learning Prediction

A machine learning model can be developed to predict whether an employee is likely to leave the organization.

Retention Risk Score

A retention risk score can be developed to categorize employees into different levels of attrition risk.

Interactive HR Dashboard

The analysis can be extended into a complete interactive Power BI dashboard containing:

* Total Employees
* Attrition Count
* Attrition Rate
* Department-wise Attrition
* Job Role Analysis
* Income Analysis
* Overtime Analysis
* Employee Risk Categories

Advanced Analytics

Future work can include:

* Feature importance analysis
* Statistical hypothesis testing
* Machine learning model comparison
* Model evaluation
* Employee retention prediction

⸻

📌 Conclusion

This project demonstrates how Python-based data analytics and Power BI can be used to analyze employee attrition and generate meaningful HR insights.

The EDA identified several factors associated with employee turnover, including overtime, job level, monthly income, department, and job satisfaction.

The analysis provides a foundation for developing predictive models and retention-risk strategies that can help organizations make more data-driven employee retention decisions.

⸻

👩‍💻 Author

Archana Jayaprakash

Project: Employee Attrition Prediction & HR Analytics Dashboard

Skills Demonstrated: Python | SQL | Excel | Power BI | Data Cleaning | EDA | Data Visualization | HR Analytics
