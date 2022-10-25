### 2016-2022 US traffic accidents
This is a project I worked on with two other people, one of whom had to leave the project early. We were exploring a dataset about accident setting and effect on traffic flow. We split up the analysis in groups, one covering weather and the other on time. We analyzed 2.8 million out of 6.8 million accidents that occur in a year in the contiguous United States. Information we could have use if added to the data included population for state presence in accidents and number of drivers on the road to be able to say that more people on the road equals more accidents.


The amount of accidents. Severity is a scale from 1 to 5 of the effect each accident had on flow of traffic.
We looked at Severity 2 cases to work with loading the file in graphs.

![image](https://user-images.githubusercontent.com/66132013/197661073-1031915b-413a-4e8c-ab9a-bf275e16c64a.png)


The number and percent of accidents that happen at night versus by day.
![image](https://user-images.githubusercontent.com/66132013/197661372-3782fab9-35a9-475f-a520-d264e67c6b2f.png)
I heard that driving at night is more dangerous, so I wanted to know if there were more Severity 4 cases. The percentages of each level for day were nearly the same as for night.


Times of accidents with clustering around two areas.
![image](https://user-images.githubusercontent.com/66132013/197661707-fc73d7a3-e702-48a0-b646-4b01cce347d1.png)


Duration of the hold up in traffic
![image](https://user-images.githubusercontent.com/66132013/197661776-3a5a1d22-8587-4018-96d4-d08be72da308.png)


Weekly cycle of accidents.
![more accidents on weekdays](https://user-images.githubusercontent.com/66132013/197661860-d98fbf81-8b0d-4d5a-8b48-58fbe5e6d794.png)


A picutre of correlations of weather. I realize that weather requires more custom-made groups for adverse weather conditions.
![image](https://user-images.githubusercontent.com/66132013/197662594-8efc4b88-018f-45f0-91cc-1baaf9f4cbac.png)


Temperature lows and highs could correlate with more accidents. Above a certain amount of wind speed could make driving more difficult, only in places residents are not already warmed up to that flavor of driving. A Canadian and a Floridian could have different gauges on wind speed. Weather condition, a field we omitted was in string format so would not appear on a Pearson correlation. Furthermore, Westher_Condition had 121 or so nunique counts or phrases that could make grouping under a code laborious in light of possible payoff.
![image](https://user-images.githubusercontent.com/66132013/197663106-ba6339e2-d597-4653-9b57-57363e81510c.png)


Accidents counted by state. I had failed pivoting columns in a dataframe without column names into one that could be merged on state name abbreviation to get percent of accidents to number of people living in each state. That number for each state would still require disclaimer on number of drivers in each state out of the population. As it is, location wraps up a summary of this dataset's accidents of the United States contiguous in recent years.
![image](https://user-images.githubusercontent.com/66132013/197663261-99eff495-6871-4cf5-b492-fa0dd0369127.png)


The site with the data dictionary from the datset's creator, Sobhan Moosavi.
https://smoosavi.org/datasets/us_accidents
