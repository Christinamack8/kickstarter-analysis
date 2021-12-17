# Kickstarter Analysis  
## Overview of Project
Performing analysis on kickstarter data to uncover some trends 

## Analysis and Challenges
My main challenges included figuring out the Countifs function to determine the Outcomes based on goals.  My formula's were not working as well as I missed a line row containing one of the ranges causing my chart to look off. All of the criteria's needed to be added which took me a while to figure out.

=COUNTIFS('Kickstarter '!$F:$F, "successful", 'Kickstarter '!D:D,"<1000", 'Kickstarter '!$R:$R, "plays")

Dates needed to be converted and column added to create the year.  Subcategory was added and Parent Category was fil
tered out.  

=YEAR([@[Date Created Conversion]])

## Outcomes based on Theater Launch Date Charts

![ima
ge](https://user-images.githubusercontent.com/95730183/146591443-1c3c9011-8104-48c9-b07d-597a83e8ad9a.png)

In May kickstarter campaigns had the most success with 111 successful, 52 failed, amd 3 canceled with a total of 111.  December saw the least amount of Kickstarters with 37, 35 failed, amd 3 canceled with the total being the least amount of theater outcomes of all the months.  

## Outcomes based on Goals Chart

![image](https://user-images.githubusercontent.com/95730183/146593234-717ae8c6-fcb5-4433-bba5-b39eb4242f07.png)
There were zero successful campaigns with goals  between 45000 to 49999.  Campaigns with goals less than 1000 were almost 80% successful.  

## A Written Analysis of the Results
### Summary of the limitations of the dataset

There is one goal that is 100,000,000 wich jumps from the previous goal by 70,000,000.  This could be considered an outlier and skew the data. 

### Recommendation for additional tables or graphs
An analysis and could be used to compare successful or failed kickstarters by years with a line chart.
An analysis and pie chart could be used to show the most successful types of kickstarters.  




