# School District Analysis

Data analysis project using pandas to analyze school district tests.  

## Overview of Project

Maria the chief data scientist for a city school district is responsible for analyzing data from a variety of sources and a variety of formats. She is tasked with preparing all standardized test data for analysis reporting and presentation to provide insights about performance trends and patterns. The analysis was made in the students reading and math scores. 

On the second part of the analysis all grades from students in the Thomas High School of the 9th grade were taken out and repeated the analysis. 


### Purpose

The purpose of this project is to get insight on the performance of schools in the district depending on the budget and size of the school. 

Also, how were the district statistics changed after the grades of Thomas High School of the 9th were not taken in consideration. 



## Results

We are going to compare the results of the first analysis and how affected taking out the grades of the 461 students of 9th grade of the Thomas High School.

Loc method to select the students of the Thomas high School of the 9th grade:

![Codigo para sacar los 461](https://user-images.githubusercontent.com/96758511/151742155-acbc311a-bf38-4d26-86a0-05b3c1f67398.png)


### How is the district summary affected?

To see more clearly how the school summary was affected we need to use more decimals because the number of students not considered in the calculation is small compared to the total. 

In the images we can see how the averages changed from the original calculation and not considering the 461 students. 

District summary before the change

![District summary con 461](https://user-images.githubusercontent.com/96758511/151742265-bf187070-9a35-4b21-8a66-53ca6c4850d4.png)

District summary after the change

![District summary sin 461](https://user-images.githubusercontent.com/96758511/151742292-b771e32c-34a2-4b18-b949-df764f19f093.png)


### How is the school summary affected?

The school summary before was: 
Average Math Score	83.418349
Average Reading Score	83.848930
% Passing Math	93.272171
% Passing Reading	97.308869	
% Overall Passing  90.948012
	
  

And after: 
Average Math Score	83.350937
Average Reading Score	 83.896082
% Passing Math	93.185690	
% Passing Reading	 97.018739	
% Overall Passing  90.630324
	
  

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

There was a reduction in math metrics of the school when the students were excluded from the calculation. This can be evidence that the grades were modified


### How does replacing the ninth-grade scores affected the following: 
•	Math and reading scores by grade: The students of the 9th grade appear with a NaN
•	Scores by school spending: Thomas appear with NaN. 
•	Scores by school size: The overall passing rate reduces from 90.621 to 90.557 after the change.
•	Scores by school type: There is a small reduction in the passing average of the charter schools without the students.


## Summary
We can see that the averages of the Thomas High School reduces after we take out the 461 students of the calculation. Some of the reductions are in:
•	Average Math score
•	% Passing Math
•	% Overall Passing
•	Medium size school % Overall Passing 
•	Charter school results

We can conclude that it was very possible that the math grades of the 9th grade of the Thomas High School were augmented when they were reported. 



