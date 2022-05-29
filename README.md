# Surfs Up #

# Overview and Purpose #
This analysis made use of VS Code, SQLite, and PostgresSQL databases to analyze weather trends. These queries provided temperature and precipitation trends for the city of Oahu. An investor is interested in creating a Surf and Ice Cream shop. Using the weather analysis, the investor will determine if temperature and precipitation trends will create variance in the shop remaining open during the months of June and December. Ideally, the investor is interested in the shop remaining open and sustainable year-round. The following analysis reports on these weather trends. 

# Results #

***Analysis for June and December***

The average (mean) temperature for June is 75°F and the average precipitation is 0.14 inches. 

<p align="center">
<img src="https://github.com/teachjanderson/surfs_up/blob/main/Resources/June%20Prec_Temp.png">

The average (mean) temperature for December is 71°F and the average precipitation is 0.22 inches. 
  
<p align="center">
<img src="https://github.com/teachjanderson/surfs_up/blob/main/Resources/December%20Prec_Temp.png">
  
To further check the frequency of temperature during June and December, the following plots demonstrate the months respectivtly. 
  
<p align="center">
<img src="https://github.com/teachjanderson/surfs_up/blob/main/Resources/June.png">
  
<p align="center">
<img src="https://github.com/teachjanderson/surfs_up/blob/main/Resources/December%20Graph.png">

While both months demonstrate a low amount of precipitation overall, the following points should be considered based on the analysis:
  - The precipitation for both months appears low enough that interference with the surf and ice cream shop should have minimal interruptions. 
  - The plot for the month of June demonstrates most days are above 70°F and should provide pleasant weather for business. 
  - The plot for the month of December demonstrates a slightly lower temperature trend. While many days are above 70°F, there are many below that range. The business should prepare for lower sales in surfing and ice cream during this month than in June, but will still have a number of days that are profitable for business. 
  
# Summary #

In reviewing the average temperature in June and December, along with running two additional queries to determine the average preciptation, it is clear the variance is minimal and will provide opportunities for profit. The surf and ice cream shop will expereince multiple days each month with positive weather for its business. To determine is this remained true throughout the rest of the year, two additional months were queried. Both October and April are known for fluctuation days for weather. However, in reviewing the data, it is clear even these months shows positive weather trends as demonstrated in the table below. 
  
<p align="center">
<img src="https://github.com/teachjanderson/surfs_up/blob/main/Resources/april_oct.png" />
