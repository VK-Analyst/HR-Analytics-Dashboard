# HR-Analytics-Dashboard
# Question
"Given the raw data we have on employee records, including information such as hire dates, resignation dates, departments, job titles, education fields, and performance reviews, please analyze the data to determine the company's employee attrition rate over the past years.

# Your Analysis should include:

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

# vis

**1. Create Text Box**

Add a text box to the dashboard and label it "HR Analytics Dashboard" to serve as the title of the report.

**2. Create Cards**

Total Employees: Create a card to display the total number of employees.

Attrition Count: Use an IF function to count attrition (e.g., IF(Attrition = "yes", 1, 0)).

Attrition Rate: Develop new measures to calculate the attrition rate.

Average Age: Create a card to show the average age of employees.

Average Salary: Add a card for the average salary.

Average Years in Company: Display the average number of years employees have been with the company.

**3. Create Visualizations**

Donut Chart: Add a donut chart titled "Attrition by EducationField" to visualize attrition rates across different education fields.

Stacked Column Chart: Create a stacked column chart titled "Attrition by Age" to illustrate attrition rates by age groups.

Clustered Bar Chart: Add a clustered bar chart titled "Attrition by SalarySlab" to show attrition rates across different salary slabs.

Clustered Bar Chart: Create another clustered bar chart titled "Attrition by JobRole" to display attrition rates by job roles.

Area Chart: Include an area chart titled "Attrition by Year at Company" to show trends in attrition over the years.

Matrix Table: Add a matrix table titled "Job Role" to provide detailed information on attrition rates by job role.

Stacked Column Chart: Create a stacked column chart titled "Attrition by Gender" to visualize attrition rates by gender.

**4. Add Slicer**

Include a slicer for "Department" to allow users to filter the data by department.

**5. Format Visuals**

Adjust color schemes and formatting for all visuals to ensure consistency and clarity in the dashboard.
