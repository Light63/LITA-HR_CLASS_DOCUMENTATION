# LITA-HR CLASS DOCUMENTATION
DATA ANALYSIS FOR THE HR DEPARTMENT IN LITA

---

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Key Features](#key-features)

[Technologies Used](#technologies-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis_EDA](#exploratory-data-analysis-eda)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Results](#results)

[Recommendations](#recommendations)



---

### Project Overview
This project analyses a dataset containing HR data for LITA, including attrition, business travel, CF_age band, gender, department, employee number etc. The aim of this project is to analyze HR data to gain insights into employee demographics, job satisfaction, attrition rates, and educational backgrounds. The findings will inform strategies for improving employee retention, enhancing job satisfaction, and optimizing recruitment processes.

---

### Data Sources
The primary source of data used here is Data Sale.CSV. It is open-source data that can be freely downloaded from an open source online such as Kaggle, FRED or any other data repository site. 

---

### Key Features

I. Attrition: Indicates whether an employee has left the organization or not. This is essential for analyzing turnover rates and employee retention strategies.

ii. Educational Field: The area of study in which the employee has a degree, useful for assessing the educational background relative to job roles.

iii. Education: Level of education attained (e.g., high school, bachelor's, master's), this provides insights into the qualifications of the workforce.

iv. Daily Rate: Employee's daily compensation, particularly useful for payroll analysis and benchmarking salary structures.

v. Job Role: Title or position held by the employee, allowing for analysis of job-specific trends, performance, and attrition rates.

vi. Job Satisfaction: Measures employee contentment with their role, often rated on a scale, crucial for understanding morale and retention.

vii. Department: This is the Specific area within the organization (e.g., HR, IT, Sales), enabling departmental analysis of performance and employee engagement.

viii. Age Band: Employees are categorized into age ranges (e.g., 18-25, 26-35), which facilitates demographic analysis and workforce planning.

---

### Technologies Used
- Microsoft Excel [Download here](https://www.microsoft.com)
  1. For Data Cleaning
  2. For Analysis
  3. For Data  Visualization
- SQL-  Structured Query Language
  1. For querying of data.
  2. For storing data.
  3. For managing data and,
  4. For manipulating data.
- POWER BI
  1.  For beautiful and interactive data visualizations.
  2.  For insightful data reports.
  3.  For retrieving data from different sources.
- Github
  1. For Portfolio Building.
  2. For collaboration and teamwork

  Therefore, this project aims to equip stakeholders of the brand with actionable insights to enhance sales strategies, boost customer retention, and streamline inventory management.
  
---

### Data Cleaning and Preparations

In the initial phase of the data cleaning and preparations, the following actions were performed on the different technologies used;

#### Excel
  1. Data loading and inspection
  2. Handling missing and null variables using ISBLANK function in Excel
  3. Eliminating duplicates.
  4. Data cleaning and formatting.

#### SQL
  1. Conversion of the already cleaned data from Excel to a CSV file format, this was to enable importation of the data into SQL quickly and efficiently as opposed to importing an Excel       file format directly.
  2. Creation of a database.

      ```SQL
          CREATE DATABASE LITA_PROJECT
      ```

     The above code creates a database that houses all tables ready for querying.
     
  4. Import the SalesData and CustomerData data into the already created database.
  5. Writing amazing codes to show the different trends and patterns in the dataset for making sound decisions (screenshot of the codes).

#### POWER BI
  1. launched the power bi environment.
  2. Importation of both datasets using the TEXT/CSV file extension.
  3. Explored and cleaned the dataset.
  4. Confirmed the integrity of the datasets by using column quality, column distribution, and column profile options under the view tab.

---

### Exploratory Data Analysis (EDA)
EDA involves exploring the data to answer some questions about the data such as;
- What is the overall sales trend
- Which products are top sellers
- What are the products on peak sales? 

  ![Alt text for image](https://github.com/Light63/LITA-HR_CLASS_DOCUMENTATION/blob/main/Excel%20HR%201.JPG?raw=true)
  Figure 1: Shows the overall trend for the HR data using pivot tables and charts


  ![Alt text for image](https://github.com/Light63/LITA-HR_CLASS_DOCUMENTATION/blob/main/Excel%20HR%202.JPG?raw=true)

  Figure 2: Shows the overall trend sales for the HR data using pivot tables and charts



  ![Alt text for image](https://github.com/Light63/LITA-HR_CLASS_DOCUMENTATION/blob/main/HR%20BI%201.JPG?raw=true)



  Figure 3: Shows the cleaned dataset ready for visualization. This is particularly important as it enables effective analysis of the data to make valid and informed decisions 
            that will, in turn, identify patterns, improve employee retention, enhance job satisfaction, and optimise recruitment processes.

---

  ### Data Analysis
  the images  and codes below show how data analysis was performed on the datasets using the above-mentioned tools.

  ```SQL
  SELECT * FROM TABLE 1
  WHERE CONDITION = TRUE
  ```

---

### Data Visualization


![alt text for image](https://github.com/Light63/LITA-CLASS-PROJECT/blob/main/CLASS%201.JPG?raw=true)




![alt text for image](https://github.com/Light63/LITA-CLASS-PROJECT/blob/main/class%202.JPG?raw=true)






![alt text for image](https://github.com/Light63/LITA-CLASS-PROJECT/blob/main/Class%203.JPG?raw=true)


### Results

from the above analysis, The total number of attrition reflects 237 employees, the total number of employees is 1,470 and the current employee is 1,233. This indicates that more employees are leaving the organization quickly, especially from the life sciences educational field. 20 employees from the laboratory technicians roles are very dissatisfied as against the 13 very satisfied employees. 16 sales executives are very dissatisfied as against the 14 very satisfied sales executives. Also, 13 research scientists are very dissatisfied as against the 9 very satisfied research scientists.

This reflects poor employee treatment by the organization. Again, it was observed that 112 of the employees who left were within the age bracket of 25-34. this is particularly risky as the organisation is fast losing her young minds that have the potential of bringing in digital innovations that could make the organization a global empire.


### Recommendations

Targeted Retention Strategies: Develop tailored retention programs for departments with high attrition like laboratory technicians, sales executives, and  research scientists, focusing on improving job satisfaction and career growth opportunities.

Compensation Review: Conduct a compensation audit to ensure competitive pay across similar roles, addressing any disparities linked to education. this will encourage employees to remain in the company and give their best, especially for married men who from our analysis have a higher attrition rate.


Education and Development Programs: Implement training and development initiatives that align with the educational backgrounds of employees to enhance job satisfaction and performance. This initiative will help keep the age bracket of 25-34 in the organization as they tend to want to learn new things and grow. knowing that they have the company's support for their growth and development will help them explore strategic innovations in the organisation thereby helping the organisation grow in the process.

Exit Interviews: Regularly conduct exit interviews to gather insights on why employees leave, particularly focusing on departments with high turnover rates.

Mentorship Programs: Establish mentorship opportunities for new hires, particularly in high turnover departments, to improve integration and retention.

By focusing on these areas, the organization can better understand its workforce dynamics and take proactive steps to enhance employee satisfaction and retention.





