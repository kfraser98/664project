## Title: 
Film Genre Tracking

## Description: 
This project is meant for tracking the popularity of film genres across the past decade. Popular genres are tracked through various data points including: highest grossing in the U.S. box office, highest audience ratings, and award ceremony nominations. The project looks at the time period from 2015/16-2025/26 to see how certain genres perform over the years, ultimately tracking the percent of change for each genre.


## Rationale:
Movies are often reflective of society, so when certain genres become popular, it can be indicative of cultural attitudes during a specific time period. For example, during World War 1, propaganda films, including spy movies, became really popular to boost American citizens’ morale and support for the military. This project aims to see if there is a correlation between what is going on in American society today and what genres have become more popular across the past decade.

## Workflow:
* Extract top 10 highest rated films with genre IDs from 2015-2026 using the TMDb API and export it as a CSV, use search and replace in Excel to convert genre ID numbers into words.
* Extract top 10 highest grossing films from 2015-2026 using the unofficial BoxOffice Mojo API and export it as a CSV file.
* Create a file of Academy Award nominees and winners from 2016-2026 from major categories (including but not limited to Best Picture, Best Actor/Actress, Best Screenplay - Original/Adapted) and convert to CSV.
* Download Golden Globes dataset from Kaggle and extract nominees and winners in major categories (including but not limited to Best Picture - Drama/Comedy, Best Actor/Actress, Best Screenplay) from the years 2016-2020, supplement 2021-2026 data from the Golden Globes website in Excel and convert to CSV.
* Source genres for all films from AA, GG, and BoxOffice Mojo from the IMDb website.
* Clean the data into a usable dataset using a mixture of Open Refine and Excel.
* Analyze and visualize all datasets using Pandas and MatPlotLib libraries to search for genre trends.

## Further Uses:

## Files List:
* TMDb API data
* TMDb python notebook
* Unofficial BoxOffice Mojo API
* BoxOffice python notebook
* Academy Awards file
* Golden Globes file
* TMDB visualizations python code
* BoxOffice visualizations python code
* Academy Awards visualizations python code
* Golden Globes visualizations python code

