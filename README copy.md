# Bike_sharing

## Overview of the analysis

The purpose of this analysis is to convince investors about a bike-sharing program business proposal using data from the Citi Bike system web page

## Results

### Convert a column using Pandas

After downloading data, the first step was to convert the trip duration column from int64 to a datetime.Below is the code and the result

![Screen Shot 2021-05-25 at 5 02 17 PM](https://user-images.githubusercontent.com/78506782/119567959-f8a2a300-bd7a-11eb-8bf3-8447096a41fa.png)
 
### Analysis using Tableau

#### Tableau Public VIZ location

https://public.tableau.com/profile/francis7054#!/vizhome/NYCBikesharing_16219097517930/NYCBikesharing

#### Checkout Time

This graph shows the lenght of time that bikes are checked out for all riders

![Screen Shot 2021-05-25 at 5 17 04 PM](https://user-images.githubusercontent.com/78506782/119569648-08bb8200-bd7d-11eb-9519-3c30325d64b4.png)

#### Checkout Time by Gender

This graph shows the lenght of time that bikes are checked out for each gender

![Screen Shot 2021-05-25 at 5 19 02 PM](https://user-images.githubusercontent.com/78506782/119569851-4fa97780-bd7d-11eb-8a03-c9111e36d13a.png)

#### Trips by weekday for each hour

This heatmap shows the number of bike trips by weekday for each hour of the day 

![Screen Shot 2021-05-25 at 5 21 08 PM](https://user-images.githubusercontent.com/78506782/119570067-9bf4b780-bd7d-11eb-81fe-fd7c2161ac8d.png)

#### Trips by weekday for each hour by gender

This heat map shows the number of bike trips for each hour of the day by gender.

![Screen Shot 2021-05-25 at 5 23 51 PM](https://user-images.githubusercontent.com/78506782/119570348-fd1c8b00-bd7d-11eb-8614-1fb7e54dd490.png)

#### User trip by gender by weekday

Here we have the number of bike trips by user type, by gender for each hour of the day

![Screen Shot 2021-05-25 at 5 26 46 PM](https://user-images.githubusercontent.com/78506782/119570638-643a3f80-bd7e-11eb-865f-b724e8b8ea97.png)

#### Top Starting Locations

This map shows the top starting locations in New York City

![Screen Shot 2021-05-25 at 5 28 23 PM](https://user-images.githubusercontent.com/78506782/119570853-9d72af80-bd7e-11eb-9b5e-b4cfe2be53f2.png)

#### Top Ending Locations

This map shows the top ending locations in New York City

![Screen Shot 2021-05-25 at 5 30 32 PM](https://user-images.githubusercontent.com/78506782/119571076-ea568600-bd7e-11eb-9b07-d653b72c718a.png)

### Summary

Given the analysis provided in this project, we can conclude this : 

1) There is a higher activity in mornings between 6 a.m and 9 a.m, and in the evening between 4 p.m and 8 p.m. On weekends, the afternoon seem to have a higher number of trips
2) When it come to gender use, Men use bike share more than women as it is shown on the heat map for gender
3) Again, most users are male subscribers
4) The top starting locations, and top ending locations show a higher activity in downtown NYC

#### Two additional graphs to use

##### Trip duration by subsribers

The bar chart below shows that most subsribers use the bike between 5 minutes and 8 minutes

![Screen Shot 2021-05-25 at 5 52 16 PM](https://user-images.githubusercontent.com/78506782/119573215-f3952200-bd81-11eb-9e7a-384a2d465e8f.png)

#### Top 10 Stations

##### Starting
The map below shows the origin stations with more than 10000 bike share. And we can see that the location with the most start is Pershing Square North

![Screen Shot 2021-05-25 at 6 01 17 PM](https://user-images.githubusercontent.com/78506782/119574126-360b2e80-bd83-11eb-8384-23f63fd2ce24.png)

##### Ending
The map below shows the destination stations with more than 10000 bike share. And we can see that the location with the most destination is Pershing Square North

![Screen Shot 2021-05-25 at 6 09 17 PM](https://user-images.githubusercontent.com/78506782/119574990-54bdf500-bd84-11eb-99d4-fcde44a15ac3.png)


After some research , i found out that Pershing Square is very busywith restaurants and other businesses, and morst of all the Grand Central station is close by. Which explains why this station has the highest bikeshare traffic.
