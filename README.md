Interactive vizualization of NYC Bikesharing Data using Tableau Public. 

# NYC_Bikesharing
# Overview
To create a visual bike trip analysis of the NYC Citi Bike System whose results can be used to create a similar ride sharing system in Des Moines. 
For this analysis, we’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, create a set of visualizations to:

* Show the August Peak Riding Hours/breakdown of annual subscribers vs. short-term customers/Gender breakdown
* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.
* Show the top starting and ending locations

# Resources
* **Data Sources:** Select 201908-citibike-tripdata.csv.zip from [Citi Bike System Data](https://s3.amazonaws.com/tripdata/index.html. This zip file contains all the August 2019 data. 
* **Software:** Tableau Public, Python 3.8.8, Pandas Dataframe, Jupyter Notebook 6.3.0

# Results
Link to Tableau Story Public : [CitiBike NYC Bikesharing](https://public.tableau.com/app/profile/ramya.ramamurthy/viz/CitibikeNYCBikesharing/CitiBikeNYCBikesharing)

Place your cursor over the charts in the link above for exact breakdowns.

1. August Peak Riding Hours/breakdown of annual subscribers vs. short-term customers/Gender breakdown.
      
<img width="1161" alt="Screen Shot 2022-02-04 at 2 21 58 PM" src="https://user-images.githubusercontent.com/75961057/152611231-ae6cc223-ad9f-4d16-8240-d769b563bf08.png">


* Of the bike renters: ~65% of them are Male
* annual subscribers : short-term customers : ~81% : 19%
* Peak riding times are: Mornings 8-9AM and Evenings 5-8PM

2. Checkout times for Users
<img width="1054" alt="Screen Shot 2022-02-04 at 2 20 18 PM" src="https://user-images.githubusercontent.com/75961057/152611242-edf8c0fc-91cc-4b4e-a57d-8138332b30d4.png">


- Average trip duration is less than 20 minutes with shorter trips of 5-10 minutes being the highest. 

3. Checkout Times by Gender

<img width="1054" alt="Screen Shot 2022-02-04 at 2 20 01 PM" src="https://user-images.githubusercontent.com/75961057/152611252-e4269f6d-ff89-4bad-9e19-81916de78fb8.png">

- There is no significant difference in the tripduration between Male and Female Gender. 

4. Trips by Weekday for Each Hour

<img width="1056" alt="Screen Shot 2022-02-04 at 2 19 37 PM" src="https://user-images.githubusercontent.com/75961057/152611303-d25999da-2633-4510-8148-b2c7f1d14ac9.png">

- Saturday and Sunday have the high ridership from 9AM - 8PM  with weekdays being busy between 5-8PM

5. Trips by Gender (Weekday by Hour)
<img width="1064" alt="Screen Shot 2022-02-04 at 2 19 14 PM" src="https://user-images.githubusercontent.com/75961057/152611320-4f4a721e-6973-4465-846e-563abc6e09f6.png">

- Male and female riders follow the results of the previous graph - Saturday and Sunday have the high ridership from 9AM - 8PM  with weekdays being busy between 5-8PM

6. User Trips by Gender by Weekday
<img width="1134" alt="Screen Shot 2022-02-04 at 2 17 34 PM" src="https://user-images.githubusercontent.com/75961057/152611330-3da012b8-5588-412b-905f-fd950bb11b86.png">

- Male ridership increases mainly on Thursday and Friday tapering slightly on the weekends. 

7. Top Starting Locations
<img width="1069" alt="Screen Shot 2022-02-04 at 2 18 32 PM" src="https://user-images.githubusercontent.com/75961057/152611350-9e9e5b55-73ab-4bed-997a-162d14aea6c8.png">

-The maximum number of rides start are in the heart of NYC in the island of Manhattan, Bronx and Queens with ridership reducing towards the suburbs. 

8. Top Ending Locations

 <img width="1057" alt="Screen Shot 2022-02-04 at 2 18 11 PM" src="https://user-images.githubusercontent.com/75961057/152611392-550b4616-d7ba-45e5-af62-be95a5c8b93e.png">

 -Ending location map shows a similar story to the starting location story which corroborates with tripduration on average being less than 20 minutes. 
9. Bikes due for repair
<img width="1165" alt="Screen Shot 2022-02-04 at 2 16 49 PM" src="https://user-images.githubusercontent.com/75961057/152611417-c1a3e0b0-f9de-4df4-bd48-02e5fa00c299.png">

-  The bikes used most frequently will probably be the ones that require the most maintenance. The green squares are bike ids that have maximum bike utilization with the yellow squares are ones with moderate usage and the oragne-red ones are those bikes with low usage. The squares also decline in size according to usage. this graph is helpful in determining how many bikes need maintenance. 
 


# Summary
From the visual analysis of the NYC Bikesharing Data, we see that
* Average tripduration is less than 20 minutes regardless of Gender
* 65% of renters are Male
* The busiest time for rentals is Weekdays 5-8PM and Weekends 9AM-8PM 
* 81% of renters are Subscribers who regularily use the service. 

It would be advisable to also look at visualization for the following to understand the demographics and locations to market to. 
* Trip Distance and 
* Duration by Age 
* Bike Utilization
