# NY Citibike with Tableau
## Project Overview
The purpose of this project is to analyze and visualize the data surrounding the utilization of the NYC Citibike program in order to create similar programs in other cities such as Des Moines.

## Resources
Data Source: 201908-citibike-tripdate-noindex.csv

Software: Python 3.7.6

## Results
The complete Tableau story can be found at the following link:
[Tableau Story](https://public.tableau.com/app/profile/ee1691/viz/Bikesharing_Assignment/CitiBikesharing)

The first visualization in the story is a map of popular starting locations for Citibike rides. The image shows that most rides start in Midtown or the West Side of Manhattan, which are usually popular tourist destinations. One may make the initial assumption that a lot of Citibike users are tourists and visitors to NYC.
![This is an image](https://github.com/EricaEidelman/Bikesharing/blob/main/Popular_Start_Locations.png)

The second image is a map of popular ending locations, and the first thing to notice is that the two maps look very similar. This would imply that most riders don't use the bikes to travel very far. Tourists might be expected to have a wider range of travel than only Midtown.
![This is an image](https://github.com/EricaEidelman/Bikesharing/blob/main/Popular_End_Locations.png)

The next image shows a breakdown of rides by user type (customer or subscriber) on a daily basis. Given that subscribers significantly outnumber customers, one may conclude that most users are either New York residents or frequent visitors, and thus they have an ongoing subscription. Additionally, customers are more likely to ride on the weekends than on weekdays, which would make sense for users visiting New York or just not riding frequently.
![This is an image](https://github.com/EricaEidelman/Bikesharing/blob/main/User_Type_Usage.png)

Given that most riders can be understood to be New York residents, we can then look at the most popular riding times. These turn out to be weekdays 7-9 am (with the peak around 8 am) and then weekdays 5-6 pm, as shown in the image below. These are typically rush hour times, which would imply that most bike riders use the Citibikes as part of their daily work commute.
![This is an image](https://github.com/EricaEidelman/Bikesharing/blob/main/Popular_Times.png)

One thing to note is that popular riding times do not change much when broken down by gender. This would imply that both male and female riders are using the bikes to commute, although there is a noticeable difference between male and female ridership volumes.
![This is an image](https://github.com/EricaEidelman/Bikesharing/blob/main/Popular_Times_Gender.png)

In order to get some more evidence to test the hypothesis that the Citibike program is primarily used by commuters, we can look at the most popular trip durations. As seen in the image below, rides peak at about five minutes, after which ride durations drop significantly. Given that most rides are short duration during rush hour, this would provide further evidence that the program is used by riders to avoid rush hour traffic when commuting to and from work.
![This is an image](https://github.com/EricaEidelman/Bikesharing/blob/main/Ride_Duration.png)

Finally, we can look at trip durations broken down by gender. While both male and female riders tend to use the bikes primarily for short trips, male riders outnumber female ones by about 3 to 1. As trip durations increase, the ratio changes to about 2 to 1 but male ridership sees a much steepe decline than female ridership. This would seem to imply that there are certain (perhaps social) circumstances which keep women from using the Citibike program for commuting as frequently as men.
![This is an image](https://github.com/EricaEidelman/Bikesharing/blob/main/Ride_Duration_Gender.png)

## Summary
The analysis shows that most users of the NYC Citibike ridesharing program are likely professionals taking advantage of a way to get around rush hour traffic when commuting to and from work. Additionally, male riders significantly outnumber female riders, which means that there is an underdeveloped market of potential users for te Citibike program. Some more visualizations would be helpful in figuring out how to tap into this market. One visualization might be to create a breakdown of the ages of users between males and females to figure out which demographic to focus on for increasing rideship. Another future visualization would be to focus on the most common start and end locations specifically for female users during the popular rush hour times. By identifying where these potential users work, the program could partner with their employers to promote the Citibike as a viable commute alternative. 
