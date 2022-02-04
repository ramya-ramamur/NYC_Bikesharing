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
      
<img width="1113" alt="Screen Shot 2022-02-04 at 1 00 23 PM" src="https://user-images.githubusercontent.com/75961057/152603261-c5138c5e-f996-4a46-abcf-9eee14e2818a.png">

* Of the bike renters: ~65% of them are Male
* annual subscribers : short-term customers : ~81% : 19%
* Peak riding times are: Mornings 8-9AM and Evenings 5-8PM

2. Checkout times for Users
<img width="997" alt="Screen Shot 2022-02-04 at 1 01 30 PM" src="https://user-images.githubusercontent.com/75961057/152603349-1338abb1-e35a-43a4-8ce1-b549492b2188.png">

- Average trip duration is less than 20 minutes with shorter trips of 5-10 minutes being the highest. 

3. Checkout Times by Gender
<img width="998" alt="Screen Shot 2022-02-04 at 1 02 07 PM" src="https://user-images.githubusercontent.com/75961057/152603541-ad075314-6606-4006-831d-d21b6bdf6479.png">

- There is no significant difference in the tripduration between Male and Female Gender. 

4. Trips by Weekday for Each Hour
<img width="1001" alt="Screen Shot 2022-02-04 at 1 02 56 PM" src="https://user-images.githubusercontent.com/75961057/152603581-39c12544-a26c-4bf3-9cbb-6db7f67e4f80.png">
- Saturday and Sunday have the high ridership from 9AM - 8PM  with weekdays being busy between 5-8PM

5. Trips by Gender (Weekday by Hour)
<img width="1002" alt="Screen Shot 2022-02-04 at 1 03 14 PM" src="https://user-images.githubusercontent.com/75961057/152603622-9bf135b2-c056-4771-b7a7-daa96c664057.png">
- Male and female riders follow the results of the previous graph - Saturday and Sunday have the high ridership from 9AM - 8PM  with weekdays being busy between 5-8PM

6. User Trips by Gender by Weekday
<img width="998" alt="Screen Shot 2022-02-04 at 1 12 04 PM" src="https://user-images.githubusercontent.com/75961057/152603767-461bf02e-a269-4567-81fc-7e260a2d9606.png">
- Male ridership increases mainly on Thursday and Friday tapering slightly on the weekends. 

7. Top Starting Locations
<img width="995" alt="Screen Shot 2022-02-04 at 1 03 44 PM" src="https://user-images.githubusercontent.com/75961057/152603638-0571b5d9-b539-4f15-b375-579add89b086.png">

-The maximum number of rides start are in the heart of NYC in the island of Manhattan, Bronx and Queens with ridership reducing towards the suburbs. 

8. Top Ending Locations
<img width="986" alt="Screen Shot 2022-02-04 at 1 04 09 PM" src="https://user-images.githubusercontent.com/75961057/152603655-82edb844-c64b-4014-b487-459290919602.png">
 
 -Ending location map shows a similar story to the starting location story which corroborates with tripduration on average being less than 20 minutes. 

# Summary
From the visual analysis of the NYC Bikesharing Data, we see that
* Average tripduration is less than 20 minutes regardless of Gender
* 65% of renters are Male
* The busiest time for rentals is Weekdays 5-8PM and Weekends 9AM-8PM 
* 81% of renters are Subscribers who regularily use the service. 

It would be advisable to also look at visualization for the following to understand the demographics and locations to market to. 
* Trip Distance and 
* Duration by Age 
