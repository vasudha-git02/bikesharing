# NYC Citibike 

## Purpose:
Import data into Tableau.
Create and style worksheets, dashboards, and stories in Tableau.
Use Tableau worksheets to display data in a professional way.
Portray data accurately using Tableau dashboards.

## Overview of the statistical analysis:
Des Moines requested data for a business proposal. August 2019 Citibike data from NYC was reviewed by looking at geographical data as well as data disaggregated by user types and genders to determine if it would be a good investment for Des Moines. Other data points include usage durations, peak usage times, and the key target market.

## Link to Tableau Story:
https://public.tableau.com/app/profile/vasudha1634

## Cleaning the Data:
Jupyter Notebook was used to change the trip duration data to a datetime field. 

- Dataframe data types before conversion

<img width="758" alt="df before conversion" src="https://user-images.githubusercontent.com/104597335/184211973-3582f8dd-57da-49a9-9ab7-5b94ebcb47a9.png">

- Dataframe data types after conversion

<img width="758" alt="image" src="https://user-images.githubusercontent.com/104597335/184212082-43d97a2e-643d-4b53-b23e-a940b9fb3367.png">



## Results of the NYC Citibikes Analysis:
For NYC, there were some interesting geographical areas of interest. Some trips were outside the main city center. Other areas followed the along the river. Future analysis would need to include a geographical review.

1. Checkout Times for All Users
Checkout Times for All Users . 


<img width="758" alt="Checkout Times for Users" src="https://user-images.githubusercontent.com/104597335/184212119-141b3536-8ed0-4309-b10f-02389bb4c76a.png">


2. Checkout Times by Gender
Checkout Times by Gender Males are significantly higher users than others. 

<img width="763" alt="Checkout Times for Users by Gender" src="https://user-images.githubusercontent.com/104597335/184212186-df25b946-63d6-441a-9e70-3b348a966c01.png">


3. Trips (Weekday per Hour)
Trips (Weekday per Hour) 6-10 am and 5-8 PM are peak riding hours during the weekday and 8 am to 7 pm on the weekends.


<img width="782" alt="Trips by Weekday per Hour" src="https://user-images.githubusercontent.com/104597335/184212907-efaa7945-d641-4ebc-ad5a-f2ae6b553d79.png">


4. Trips by Gender (Weekday per Hour)
Trips by Gender (Weekday per Hour) Males are high users during the peak hours. 

<img width="778" alt="Trips by Gender" src="https://user-images.githubusercontent.com/104597335/184212987-f25727bc-fb58-41d8-a58d-15b6f94fc9e7.png">


5. Trips by Gender and User Type (Weekday per Hour)
Trips by Gender and User Type (Weekday per Hour) Males subscribers are the highest users followed by female subscribers. 


<img width="793" alt="User Trips by Weekday by Gender" src="https://user-images.githubusercontent.com/104597335/184213057-3cc0389b-638c-4c9d-ac68-f96dae30b790.png">



6. Number of Rides per Hour
Number of Rides per Hour Non-peak hours are 1-5 am.

<img width="764" alt="Peak Riding Hours" src="https://user-images.githubusercontent.com/104597335/184213090-61ef7713-3fbe-4cce-9b34-4d5d62fb7d83.png">



7. Number of Rides with Bike ID
Number of Rides with Bike ID The divergence line shows that there are high use on 1/3 of the bikes. 


<img width="769" alt="Bike Utilization" src="https://user-images.githubusercontent.com/104597335/184213116-3175b22d-5891-464d-b806-16dc75c4f05f.png">



## Summary:
Bike Repairs for 1/3 of the Citibikes need to be done during non-peak hours around 1-5 am.
Male subscribers are the highest users and follow the traditional high use times of travel to and from work.
Target market should be males needing transportation to work and weekend activities and push for subscribing to the services.

## Additional Analysis:
For NYC, there were some interesting geographical areas of interest. Some trips were outside the main city center. Other areas followed the along the river. Future analysis would need to include a geographical review.

1. Ride Starting Locations by Gender
Ride Starting Locations by Gender Males are more likely to start a trip farther than the main city center of NYC than others. 


<img width="769" alt="Ride Starting Locations by Gender" src="https://user-images.githubusercontent.com/104597335/184213374-624a6909-fd82-4aaf-8ac3-6cbdd9548154.png">



2. Ride Ending Locations by Gender
Ride Ending Locations by Gender Males are more likely end a trip across the river in the southwest area of NYC than others. 



<img width="767" alt="Ride Ending Locations by Gender" src="https://user-images.githubusercontent.com/104597335/184213413-2d762c73-f667-41ae-819c-caa190e71e29.png">

