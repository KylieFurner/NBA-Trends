# NBA-Trends
A project to analyze National Basketball Association (NBA) data to look at associations between teams, win-rates, playoff appearances, and more.

In this project, I analyzed data from the NBA (National Basketball Association) and explored possible associations. 

This data was originally sourced from 538's Analysis of the [Complete History Of The NBA](http://fivethirtyeight.com/interactives/the-complete-history-of-every-nba-team-by-elo) and contains the original, unmodified data from [Basketball Reference](http://www.basketball-reference.com/) as well as several additional variables 538 added to perform their own analysis. 

You can read more about the data and how it's being used by 538 [here](https://github.com/fivethirtyeight/data/tree/master/nba-elo). For this project the data is limited to just 5 teams and 10 columns (plus one constructed column, `point_diff`, the difference between `pts` and `opp_pts`).

In 11 steps I created a variety of charts and tables to explore relationships between variables.

Summary
- I observed the differences in the average points for the Knicks and Nets during the 2010 and 2014 seasons using overlapping histograms. (Steps 1-4)
- I explored the relationship between the franchise (fran_id) and points (pts) during the 2010 season (Step 5)
- I created frequency and proportional contingency tables to explore the relationship between wins and losses (game_result) at Home and Away games(game_location). I then furthered my observations by calculating the expected array and the chi square statistic. (Steps 6-8)
- I determined the strength and direction of the relationship between the forecasted outcome (forecast) and the margin of victory (point_diff) by calculating the covariance, correlation coefficient, and pvalue. I then visualized the relationship with a scatterplot and used linear regression to create a line of best fit (Steps 9-11)




