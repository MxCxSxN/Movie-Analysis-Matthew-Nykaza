# Movie Data Analysis - Phase 1 Project - Matthew Nykaza

![Movies Picture](https://github.com/MxCxSxN/Movie-Analysis-Matthew-Nykaza/blob/master/Images/2ac566bdad689373d124ed45b5b70209.png)


## Introduction

In order to have a viable business that can last well into the future, it is imperative to diversify. For the past 4 decades Microsoft has been a major playing in the computer marketplace, later getting into a bevy of different adjacent markets. In order to remain competitive with companies like Apple, Amazon and Google (to name a few), Microsoft must become a player in the original content game. I believe that with the following recommendations that I can assist Microsoft in achieving that goal. 

## Objectives / Business Goals

Objective is to return to Microsoft a list of recommendations and conclusions that will help with their decision making on when to release movies and which genres are the most successful in terms of making money. 

### Business Problem

Microsoft has never had a major original programming, and the decision as to the way to get in is to begin a major motion picture studio. The issue is that Microsoft is not sure about any of the major details of creating movies. I have taken some datasets and feel that through my thorough review of genres, release dates, and monetary success I can help Microsoft become a successful movie maker. 

### The Data

In the folder `zippedData` are movie datasets from:

Budgets Data
This dataset includes the movie's title, release date, production budget, domestic and worldwide gross. 

The Ratings Data
The ratings dataset includes tconst (a unique movie identifier), average ratings, and number of ratings.

The Basics Data
The basics dataset includes tconst (that same identifier), the primary and original title, start year, runtime (in minutes) and genres.

These datasets were provided to me for analysis by the Flatiron School. 

## Analysis

This project uses analysis including a review of monetary succes over time and genre, as well as reviews of the seasons. This analysis provides a useful overview of a few items that Microsoft can implement to best start their movie production efforts.

## Recommendations

![Money Made/Lost](https://github.com/MxCxSxN/Movie-Analysis-Matthew-Nykaza/blob/master/Images/dsc-phase-1-project-online/moneymadevsmoneylost.png)

 
Most movies make at least some money (in comparison to their production budgets), but there are a few genres to target, and some to avoid. Animation and Adventure films make money at a 85% and 90% clip respectively. While War and Western films have tended to lose money (41% and 36% made money). 

![Worldwide Gross and Budgets](https://github.com/MxCxSxN/Movie-Analysis-Matthew-Nykaza/blob/master/Images/worldwidegrossandbudgetbyseason.png)


Movies in May, June and July and November tend to make the most money (Worldwide Gross). Production Budget is highly correlated with Worldwide gross. However, there is one slight outlier here that can be taken advantage of. Over the past 10 years the month of June has seen the highest Worldwide Gross, while only being thrid in terms of Production Budget. 

![Successes vs failures](https://github.com/MxCxSxN/Movie-Analysis-Matthew-Nykaza/blob/master/Images/commercialsuccessesvsfailuresbymonth.png)


The month of November statistically has the most successes (7.0 rating or greater and greater than $110,000,000 in Worldwide Gross) realative to failures. January seems to be a month inwhich very few movies are released, and by far the fewest are major successes. The other months that have realtively good stats on successful movies are May, June and December. 

## Conclusion

This analysis has lead to three recommendations for Microsoft's budding movie empire.

- Focus on genres that consistently make money such as Animation and Adventure movies. 
    - Given that Microsoft is already a major software company I think leveraging that business into the animation genre can relly pay dividends and nearly guarntee money made.
- Avoid releasing movies in the Autumn season. 
    - All of the five lowest grossing seasons over the past 10 years are in autumn, best to make sure to avoid any releases during this time.
- Release movies in November and December
    - Over the past ten years November and December have the most commercial successes (over a 7 average rating and greater than $110,000,000 made. By percentages Novemeber has 23% success on that metric with the next closest being June at 17% success (only a 29 movie difference in between November (144) and June (115).

## Further Work

Completing these following steps can help with ensuring Microsoft's success. 
- Comparison of genre and movie budgets to assist with seeing which movies will cost the most to produce.
- Get data on actors/actresses to see which stars are best able to move the needle for successful movies.
- Get more data for the reviews and see which movies are most likely to achieve higher ratings, and which are more likely to have poor reviews.

## For More Information
See the full analysis in the Jupyter Notebook or review this presentation 

For further information, contact Matthew Nykaza at matt . cs . nykaza @ gmail . com