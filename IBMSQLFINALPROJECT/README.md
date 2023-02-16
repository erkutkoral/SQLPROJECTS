<br/>
<p align="center">
  <a href="https://github.com/erkutkoral/SQLPROJECTS">
    <img src="https://www.chicago.gov/content/dam/city/about/skyline_night.jpg" alt="Logo" width="400" height="400">
  </a>

  <h3 align="center">Exploring what's going on in Chicago.</h3>

  <p align="center">
    Analyzing Chicago via SQL.
    <br/>
    <br/>
    <a href="https://github.com/erkutkoral/SQLPROJECTS"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/erkutkoral/SQLPROJECTS/issues">Report Bug</a>
    .
    <a href="https://github.com/erkutkoral/SQLPROJECTS/issues">Request Feature</a>
  </p>
</p>

![Contributors](https://img.shields.io/github/contributors/erkutkoral/SQLPROJECTS?color=dark-green) ![Issues](https://img.shields.io/github/issues/erkutkoral/SQLPROJECTS) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Used Techs, Libraries and Frameworks](#built-with)
* [Authors](#authors)

## About The Project

3 tables integrated SQL project:
* Socioeconomic indicators in Chicago
* Chicago public schools
* Chicago crime data
The following questions were answered using the techniques mentioned.
1. List the school names, community names and average attendance for communities with a hardship index of 98.
--> Used Joins

2. List all crimes that took place at a school. Include case number, crime type and community name.
--> Used Joins

3. Create a view showing the columns listed in the following table, with new column names as shown in the second column.
--> Created View

4. Returns all of the columns from the view.
--> Used View which I created.

5. Write the structure of a query to create or replace a stored procedure called UPDATE_LEADERS_SCORE that takes a in_School_ID parameter as an integer and a in_Leader_Score parameter as an integer.
--> Created a Stored Procedure

6. Inside your stored procedure, write a SQL statement to update the Leaders_Score field in the CHICAGO_PUBLIC_SCHOOLS table for the school identified by in_School_ID to the value in the in_Leader_Score parameter.
--> Used Stored Procedure

7. Inside your stored procedure, write a SQL IF statement to update the Leaders_Icon field in the CHICAGO_PUBLIC_SCHOOLS table for the school identified by in_School_ID using the following information.
--> Updated Stored Procedure

8. Call the stored procedure, passing a valid school ID and a leader score of 50, to check that the procedure works as expected.
--> Called the stored procedure

9. Update your stored procedure definition. Add a generic ELSE clause to the IF statement that rolls back the current work if the score did not fit any of the preceding categories.
--> Used Transactions

## Used Techs, Libraries and Frameworks

Used Technologies/Libraries: SQL, Python Integration for SQL
Magic SQL Commands, sqlalchemy

## Authors

* **Erkut Koral** - *Industrial Engineering Student* - [Erkut Koral](https://www.linkedin.com/in/erkutkoral/)
