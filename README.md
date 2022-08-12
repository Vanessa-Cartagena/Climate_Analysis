# Surfs_Up
Climate analysis module that introduced new tools such as SQLite, SQLAlchemy, and Flask to expand your knowledge of SQL database structures and querying methods. Executed Python code in a Jupyter notebook and created graphs using Python. 

## Overview 
In order to provide data that will convince an investor that opening up a surf shop, Surf n' Shake, in Oahu, Hawaii is a smart business move, we examined a weather-related dataset that has been stored in a SQLite database. The shop is to sell surfboards and ice cream to locals and tourists. The investor M. Avy, who is well-known for his love of surfing, was cautious despite the venture's seeming potential because he once invested in a surf shop without asking about the weather, and the business failed as a result of a lot of rain. We presented a statistical analysis that focused exclusively on the weather in Oahu to persuade this investor that this will be a profitable business venture. W. Avy requested more information about temperature trends before opening the shop following our analysis. He specifically requests Oahu temperature information for the months of June and December to assess if the surf and ice cream store industry can survive year-round. 

## Results 
These results are based on our initial examination of precipitation data from 8/23/2016 to 8/23/17. The largest amount of rainfall, 6.7 inches, occurred in September, with the average amount of precipitation being 18%. This indicates that there is no rain for the majority of the year.

<img width="141" alt="YearPrecipStats png " src="https://user-images.githubusercontent.com/105958160/184363863-b26f95c8-9bd1-4afd-a7d9-29b74e7557e7.png">
<img width="444" alt="YearPrecipBarGraph" src="https://user-images.githubusercontent.com/105958160/184363875-e04deef2-5613-46dd-aa56-5f615c8efa41.png">

Then, using data from the same time period, we examined the temperature information obtained from the busiest weather station, USC00519281. The average temperature was 72°F, with the lowest temperature being 54°F and the highest being 85°F. This graph depicts pleasant temperatures for ice cream and surfing throughout the year!
<img width="433" alt="YearTempHistogram" src="https://user-images.githubusercontent.com/105958160/184371011-df66abd4-90c3-4a7f-a63b-7b0782622c2b.png">

W. Avy asked that we examine the temperature information for the months of December and June. The findings indicate that the temperatures for the two months are quite similar, with December's slightly lower temperatures.

<img width="142" alt="JuneTempStats" src="https://user-images.githubusercontent.com/105958160/184379827-d5994a5a-b042-4786-bf08-b214352a6e16.png">
<img width="165" alt="DecTempStats" src="https://user-images.githubusercontent.com/105958160/184379895-87cf78d4-bce9-4e37-8093-92b79d99c676.png">

## Summary 
In addition to W. Avy's request, we looked at the precipitation data for June and December. June and December saw average precipitation of 14% and 22%, respectively. 

<img width="168" alt="JunePrecipStats" src="https://user-images.githubusercontent.com/105958160/184382472-97a03d1b-b8ff-44bd-b274-3127f7d45438.png">
<img width="141" alt="DecPrecipStats" src="https://user-images.githubusercontent.com/105958160/184382501-7ebe2aa4-5805-4749-a24e-9d8d06532fcd.png">

According to our weather analysis, participating in this venture would be a good decision and won't end like W. Avy's previous surf shop endeavor.
