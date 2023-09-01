# SQL-AND-PBI-RELATIONSHIP

# **Introduction**
In this analysis Microsoft PowerBI tool will be used in conjunction with SQL server to clean datasets, transform them into a desired format. Comma separated values (CSV) files will be imported into SQL server and also transfered from the SQL server into PBI. 

# **Activity**
1. Importing the ‘Bank Term Deposit Subscription’ dataset into your Power BI Desktop using the csv file option
2. Load the dataset into a database in SQL Server, connect your Power BI desktop to this database and import only the first 25 rows into your desktop for analysis
3. Extensively clean the ‘Employee.csv’, ‘Department.csv’ and ‘Salary.csv’ datasets provided under the Dirty Datasets folder in the drive.
4.  Merge all three datasets together.

# **Skills Demonstrated**
1. Database Importation
2. Data Cleaning
3. Data Transformation using PowerBI

# **Data Importation**
To carry out the first activity successfully a database was created named 'Bank_full', in the the newly created database the 'bank_full' csv file will be imported into the SQL Database table. to import the csv file I right-clicked on the bank_full database and selected 'import data', this gave a prompt box 'Welcome to SQL Server import and export wizard' then I clicked next to select my 'data source' as flat file source then I browsed the file name 'bank full' from my desktop, then I edited the 'text qualifier' from 'none' to double quotation mark (") then I viewed the table by clicking on 'columns', followed by next then I selected my destination source as 'Microsoft OLE DB Provider for SQL Server' this provided a prompt box where I clicked next until my files all successfully uploaded. The wizerd automatically created the table in the 'table' section of the bank_full database in SQL Server. Please view the steps I followed from the screenshots below.

![SQL WIZARD](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/789c6bdc-038e-4571-b287-7bb2f4b2242a)

![step 2](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/74395479-3d55-4467-8ed5-57611361aa89)

![step 3](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/1a7c744e-2190-4a8f-8509-9b535db2010d)

![Step 4](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/3f1afeff-dd47-4d94-b3c9-f4fb68bf67ac)

![Step 5](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/74dae271-64b9-46be-b1b0-3a18db5e2444)


# **Transfering data from SQL to PBI **

The uploaded 'bank_full csv table in the SQL server was transfered to the PBI by clicking on 'import data from the SQL Server database' option on the home ribbon of the Power bi query, then an interface popped-up that showed up, where I clicked on the advanced options then filled in the SQL statment, this loaded the table to the Power BI query. please see the screenshot below.

![SQL TO PBI](https://github.com/Jessie-Watt/SQL-AND-PBI-RELATIONSHIP/assets/140435577/bd07531e-bbf8-4403-9ffc-88c9f8442ad0)

