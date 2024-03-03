# Will_the_Customer_Accept_the_Coupon
This assignment aimed to review the attributes associated with influencing a customer to purchase a product while they were out driving. The dataset included but was not limited to, customers with varying degree levels, education levels, marital status, spending habits, weather, and time of day the coupon was electronically delivered. The Jupyter Notebook I used to complete this assignment can be found here. 

https://github.com/shannonamcgill/Will_the_Customer_Accept_the_Coupon/blob/main/assignment_5_1_starter/SMcGill_Module5.ipynb

My initial steps were to review the data to understand better what columns were present and identify any required cleanup. From this step, I removed one of the columns as it was over 99% empty. 

I then reviewed the coupon distribution amongst different restaurant types. This can nicely be displayed using seaborn's boxplot as demonstrated below.

![alt text](https://github.com/shannonamcgill/Will_the_Customer_Accept_the_Coupon/blob/main/assignment_5_1_starter/images/Distributed_Number_of_Coupons_Barchart.png?raw=true)

Following the box plot distribution, I created a histogram of the of temperature when I customer accepted the coupon. This shows that people were more likely to accept the coupon when temperatures were higher.  

![alt text](https://github.com/shannonamcgill/Will_the_Customer_Accept_the_Coupon/blob/main/assignment_5_1_starter/images/Histogram_of_Temperature.png?raw=true)

I then analyzed other attributes that influence a bar customer to accept a coupon. After looking at various attributes, my interpretation of the data leads me to believe that the biggest influence on accepting the bar coupon was how often the customer drank alcohol. This is displayed with the following bar charts. 

![alt text](https://github.com/shannonamcgill/Will_the_Customer_Accept_the_Coupon/blob/main/assignment_5_1_starter/images/Coupon_Acceptance_Rate_for_Number_of_Bar_Visits.png?raw=true)

This chart compares the acceptance rate between drivers who go to a bar more than once a month and are over 25 to all others.

![alt text](https://github.com/shannonamcgill/Will_the_Customer_Accept_the_Coupon/blob/main/assignment_5_1_starter/images/q4_Bar_Customer_Segmentation_for_Number_of_Bar_Visits.png?raw=true)

Using the same process, I compared the acceptance rate between drivers who go to bars more than once a month and had passengers who were not a kid and had occupations other than farming, fishing, or forestry.  

![alt text](https://github.com/shannonamcgill/Will_the_Customer_Accept_the_Coupon/blob/main/assignment_5_1_starter/images/q5_Bar_Customer_Segmentation2.png?raw=true)

I love coffee and visiting new coffee shops both locally and while traveling. For my independent study, I chose to look at the influences on someone’s choice to accept a coupon for coffee shops.

I followed the same process for cleaning and the initial data review as I did with the bar data. But I also chose to include seaborn's subplot functionality. This allowed me to plot the value counts of several of the coffee dataset's attributes. Choosing a few that I thought would have the most influence on someone's acceptance, I created the following charts. 
 

![alt text](https://github.com/shannonamcgill/Will_the_Customer_Accept_the_Coupon/blob/main/assignment_5_1_starter/images/q7_Yes_Factor_1.png?raw=true)

Using these plots, I could determine which sub-categories within each attribute had the most influence on a customer. This led me to identify a group of attributes with an acceptance rate of 63%.
