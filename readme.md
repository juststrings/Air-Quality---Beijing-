# Introduction
A quick back story Mr Olanrewanju Oyinbooke posted this chanllege on his twitter handle which I bookmarked and decided to get back to. Here is the analysis I carried out after I cleared the tasks on my table.
<br>[Link to challenge](https://twitter.com/TheOyinbooke/status/1617455232954269698?t=nl3yVqO240BD464oWji5dg&s=19)
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Challenge 1: Consider the use case described below and the accompanied data, and carry out a detailed analysis using Microsoft Power BI. This is the only way to convince me how good you are at answering business questions.<a href="https://t.co/FK3SMtDXE7">https://t.co/FK3SMtDXE7</a> <a href="https://twitter.com/hashtag/GitHub4Me?src=hash&amp;ref_src=twsrc%5Etfw">#GitHub4Me</a></p>&mdash; TheOyinbooke (@TheOyinbooke) <a href="https://twitter.com/TheOyinbooke/status/1617455232954269698?ref_src=twsrc%5Etfw">January 23, 2023</a></blockquote>

---

# Project Name: Impact of Weather Conditions on Air Quality (How does weather affects Air Quality?)
---

# Problem Objective <br>

Analyzing dataset provided, seek insights and make recommendations to achieve the set objectives of a company in the environmental consulting industry is seeking to analyze the air quality in a specific city during hot and cold weather, during high-wind conditions and during precipitation. 
<br>
They are majorly interested in making recommendations to the government and businesses in the region on how to mitigate the impact of weather conditions on air quality.  

---

# Tools used in actualizing the project

Power Bi<br>
Excel<br>
Notepad<br>

---

# Data Sourcing
The dataset was provided by Mr Olanrewanju <br>
[Link to dataset](https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data) <br>
---

# Data Transformation & Modeling

## Data Cleaning & Transformation
### - Step 1
After importing the datasets using the import method in power bi:<br>
Then, the first task i did was to clean the data by renamed columns, converted columns to their right data types. Re formed the time and date column.
<br>
<br/>
![power query](https://user-images.githubusercontent.com/92920156/221429895-d072d633-ed98-4587-991f-00177b9f8d55.jpg)


### - Step 2
I created a date table using blank query and M code.<br>
I also disabled power bi's defualt date table by setting my created table as my date table

## Data Modeling
I enabled many to one relationship and cross filter direction from the destination table (fact table) to other tables using their respective keys.
<br>
<br>

![modelling](https://user-images.githubusercontent.com/92920156/221429968-3b8f1b8c-67a2-4e6d-9883-81e783037f27.jpg)

---

# Findings and Recommendations 

## This dashboard contains
<br>

Which contains 5 main visuals, 4 cards and 3 slicers
### The cards shows:
- The Average value of P.M 2.5
- The Average Temperature Value
- The average Value of precipitation per hour (average of both average of raining hours and average of snowning hours)
- 
### The slicers shows:
- Year Slicer to filter between years
- Month Slicer to filter between Months
- Time period within a day to filter between periods
 <br>

![filters and cards](https://user-images.githubusercontent.com/92920156/221430407-f03e0e29-cc0b-4cb0-b715-cb37664199f3.jpg)


<br>

### Now to the Visuals

- ### The first visual contains an area chats shows the average value of P.M 2.5 per Months
#### Importance of The visual
This visual will make it easier for the company to know which of the months had the highest average value of P.M 2.5
<br>

![PM 2 5 BY MONTHS](https://user-images.githubusercontent.com/92920156/221430665-40d514ab-b766-4725-bfbb-d18452742475.jpg)


- ### Line Chats showing the hours of precipitation (snow and rain where representended with different lines)
This visual shows the number of request by type
#### Importance of The visual
This will enable the stakeholders know the type of request which are being received.

- ### Pie chart showing the no of request by department
#### Importance of The visual
This will enable the stakeholders know the department that's receiving the most requests.

- ### Bar Charts Showing the number of request by day
#### Importance of The visual
This will enable the stakeholders know the days/ period they are receiving the most requests


![dashboard](https://user-images.githubusercontent.com/92920156/221430067-348845bf-60f8-4474-b0be-3f61195071b4.jpg)
## Findings
South queens neighborhood had the most requests, with public services department having the most requests.<br>
While mental and funitures had the most reports.

## Recommendation
I will recommed the stakeholders to take critical note of department with the most reports and those with the most report over due and compare them with those with lesser report in other to recommed and effective way to reduce the overdue status
<br><br>
<img src= "https://user-images.githubusercontent.com/92920156/214137077-99aaa4e8-6833-4339-85df-2c41d7e81412.jpg" width="50%" height="80%"><br>

<img src= "https://user-images.githubusercontent.com/92920156/214137339-3be0293a-97d4-4bb5-83fd-25818c3e575a.jpg" width="50%" height="80%"> <br>

<img src= "https://user-images.githubusercontent.com/92920156/214137365-bcd16443-8288-4446-9fd1-15b397faefc4.jpg" width="50%" height="80%"> <br>


[Link to live Report](https://app.powerbi.com/view?r=eyJrIjoiNTkxOTcwMDctOWE0Yy00NDBlLTk3MzgtOWI2YjA1ODVjMWRiIiwidCI6Ijg4ZTlhN2RjLTU2MzMtNGM2Ni1iNjZjLTkyZGY1Y2E3NDhmYyJ9&pageName=ReportSection)



