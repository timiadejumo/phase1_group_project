# MICROSOFT FILM STUDIOS: Analytical Suggestions for Film Development

## Overview:

Our team generated insights through data analysis for the creation of a movie studio

## Business Problem:

Our client, Microsoft has just decide to go into orioginal movie content creation. They intend owning a studio. The company needs information to reach a decision on what type of movies to create based on movies currently topping at the box office.

## Data Understanding and Analysis:

### Source of Data:

This project analyzes data from IMDB, TheMovieDB, and The Numbers to create actionable insights for film development. We combined values from different CSV and SQL databases to create a master data set for analysis. We then used Pandas libraries and Python to organize, clean, combine, and analyze the data. The data was then graphed using MatPlotLib and Seaborn to create visualizations. 

The data suggests that Sci-Fi, Fantasy, Action, and Adventure movies are the most popular. The popularity metric is an IMDB proprietary metric that takes into account several factors including: Release Date, “Watchlist” hits per day, Total votes, Votes per day, “Favorite” marks per day, and the Previous day’s score.

The data also tells us that these categories perform the best generally. Their domestic and international gross revenue (averages) are the highest of any genre. In addition, the film studio must pay attention to the International market as over half the average revenue comes from these markets


### Tools:

To analyze the dataset we had, we made use of the following language and libraries:
1. Python 3.9.10
2. Pandas 1.3.5
3. Numpy 1.22
4. Seaborn 0.11.2
5. Sqlite3 3.37.2
6. Shutil 3.10.2
7. Regular Expressions (RE) 3.10.2
8. Matplotlib 3.5.1



![pop_score_genre.png](attachment:pop_score_genre.png)

![gross_rev_genre.png](attachment:gross_rev_genre.png)

![rev_budget_regression.png](attachment:rev_budget_regression.png)
