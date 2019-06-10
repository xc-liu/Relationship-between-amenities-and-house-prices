# The relationship between amenities and house prices

## Background
Perth is the capital city of Western Australia, the fourth-most populous city in Australia, and some say the most isolated city in the world. It has over 200 suburbs, stretching from Two Rocks in the north to Singleton in the south, and east inland to The Lakes. 

When it comes to the house prices of these suburbs, distances to the nearest urban center, airport, and train station are without doubt having a big influence in it. Besides that, considering that different suburbs have different compositions of local venues - some have mainly restaurants and pubs, while some are enjoying more nature related venues - it would be interesting to see if and how the ratios of different venue types in the suburbs also contribute to the house prices. 

If there is any relationship, understanding it might help predict house prices, especially when the local venues change significantly, help adjust the housing market by adjusting the policies to different venues, and help find the suburbs that are of the most potential to have a growing housing market this year by looking for the suburbs with a “right” composition of local venues.

## Problem
The aim of this project is to qualitatively explore the relationship between the medium house prices of Perth suburbs, and the ratios of different venue types in these suburbs, with their distances to their nearest urban center, airport and train station also in the consideration.

## Data
The housing prices for 2018 were scraped from [reiwa.com](https://reiwa.com.au/the-wa-market/perth-suburbs-price-data/). The geological information of Perth suburbs was scraped from [Postcodes Australia](https://postcodes-australia.com) and Wikipedia. The venue information was pulled from [Foursquare API](https://foursquare.com/).

After data cleaning, there were 297 suburbs' house price and venue data left, with 281 categories of venues in total. There were 285 suburbs with information of their distances to the nearest urban center, airport and train station.

## Findings and limits
In this project, I clustered the Perth suburbs by their venue compositions, explored the differences in the house prices among different suburb clusters, including how distances to the nearest urban center, the nearest airport, the nearest train station affect the suburbs in different clusters differently, and investigated the relationships of venue category ratio and house prices for some venue categories.

The differences in house prices among different cluster clearly showed that local venue composition and affect / indicates the local house prices to a degree. This relationship between venue compositions and house prices is complicated and non-linear, with the food venues having the clearest and most obvious relationship with house prices. It’s also found that the distances to the nearest urban center, airport, and train station affect suburbs with different venue compositions slightly differently.

The limit of this study is, there were only small numbers of venues pulled for some suburbs. Thus, the relationships of the ratios of some venue categories and the house prices are not studied thoroughly. If there were more data, there might have been different conclusions drawn for these venue categories. Besides that, this project only studied the suburbs in Perth, WA, so the conclusions might not be applicable to other areas.

## More details
Raw data scraped can be found in Data/Raw/<br>
Cleaned data can be found in Data/<br>
My jupyter notebooks of data wrangling and exploratory data analysis can be found in Notebooks/<br>
Final_report.pdf is a full report of this project, and Presentation.pdf contains a short overview of it.
