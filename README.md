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

---

### Project Overview
This project analyses a dataset containing HR data for LITA, including attrition, business travel, CF_age band, gender, department, employee number etc. The datasets include key information such as product types, order IDs, customer IDs, quantity of products sold, and unit prices. the primary objective of this project is to uncover insights from the sales data that can help this business brand make informed decisions to improve its product offerings, sales strategies, and customer experience.

---

### Data Sources
The primary source of data used here is Data Sale.CSV. It is open-source data that can be freely downloaded from an open source online such as Kaggle or FRED or any other data repository site. 

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
  4. Confirmed the integrity of the datasets by using column quality, column distribution, and column profile options under the view tab(screenshot of this).

---

### Exploratory Data Analysis (EDA)
EDA involves exploring the data to answer some questions about the data such as;
- What is the overall sales trend
- Which products are top sellers
- What are the products on peak sales? (pivot tables and charts for both datasets here)

  ![Alt text for image](https://github.com/Light63/LITA-HR_CLASS_DOCUMENTATION/blob/main/Excel%20HR%201.JPG?raw=true)
  Figure 1: Shows the overall trend for the HR data using pivot tables and charts


  ![Alt text for image](https://github.com/Light63/LITA-HR_CLASS_DOCUMENTATION/blob/main/Excel%20HR%202.JPG?raw=true)

  Figure 2: Shows the overall trend sales  for the customer data using pivot tables and charts




  ![Alt text for image](https://github.com/Light63/LITA-HR_CLASS_DOCUMENTATION/blob/main/HR%20BI%201.JPG?raw=true)







  Figure 3: Shows the already prepared dataset ready for visualizations. this is particularly important as it enables effective analysis of the data to make valid and informed decisions 
            that will in turn, identify patterns, and sales trends, as well as boost productivity. Hence, increasing revenue and customer satisfaction.


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
