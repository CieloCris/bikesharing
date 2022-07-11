# Bikesharing Analysis

## Overview
In this module, our goal is to analyze an NYC Citi Bike dataset in order to decide if it is possible to replicate a similar cycling project in Des Moines, Iowa. In other words, our purpose is to create visualizations based on bike-sharing data to determine if We can replicate the business proposal in another city.

To achieve our goal, we use **Tableau Public, in addition to Python, Jupyter Notebook, and Pandas**.

## Results

We present the analysis in the following steps: 1) the data modification on the dataset, 2)the visualizations, and 3)the link to Tableau's story and the summary.

### 1) The first step of this project was to adapt the dataset. In this case, We needed to convert the Tripduration column to a DateTime format with the help of Python and Pandas, as we can see in the following screenshots:

![Alt text](/Resources/uno.png "imagen1")

![Alt text](/Resources/dos.png "imagen2")

![Alt text](/Resources/tres.png "imagen3")

![Alt text](/Resources/cuatro.png "imagen4")

### 2)The next step was to create the visualizations that the challenge requested: 

#### The following image explains the Citi Bike experience and shows purpose of our project.
![Alt text](/Resources/portada.png "imagen100")

#### Below, a screenshot shows general information of our challenge. In August 2019, 2,344,224 persons used the Citi Bike service. Most of them were male and subscripters.
![Alt text](/Resources/general.png "imagen10")

#### In the following chart, we present the checkout times by user and we can conclude that most of the trips takes than 20 minutes.
![Alt text](/Resources/check1.png "imagen11")

#### This chart show the checkout times by gender. As We can see, Citi Bike have more males users than females.
![Alt text](/Resources/cinco.png "imagen12")

#### The heat map below shows Trips by Weekday.
![Alt text](/Resources/heat1.png "imagen13")
From this first heat map, we can deduce that the Citi Bike service is used more for commuting to work during weekdays, that is, from 7:00 to 9:00 AM, and from 5:00 to 7:00 PM. The day with the most users riding the bikes is Thursday.

#### Heat map with Trips by Gender (Weekday per Hour)
![Alt text](/Resources/heat2.png "imagen14")
The second heatmap shows the trips per week according to the user's gender. From the map, we can conclude that men use bikes more when traveling to the office. We can also see that people whose gender is unknown generally used the service over the weekend.

#### Heat Map with User-type Trips by Gender by weekday
![Alt text](/Resources/heat3.png "imagen15")
We can conclude that male subscribers are the largest group using Citi Bike in NYC. In order to understand the bike service's trends by gender, it's important to study more months and characteristics.![Alt text](/Resources/extra.png "imagen16")

#### Top Starting Locations and Top Ending Locations
![Alt text](/Resources/extra.png "imagen17")

#### Start Location by User-type
![Alt text](/Resources/extra2.png "imagen18")

#### Bike Utilitation
![Alt text](/Resources/extra3.png "imagen18")

## Summary 

The data and visualization analysis allows us to conclude that the majority of Citi Bike users in New York City are male subscribers. Women use the service less and are often casual customers, not subscribers.

We deduce that Citi Bike is an attractive transportation alternative in New York since this city is known for its traffic congestion. Bike rides are more in demand from 7:00 to 9:00 AM, and from 5:00 to 7:00 PM, which is the time to commute from home to the office and vice versa.
New York is a city with a high population density and, in addition, it has a lot of tourism, so the bike service is also used to visit attractive places, such as Central Park and downtown. According to the maps and graphs analyzed, there is a greater demand for Citi Bikes in tourist and business areas. The moment with the highest demand for bike rides is Thursday afternoon.

Most of the bike trips are short, with an average duration of fewer than 20 minutes of use, although there are cases of longer trips, although most of them are no longer than an hour.

In this case, it would be worth analyzing why the service has fewer female subscribers and customers, in order to design a marketing campaign to attract female users.

Citi Bike's services in New York are successful because it covers the transportation needs of a densely populated urban area, however, it would be important to study whether it would be viable to replicate the business in Des Moise, Iowa. In other words, we need to study various aspects of that city, such as streets, routes, traffic congestion, population density, public transport, cycle paths, and tourist sites.

## Tableau Story Link:
Click [Here](https://public.tableau.com/app/profile/cielo.mejia/viz/Challenge_Bikesharing/NYCCitiBikeAnalysis?publish=yes) to visit the complete analysis.

## Additional visualizations

- It would be convenient to create a map that shows the distance covered in each bike trip, to make the maintenance of the bikes more efficient and to know the most traveled routes.
- Visualize the age of the user and the use of the service. It would also be a good idea to add a column that identifies whether the user is a tourist or a resident.
- It would be interesting to identify the Top Starting and Ending Locations by gender to study more factors that could explain why women use bikes less.
- It would also be attractive to know more data on traffic and cycle paths to make new visualizations and expand our analysis

We conclude that it is necessary to analyze the conditions of Des Moise, Iowa to decide if replicating the Citi Bike business model would be successful in that place.
