# Project Ford GoBike System Data, Dataset Exploration
Karina Condeixa

Seventh project for my Data Analyst Nanodegree by Udacity. <br/>
<br/>
The main objective is to Communicate Data Findings from a dataset from Ford GoBike System Data. I explored data from September of 2019. <br/>

Ford GoBike System Data is hosted at https://www.lyft.com/bikes/bay-wheels/system-data. <br/>


## Table of Contents
•	Exploratory analysis<br/>
•	Explanatory Data Analysis<br/>
•	Slides<br/>

## Tools
I used Python 3.6 in Jupyter Nobebooks importing  numpy, pandas, matplotlib and seaborn.<br/>

## How I made it

After a first exploratory view, I chose to simplify the dataset according to my targets. So, I dropped columns
of the stations (coordinates), and I created columns of age, age group and weekdays. I noticed that the
gender female has no outliers in informing the date of birth, hence the age.<br/>

In the exploratory analysis, I explored different types of visualizations for my variables and found
interesting features. <br/>
Regarding the users and trips, men and people between 18 and 39 years old are a majority
on trips. Subscribers are also a majority in the trips, they use these bikes regularly on weekdays, mainly for
short trips. Saturday has a lower demand for bikes. Strangely, the behavior of 70+ change on Wednesdays
and on Fridays, they have a higher variation in the duration of trips.<br/>

I chose the results to put in your explanatory analysis according to the relevance they have to draw the user
profile and demands per bike on weekdays.<br/>

I had good feedback given by a Data Analyst in a preliminary version of the exploratory analysis and I have applied some of her suggestions in my project.<br/>

## References
- https://towardsdatascience.com/ways-to-detect-and-remove-the-outliers-404d16608dba
- http://localhost:8888/notebooks/Documents/07-Programming/Udacity/Nanodegree_DataAnalysis/5-
Data_visualization/Project/communicate-data-exampleproject/
Example%20Project/Example_Project_Diamonds_Part1.ipynb
- https://github.com/J2Naughton/FordGoBike/blob/master/FordGoBikePart1.ipynb
- https://github.com/burakgunbatan/UdacityProject---
CommunicateDataFindings/blob/master/Exploration_Ford_GoBike_BurakGunbatan.ipynb
- https://github.com/meet3012/Ford-GoBike-System-Data-Visualization/blob/master/Data-Explorationwith-
Bike-Data.ipynb
- https://github.com/paulfoley/Udacity_Nanodegree-Data_Analyst/blob/master/Ford_GoBike-
Analysis/Ford_GoBike-Analysis.ipynb
- https://www.tutorialspoint.com/seaborn/seaborn_linear_relationships.htm
-Documentations
-Udacity course
- https://stackoverflow.com/questions/34796451/changing-the-marker-size-in-python-seaborn-lmplot
- Life expetance in USA: 78 years and average age in USA: 38 years, in
https://www.google.com/search?client=firefox-bd&
sxsrf=ACYBGNTxM7EZwHhzEi3LOM_4PyjP3ZlixQ%3A1570911206033&ei=5jOiXaHXAcT5sAf
6gLn4DA&q=averge+life+expetance++in+us&oq=averge+life+expetance++in+us&gs_l=psyab.
3..0i13l10.12434.20264..20754...0.2..0.184.1798.5j10......0....1..gwswiz.......
0i71j0i7i10i30j0i13i30j0i8i13i30j0i8i13i10i30.yZj9_rmChPs&ved=0ahUKEwih4qKjxJflAhXEP
OwKHXpADs8Q4dUDCAo&uact=5
- https://www.geeksforgeeks.org/create-a-new-column-in-pandas-dataframe-based-on-the-existingcolumns/
- http://www.datasciencemadesimple.com/drop-delete-rows-conditions-python-pandas/
