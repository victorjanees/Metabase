# Metabase

## Introduction
Metabase is an open source business intelligence tool. It lets Users to ask questions about userdata, and displays answers in formats that make sense, whether that’s a bar chart or a detailed table.

User's questions can be saved for later, making it easy to come back to them, or They can group questions into great looking dashboards. Metabase also makes it easy to share questions and dashboards with the rest of your team.

## Setup
1. Install JRE(Java Runtime Environment)
2. Download Metabase 
3. Create a new directory and move the Metabase JAR into it.
4. Change into your new Metabase directory and run the JAR.

The process of setting up the Metabase requires least minimum time. The details and codes for setup and run the Metabase JAR is given in the Reference section under setup link.

## Language
Metabase uses SQL(Structured Query Language), Which is a commonly used languages in other Databases like MySql, Sqlite3, etc.

## Features
* Allows anyone in the team to ask questions without knowing sql.
* Uses the SQL editor for more complex queries.
* Allows to build interactive dashboards with filters and custom click behaviour.
* Set up alerts to have Metabase, Which notifies the user when the user data changes.

## Custom Expressions in query builder
Custom Expressions are like formulas used in spreadsheet software like Excel, Google Sheets and LibreOffice Calc.
The following types are the most used expressions in Metabase.

###Basic mathematical operators
Addition(+), Subtraction(-), Multiplication(*), Division(/)
These are the basic mathematical operators. The user can also use paranthesis() for grouping these operators together.

### Conditional operators
AND, OR, NOT, greater than (>), greater than or equal to(>=), lesser than(<), lesser than or equal to(<=), not equal to(!=)

### Refering other columns
The user can refer to the columns in the current table and also refer to the table colums in other table via foreign key concept.

### Refering to segments or metrics
In Metabase, The user can also refer to the segments or metrics which are present in the current working table.

### Filter expressions and conditions
This concept is not like other ways where they returns a value. Here the return type should be a boolean either true or false.

### Filter expressions using dates
If the user wants to work with the date in the table, The format should be YYYY-MM-DD. Where Y(Year), M(Month), D(Date) should be seperated by dashes(-).

## Visualizing results
In Metabase, an answer to a question can be visualized in a number of ways:
* Numbers
* Trend
* Progress bar
* Gauge
* Table
* Pivot table
* Line chart
* Bar chart
* Combo chart
* Waterfall chart
* Row chart
* Area chart
* Scatterplot or bubble chart
* Pie chart
* Funnel
* Map

## Companies using Metabase
261 companies reportedly use Metabase in their tech stacks, where few popular compamies are:
* CRED
* Bitpanda.
* CircleCI.
* N26.
* Ruangguru.
* Yousign.
* Groww.
* kevin.


## Reference
* [Overview](https://www.metabase.com/docs/latest/users-guide/01-what-is-metabase.html)
* [Setup](https://www.metabase.com/docs/latest/operations-guide/running-the-metabase-jar-file.html)
* [Youtube](https://youtu.be/4bNp906oOhs)
