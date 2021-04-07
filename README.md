# **PyBer_Analysis**
## **Project Overview** 
We have been assigned a project from a ride-sharing service provider 'PyBer' to analyse the data based upon cities and rides, in tabular format, with thousands of rows.

The analysis outcome is required to be able to communicate findings in such a manner that it is understandable, informative and that it can engage its stakeholders to enable them to make key decisions for **Access** and **Affordability** of their ride-sharing service depending upon the type of cities where these services are being offered.

### **Purpose:**
This analysis is being done in order to find out if there are any disparities among the city types. This means we need to see how the usage of their service is impacted when the rides are in a rural city, in suburban city and when in urban city.

We should be able to detect from the given datasets if there are any patterns and trends of their earnings as well as their presence, and if there is relation about ability of riders to use their services, when it comes to 'type' of any city in the dataset. 

To be able to obtain answers to above, we need to find a relationship between the type of city and the number of drivers and rides as well as average fare per ride and average fare per driver through a Summary.

This analysis should be shareable across the teams so that the company is able to plan effectively and make informed decisions in order to improve their services in terms of accessibility of their service, make it affordable,for under-served neighborhoods, and also make company more profitable.

### **Resources:**
- city_data.csv
- ride_data_csv

We are provided above datasets which contain the details of rides and details of drivers in the cities to use for our analysis.
## **PyBer_Analysis Results**

To perform the analysis, following steps were taken:
A **PyBer Summary DataFrame** has been created, which displays the ride sharing data of PyBer, categorized as per the types of cities namely **Rural**, **Suburban** and **Urban**.

This DataFrame has **Total Rides**, **Total Drivers**, **Total Fares**, **Average Fare Per Ride** and **Average Fare Per Driver** for every **City type**. 


![PyBer_Summary_DataFrame](https://github.com/kirtibhandari/Pyber_Analysis/blob/main/Resources/DataFrame_Pyber_Summary.png)


Secondly, we have summarized the data on the basis of weeks for first four months of year 2019 and the type of city where we have weekly fares earned by drivers providing PyBer ride-sharing services in rural cities, suburban cities and Urban cities.


![Weekly_Fare_Sum_Data](https://github.com/kirtibhandari/Pyber_Analysis/blob/main/Resources/Weekly_Fare_Summary_by_City_Type.png)


Also, a multi-line chart has been plotted for visualization of the given data, organizing the data on the basis of **Weekly Fare Summary by City Type** for a period of four months.


![Multiple_Line_Chart](https://github.com/kirtibhandari/Pyber_Analysis/blob/main/Resources/Multiple_Line_Chart.png)


We used line chart as the dataset was time based, representing performance of Pyber over time. To make it easier for stakeholders to understand, as it being straightforwards, plots continuous data as points and joins them with a line. 

Also, through this kind of graph, it is easier to present a comparative analysis off multiple datasets.

On the basis of results we obtained, the following differences/disparities were found in ride-sharing data among the different city types:

- More developed a city is, more are the number of rides. Hence most rides are taken in urban cities than in suburban cities with least rides in rural cities.

- An urban city has most drivers compared to number of drivers in suburban cities and rural cities have least number of drivers.

- The total fares are least in rural cities, higher in suburban cities than rural and is highest in urban cities.

- Average fares per ride is higher in rural cities leading than those of suburban cities which then have costlier rides than rides in urban cities. Taking a Pyber ride is expensive to rural city residents than those in suburban and urban cities.

- Average fare per driver is most in rural type city whereas lower in suburban than rural city, and an urban city driver has lowest average fare.

-  Varying by the city types, as per the weekly summary graph depicts, how the usage of service varied during first four months of year 2019 for Pyber. 

    Clearly, suburban cities show least count of fluctuations in their weekly earnings last week of February 2019 and first week of April 2019, hence better average performance over the period, i.e.neither very higher profits or higher losses among themselves, when we compare average performances and fluctuations of business brought in by rural and urban cities, among rural and urban cities respectively. Rural and urban cities have more fluctuations.

-  Also, total fares by city types are highest for urban cities, lower in suburban cities and lowest in rural cities.

## **Pyber_Analysis Summary**

Business recommendations to the CEO for addressing above disparities among the city types are as follows:

1. PyBer can issue weekly discount coupons to most frequent riders in rural cities to invite them to use their services more frequently.
2. Weekly or fortnightly promotions can be launched where drivers can be given targets to complete more number of rides where they will be given extra incentives for driving more, in suburban cities.
3. Long trips may be made more lucrative for the drivers by increasing per mileage earnings they will make.
4. Inter-city trips for rural and suburban drivers may also enable them to earn more than local trips.
5. Drivers in all types of cities may launch surge areas where driver demand is high than the other areas of cities in particular times so as they can increase accessibility of services to riders.
6. Riders can also be given hour-bound(usable only in some hours of the day) discount coupons that they are motivated to use Pyber than other modes of transit.  

