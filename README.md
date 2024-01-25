# Python-TMDB-Movie-Recommendation
> This project is inpired by [Kaggle](https://www.kaggle.com/datasets/sankha1998/tmdb-top-10000-popular-movies-dataset/data). Please visit the link for further information.

> Please consider visiting these works by [Chiticariu Cristian](https://www.kaggle.com/code/chiticariucristian/quick-text-based-system-recommendation-movies) and [Saishiyam](https://www.kaggle.com/code/saishiyam/movie-recommendation-system). They are amazing.

## Scenario
TMDB.org is a crowd-sourced movie information database used by many film-related consoles, sites and apps, such as XBMC, MythTV and Plex. Dozens of media managers, mobile apps and social sites make use of its API.
TMDb lists some 80,000 films at time of writing, which is considerably fewer than IMDb. While not as complete as IMDb, it holds extensive information for most popular/Hollywood films.
This is dataset of the 10,000 most popular movies across the world has been fetched through the read API.
TMDB's free API provides for developers and their team to programmatically fetch and use TMDb's data.
Their API is to use as long as you attribute TMDb as the source of the data and/or images. Also, they update their API from time to time.

This data set is fetched using exception handling process so the data set contains some null values as there are missing fields in the tmdb database.

P.S: In the overview section, there are 30 missing data. In this Analysis, we will remove those data. 

## implementation
* `Import libraries`: pandas, numpy, matplotlib.pyplot, seaborn 
* `Check the missing values`: Investigate the data. 
* `Drop the missing rows`: There are 30 data in overview column.
* `Check the missing values again`: Investigate the missing values after dropping 30 data.
* `Recommendation`: Vectorize the overview column.
![VSCodium_OR15Ja2Y9B](https://github.com/Kwangsa19/Python-TMDB-Movie-Recommendation/assets/135963482/52ea5363-a6e4-4b67-9513-6530de92013b)

 Several movies are similar to `The Dark Knight`(The value is 1 for the given movie): 

![VSCodium_c4QDGNlC7I](https://github.com/Kwangsa19/Python-TMDB-Movie-Recommendation/assets/135963482/a93ed45e-60ad-468f-a8b7-15f5dee4225e)

## Future Works
* For analysis, pleave visit this [link](https://github.com/Kwangsa19/Python-TMDB). 
