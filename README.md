# Counting-Cars
## Feven Ferede, Kobe Magee, Grisma Niruala

---
## Introduction
This project encompassed gathering data on vehicle speeds using a radar speed detector positioned along 24th Ave with a speed limit of 30mph. The data gathered is from the whole class.
<div align = "center">
<img src = "images/30 mph.jpg" width = "450")>
</div>

---
## Data Dictionary 
Columns that we used to analyze the data:
1. Date: the different dates when the speed of vehicles were recorded
2. Day: the day when the data was recorded (a group did day like saturday, sunday, etc not date in mm-dd format)
3. Speed: Speed of the vehicle
4. Vehicle Type: Types of vehicle
5. Time: Time when the speed of vehicles was recorded
6. Temperature: Temperature throughout the time when the speed of vehicles was recorded
7. Weather: The weather, if it was sunny, partly cloudy, raining, etc during the time the data was recorded
8. Name: The names of student's who collected the data

---
## Data Cleaning 
1. Assigned names as "group 1", "group 2", etc to the excel and csv files loaded. Below is what it looks like:
<img src = "images/data to group naming and numbering.png" width = "450")>

2. We renamed columns so all the columns from the different data are similar. We also removed columns that     are unnecessary to the data analysis. Below is a snippet of the code we wrote as an example to show how we renamed and removed the columns:
<img src = "images/data analysis part 1 example.png" width = "450")>

3. We want all the tables with the same type of columns: Time of Day, Temperature, Type of Vehicle, MPH, Student, Group Number, and Weather. So we decided to add into the tables and for the ones without data for a column other than group number. the data under that column is assigned N/A. Below is an example of the code:
<img src = "images/adding missing columns.png" width = "450")>

4. We removed the Time of Day column:
<img src = "images/removal of time of day column.png" width = "450")>

5. We converted the "Date" column to character type for each group:
<img src = "images/convert date column to character type.png" width = "450")>

6. We removed the "Time of Day" column and convert the "Date" column for each group:
<img src = "images/remove of time of day column and conversion of date column.png" width = "450")>

7. We combined all 8 groups and rearranged the table to look like this:

8. We converted the column "Type of Vehicle" column to lowercase














   
