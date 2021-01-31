# PyBer_Analysis1

## Overview of analysis
    This project was designed to analyze to sets of data and create visual representations for PyBer, a ride-sharing comapny,
    from Jnauary to early May of 2019. These data includes the total rides, total drivers, total fare, average fare per driver, 
    and total fare per city type.
## Resources
    Data Source: city_data.csv, ride_data_csv
    Software: Python 3.9.7.Anaconda Navigator 1.9.6, Jupyter Notebook 6.0.1
## Results
    Base on the city type, the data showed an overall direct correation between total rides, total drivers, and total fares, and
    showed an inverse relationship for average fare per ride and average fare per driver.
    
               Total Ride    Total Drivers   Total Fares     Average Fare per Ride      Average Fare per Driver
        Rural	   125	           78	  $4,327.93	                34.62	                  55.49
       Suburban	   625	          490	 $19,356.33	                30.97	                  39.50
        Urban	  1625	         2405	 $39,854.38	                24.53	                  16.57  

Based on our knowledge of ride-sharing services and basic economic principle lead us to expect an increase in price based on increase in demand, increased distance, and driver availability. In larger cities and urban areas, the number of drivers is about 30 times greater than in rural areas, which translates to an increased relative demand. In fact, there are so many drivers in the urban area that at any given time, many drivers are not contracted, as shown by the contrast between the total number of rides and the total number of drivers. Prices are likely also increased in rural areas based on the distance between destinations. At a glance, the line chart shows exactly what's expected: an overall higher volume in total fares for urban areas, lowest volume for rural areas, with suburban falling in  between.
   

    
    ![Chellenge Plot](PyBer_Analysis1/analysis/Chellenge.png)
   
    
## Summery
    Based on the above results, I have the following recommendations:

    1. Focus recruitment marketing resources in rural areas to increase the number of available drivers at a given time, 
       while decreasing recruitment marketing in urban areas.
    2. Place a cap on fare to keep the service affordable in rural areas. 
       This would make it more accessible to those who may be living in underserved service areas while still allowing for profit. 
    3. Increase user-facing marketing efforts across the board, but particularly in urban areas, 
       focusing on the services  affordability and short wait times based on driver availability.
