<br/>
<p align="center">
  <a href="https://github.com/erkutkoral/SQLPROJECTS">
    <img src="https://www.ucheck.co.uk/wp-content/uploads/mental-health-2313426_1280.png" alt="Logo" width="400" height="400">
  </a>

  <h3 align="center">Does going to university in a different country affect your mental health? </h3>

  <p align="center">
    Analyzing Students via SQL.
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
* [Used Techs/Libraries/Frameworks](#built-with)
* [Authors](#authors)


## About The Project

Does going to university in a different country affect your mental health? A Japanese international university surveyed its students in 2018 and published a study the following year that was approved by several ethical and regulatory boards.

The study found that international students have a higher risk of mental health difficulties than the general population. Explore the students data using PostgreSQL to find out if this is true and see if the length of stay is a contributing factor.

Here is a data description of the fields you may find helpful. The full dataset is in one table with 50 fields and, according to the survey, 268 records. Each row is a student.

| Field Name    | Description                                      | 
| ------------- | ------------------------------------------------ |
| inter_dom     | Types of students                                |
| japanese_cate | Japanese language proficiency                    | 
| english_cate  | English language proficiency                     |
| academic      | Current academic level                           | 
| age           | Current age of student                           |
| stay          | Current length of stay in years                  |
| todep         | Total score of depression (PHQ-9 test)           |
| tosc          | Total score of social connectedness (SCS test)   |
| toas          | Total score of Acculturative Stress (ASISS test) |

Task will be to do the following exploratory analysis:
* Count the number of all records, and all records per student type
* Filter the data to see how it differs between the student types
* Find the summary statistics of the diagnostic tests for all students
* Summarize the data for international students
* See if length of stay impacts the test scores

## Used Techs/Libraries/Frameworks

Used Technologies/Libraries: SQL, Python Integration for SQL
Magic SQL Commands, sqlalchemy

## Authors

* **Erkut Koral** - *Industrial Engineering Student* - [Erkut Koral](https://www.linkedin.com/in/erkutkoral/)

