# SQL-AND-PBI-RELATIONSHIP

# **Introduction**
In this analysis Microsoft Power BI tool will be used in conjunction with SQL server to clean datasets, transform them into a desired format. Comma separated values (CSV) files will be imported into SQL server and also transfered from the SQL server into PBI. 

# **Activity**
1. Importing the ‘Bank Term Deposit Subscription’ dataset into your Power BI Desktop using the csv file option
2. Load the dataset into a database in SQL Server, connect your Power BI desktop to this database and import only the first 25 rows into your desktop for     analysis
3. Extensively clean the ‘Employee.csv’, ‘Department.csv’ and ‘Salary.csv’ datasets.
4. Merge all three datasets together.

# **Skills Demonstrated**
1. Database Importation
2. Data Cleaning
3. Data Transformation using PowerBI

# **Data Importation**
To carry out the first activity successfully, a database was created named 'Bank_full', in the newly created database the 'bank_full' csv file will be imported into the SQL Database table. To import the csv file I right-clicked on the bank_full database and selected 'import data', this gave a prompt box 'Welcome to SQL Server import and export wizard' then I clicked on next to select my data source as 'flat file source' then I browsed the file name 'bank full' from my desktop into the wizard, then I edited the 'text qualifier' from 'none' to double quotation mark (") then I viewed the table by clicking on 'columns', followed by next then I selected my destination source as 'Microsoft OLE DB Provider for SQL Server' this provided a prompt box where I clicked next until all my files were successfully uploaded. The wizard automatically developed the 'bank_full' table in the 'table' section of the bank_full database in SQL Server. Please view the steps I followed from the screenshots below.

![SQL WIZARD](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/789c6bdc-038e-4571-b287-7bb2f4b2242a)

![step 2](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/74395479-3d55-4467-8ed5-57611361aa89)

![step 3](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/1a7c744e-2190-4a8f-8509-9b535db2010d)

![Step 4](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/3f1afeff-dd47-4d94-b3c9-f4fb68bf67ac)

![Step 5](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/74dae271-64b9-46be-b1b0-3a18db5e2444)


# **Transfering Data from SQL to PBI **

The uploaded 'bank_full' csv table in the SQL server was transfered to the PBI by clicking on 'import data from the SQL Server database' option on the home ribbon of the Power bi query, then an interface popped-up that showed , where I filled my SQL server name, the database name then I clicked on the advanced options then filled in the SQL statement, this loaded only twenty-five rows of the Bank_full table to the Power BI query. please see the screenshot below.

![SQL TO PBI](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/bd07531e-bbf8-4403-9ffc-88c9f8442ad0)

![25 rows](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/fb61d044-e1cc-4212-b360-828e54306a28)

The third activity was carried out by clicking on 'get data' icon on the PBI home ribbon, to import the three datasets ‘Employee.csv’, ‘Department.csv’ and ‘Salary.csv’. The csv files where first changed to excel workbook format before importing the data into PBI. The 'transform data' icon was clicked on the home ribbon, where I cleaned the data, by captalizing the first letter of all title headers and choosing suitable 'data type' for each column title, the 'date of birth' column was cleaned by first separating each column by a delimeter then later merged the columns back together, highlighting the year column first followed by the month, then the day, this arranged the date of birth column properly then the entire date format was changed form text to 'date format'. The first 100 rows were kept to remove null values from the 'employee' and 'salary' data while the first 11 rows were kept in the department data to remove the null values too. The changes made were all applied then the Power Query Editor was then closed. 


![Employee (cleaned)](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/b1c08a64-c9e8-4a25-96d5-25eb094a356b)
![Salary (Cleaned)](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/67e99f0e-6f25-4137-b55e-aff007ef1f71)
![Dept (Cleaned)](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/0f98e7ce-0b50-49c5-9f4f-9af4782f1a19)

The cleaned three data sets were merged together as a new table using the 'Merge queries as new' on the home ribbon of the power query editor. The employee data was first merged to the salary data on matching 'ID' columns, then the newly created table was then merged to the dept table, and renamed as 'Full Table'. 

![Full Table](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/7277f79f-b188-4f13-a74f-4d81b7eb1861)


# **Conclusion**
This task has given me the insight to the importance of linking SQL Server and Power BI. SQL Server is a powerful database engine that provides robust data storage and management capabilities while Power BI Desktop is a powerful reporting and visualization tool that allows you to create compelling reports on your data. By linking these two tools together, you can create a powerful end-to-end solution for managing and analyzing your data.

