#  Project 2: Meteorology

# Infomation location:

  Code URL: https://github.com/stephenscharkov/Project-2/blob/master/Code.ipynb
  
  README URL: https://github.com/stephenscharkov/Project-2/blob/master/README.md
  
# Problem Statement:

  This project was given to better undersand weather changes over the ocean as it moves towards land and to be able to analyze the data.  Using the Bulk Meteorology Instrument Package at two sites in Orgean wind speeds and rain rates will be compared between over the 2019 calander year. The code is writen in python and will inform the user of correlation between the cites. 

# Results:
  In Figures 1a and 1b the data for rain rates are ploted agenst wind speeds. Four circumstances implemented in the background of the plots to show times in which there is only rain, only wind, both rain and wind, or neither rain nor wind. 
  In the following garphs the following assumptions were made: 
  
    Rainy Days: >0.1mm/hr
    Windy Days: >2.5mm/hr 
    
  
  ![alt text](https://github.com/stephenscharkov/Project-2/blob/master/Fig1a.PNG)
  
  Figure 1a: Rain and Wind Rates for Oregon Offshore Surface Mooring

  ![alt text](https://github.com/stephenscharkov/Project-2/blob/master/Fig1b.png)
  
  Figure 1b: Rain and Wind Rates for Oregon Offshore Surface Mooring
  
  
  Comparing the two site in the cross colleaction graphs bellow we can see that both the sides have a strongly correlated. We can see that the 
  
  These times can then be compared between the two sites to determine cross corrilation and see how weather events my move and expand in the region. Comparing the Wind Speeds between the sites and cross corrilating, there is a strong corrilation. This is as expected as the wind is a large scale event and it would be unusual for there to be a high number of data points where one site is windy and the other isn't. Based upon the overlayed graphs as seen in figure 3, the offshore wind is higher than the shelf with a slight lag. This also follows expectaions as the wind has little resistance over the open ocean, but as it approaches shore thermal resistance become more prevelant. The Maximum correlation occurs at lag 1, indicating near simultainious events based upon the time period examined. As the data is recorded roughly every 8 hours, this indicates that the weather travels between the two sites in 8 hours or less. The max correlation value for the wind is 0.715 and indicates a decently strong correltation.

  ![alt text](https://github.com/stephenscharkov/Project-2/blob/master/Fig2a.png)
  
  Figure 2.a: Wind Correlation Data
  
  ![alt text](https://github.com/stephenscharkov/Project-2/blob/master/Fig2b.png)
  
  Figure 2.a: Rain Rate Correlation Data
