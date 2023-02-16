<br/>
<p align="center">
  <a href="https://github.com/erkutkoral/SQLPROJECTS">
    <img src="https://media.wired.com/photos/62feb60bcea7c0581e825cb0/master/pass/Fate-of-Game-Preservation-Games-GettyImages-1170073827.jpg" alt="Logo" width="300" height="300">
  </a>

  <h3 align="center">Has the golden age of video games already passed?</h3>

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

Video games are big business: the global gaming market is projected to be worth more than $300 billion by 2027 according to Mordor Intelligence. With so much money at stake, the major game publishers are hugely incentivized to create the next big hit. But are games getting better, or has the golden age of video games already passed?

In this project, we'll explore the top 400 best-selling video games created between 1977 and 2020. We'll compare a dataset on game sales with critic and user reviews to determine whether or not video games have improved as the gaming market has grown.

Our database contains two tables. We've limited each table to 400 rows for this project, but you can find the complete dataset with over 13,000 games on Kaggle.
 * game_sales

|column	   |type   |	meaning                              |
|------------|-------|-------------------------------|
|game|	varchar	|Name of the video game|
|platform|	varchar	|Gaming platform|
|publisher|	varchar	|Game publisher|
|developer|	varchar	|Game developer|
|games_sold|	float	|Number of copies sold (millions)|
|year	|int|	Release year|

* reviews

|column	|type	|meaning|
|----------|----------|---------------------------------------|
|game	|varchar	|Name of the video game|
|critic_score|	float	|Critic score according to Metacritic|
|user_score|	float	|User score according to Metacritic|

Task will be to do the following exploratory analysis:
* The top selling video games of all time!
* Missing review scores
* Years that video game critics loved
* Was 1982 really that great?
* Years that dropped off the critics' favorites list
* Years video game players loved
* Years that both players and critics loved
* Sales in the best video game years

## Used Techs/Libraries/Frameworks

SQL, Python Integration for SQL, Magic SQL Commands, sqlalchemy

## Authors

* **Erkut Koral** - *Industrial Engineering Student* - [Erkut Koral](https://www.linkedin.com/in/erkutkoral/)

