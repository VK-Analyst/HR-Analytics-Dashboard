# HR-Analytics-Dashboard
# Question
"Given the raw data we have on employee records, including information such as hire dates, resignation dates, departments, job titles, education fields, and performance reviews, please analyze the data to determine the company's employee attrition rate over the past years.

# Analysis should include:

1) Overall Attrition Rate: Calculate the total attrition rate for the company.

2) Attrition by Education Field: Identify which education fields are associated with higher and lower attrition rates.

3) Attrition by Job Title and Role: Determine if certain job titles and roles are associated with higher attrition rates.

4) Trends Over Time: Analyze if there are any noticeable trends or patterns in attrition rates over the three-year period.

5) Key Insights: Provide any key insights or recommendations that might help HR address high attrition areas.

Please present your findings in a detailed report, including any visualizations that can help illustrate the data and your conclusions."

# Raw Data

![Raw data](https://github.com/user-attachments/assets/475970cb-4684-49d3-a6c9-8484e0ea948c)

# Data Cleaning

To ensure accurate analysis and reporting, follow these steps to clean and prepare the raw employee attrition data:

**1.) Convert CSV to Excel**

Open the CSV file in Excel.

Save the file as an Excel Workbook format for enhanced functionality and compatibility.

**2.) Check for Null Values**

Inspect each column in the dataset to identify and document any null or missing values.

Address missing data as needed, either by imputing values or excluding incomplete rows.


**3.) Remove Duplicate Records**

Select all columns in the dataset.

Utilize Excel’s “Remove Duplicates” feature to eliminate redundant rows and ensure a unique dataset.

**4.) Clean Business Travel Categories**

Locate the column for Business Travel.

Standardize category formatting to ensure consistency:

Ensure uniformity by standardizing values like "TravelRarely" by addressing discrepancies such as missing or extra underscores.

**5.) Transfer Data to Power BI**

Import the cleaned Excel file into Power BI.

# Visualization Steps

**1. Create Text Box**

Add a text box to the dashboard and label it "HR Analytics Dashboard" to serve as the title of the report.

![1](https://github.com/user-attachments/assets/52b60f18-482b-4d45-9d72-d1b34084cca9)


**2. Create Cards**

Total Employees: Create a card to display the total number of employees.

Attrition Count: Use an IF function to count attrition (e.g., IF(Attrition = "yes", 1, 0)).

Attrition Rate: Develop new measures to calculate the attrition rate.

Average Age: Create a card to show the average age of employees.

Average Salary: Add a card for the average salary.

Average Years in Company: Display the average number of years employees have been with the company.

![2](https://github.com/user-attachments/assets/ab4d7df7-1117-4097-b6e5-38ab8625f1f5)

**3. Create Visuals**

Donut Chart: Add a donut chart titled "Attrition by EducationField" to visualize attrition rates across different education fields.

![3](https://github.com/user-attachments/assets/be256497-c2b5-4902-ab6c-688486252372)

Stacked Column Chart: Create a stacked column chart titled "Attrition by Age" to illustrate attrition rates by age groups.

![4](https://github.com/user-attachments/assets/36a8ad35-602d-433e-b782-7a2c52f7f746)

Clustered Bar Chart: Add a clustered bar chart titled "Attrition by SalarySlab" to show attrition rates across different salary slabs.

![5](https://github.com/user-attachments/assets/e2bf146e-bb98-47ba-af9c-b76cfe0d7744)


Clustered Bar Chart: Create another clustered bar chart titled "Attrition by JobRole" to display attrition rates by job roles.

![8](https://github.com/user-attachments/assets/a2e9ad01-9824-4bd5-9124-e1cdbf2eff38)

Area Chart: Include an area chart titled "Attrition by Year at Company" to show trends in attrition over the years.

![6](https://github.com/user-attachments/assets/3842d4c5-418f-4b5a-aa1d-9969b23275c7)

Matrix Table: Add a matrix table titled "Job Role" to provide detailed information on attrition rates by job role.

![7](https://github.com/user-attachments/assets/eec7fbed-9509-4aee-bed5-8e7793c7e604)

Stacked Column Chart: Create a stacked column chart titled "Attrition by Gender" to visualize attrition rates by gender.

![9](https://github.com/user-attachments/assets/dc8a5feb-157c-41ca-80d1-f9ce85c54425)

**4. Add Slicer**

Include a slicer for "Department" to allow users to filter the data by department.

![10](https://github.com/user-attachments/assets/acf63f59-bf87-4acd-b2b5-a5a0ec10403d)

**5. Format Visuals**

Adjust color schemes and formatting for all visuals to ensure consistency and clarity in the dashboard.

# FINAL OUTCOME OF DASHBOARD 

![11](https://github.com/user-attachments/assets/566ea471-92e7-47aa-8b8d-e07526bfa7ce)
