# Overview of analysis

Generate a story using Tableau to present data to possible investors in bike-sharing program in Des Moines. Data from NYC Citi Bike for the month of August was used, though the difference in population density is different, the data presented sheds light on the bike_sharing business potential.
Prior to this analysis python was used to modify the trip duration using to_datetime(), modify the gender column based on 0 (unknown), 1 (male), 2 (female) and calculating an age column. The age column had outliers with a range from 0 to 135. When doing analysis by age the range should be filtered to consider from 15 to 90 years old. 

## Results
The Tableau story gives answers to the following questions: 
- What is the ratio between subscribers and customers?
 ![Alt text]( https://github.com/Jimena-QM/bikesharing/blob/main/images/Prct_of_user_types.jpg "Percentage of User Types")
    - More than 80% of users are subscribers. If the bike-sharing program in Des Moines can consider a monthly fee for subscribers that will secure a certain revenue. 
- How long is each trip for Users?  
 ![Alt text]( https://github.com/Jimena-QM/bikesharing/blob/main/images/Checkout_times_for_users.jpg "Checkout Times for Users")
    - The majority of trips last less than 20min. This could indicate the number of bikes needed in Des Moines considering the short trips. 
- How long is each trip based on gender?   
 ![Alt text]( https://github.com/Jimena-QM/bikesharing/blob/main/images/Checkout_times_by_gender.jpg "Checkout Times by Gender")
    - Gender is not a factor on the trip duration, though we can see that there are a higher number of male riders. 
- What days of the week and hours are trips most frequent?
 ![Alt text]( https://github.com/Jimena-QM/bikesharing/blob/main/images/Trip_by_wkday_per_hr.jpg "Trips by Weekday per Hour")
    - Mon, Tue and Thu between 5pm and 7pm have the highest bike rentals. During those peak hours, all available bikes should be on the streets to avoid loosing clients. It can be inferred that the high use during those hours is due to travel from work to home.  Saturday's are also highly popular for bike rentals from 10am to 6pm, most likely due to tourists. If Des Moines has a high tourist area, bikes should be available during those hours. 
- Based on previous question, is gender a factor?
 ![Alt text]( https://github.com/Jimena-QM/bikesharing/blob/main/images/Trips_by_gender.jpg "Trips by Weekday per Hour by Gender")
    - Considering the previous answer, these visualization supports the hours and days of the week and it adds the fact that bike-sharing is most popular for men. 
- Based on previous question, is user type a factor?
 ![Alt text]( https://github.com/Jimena-QM/bikesharing/blob/main/images/User_trips_by_gender_by_wkday.jpg "Trips by Weekday per Hour by Gender and user type")
     - This heat map shows that most male and female users are subscribers and that the unknown gender comes from non-subscribers. Non-subscribers have a higher use during the weekend which could indicate tourists. 
- What time of day is best for bike maintenance?
![Alt text]( https://github.com/Jimena-QM/bikesharing/blob/main/images/Best_maintenance_hrs.jpg "Best times for Maintenance")
    - Knowing when are the best times to due maintenance and reduce the number of lost clients is important to understand the costs of maintenance during the hours and the available window. The bar chart above shows that during the hours of 2am and 4am is the optimal time for maintenance. 
    
## Summary
In conclusion, bike-sharing is  a business venture that can be very popular in Des Moines with a high number of subscribers. The priority of marketing should be male users who travel from work to home. Adding bike stations in business clusters can be effective. 
Knowing that the most popular trip durations is less than 20 min and the population in Des Moines the number of bikes needed can be calculated. It is important to consider the high density areas and the population in Des Moines in order to be a successfull business. 
Two additional visualizations that can be performed to make the presentation more robust are: 
- Number of rides by age. This visualization can tell the marketing team what age range is best for publicity. 
- Number of bikes by station. This will help us understand the number of bikes that may be needed in Des Moines by station.

Link to Tableau Dasboard
https://public.tableau.com/app/profile/jimena.quinones/viz/NYC_CitiBike_Challenge_16569764569040/CitiBike?publish=yes
