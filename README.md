## phase_1

 ### BUSINESS UNDERSTANDING

#### INTRODUCTION

Movie production involves the process of film creation. Movies can be produced into different categories simply referred to as movie genres. Genres include action, adventure, drama, musical, horror, fantasy, comedy, mystery, kids and family, suspense and romance among many others. A specific movie may belong to more than one genre depending on its content.

Movie success can be attribute to a number of factors mainly the rating it receives from members of the public, its popularity, viewership across different medias and the income it generates to its stakeholders. Some of this data can be found from online movie databases which include Box office Mojo, Internet Movie Database (IMDB), Rotten Tomatoes, The Movie Database and The Numbers

This project is design to get insight from this data source to advice Microsoft on the best strategy in investing in movie production

#### OBJECTIVE

Explore the kind of movie currently doing well in the market and advise Microsoft on the best kind of movie to produce
### DATA UNDERSTANDING

in this project we have five data sources.

Box office Mojo (BOM)

Internet Movie Database (IMDB)

Rotten Tomatoes

The Movie Database (TMDB)

The Numbers

Among this three sources data proved to be more relevant in this project.TMDB data contains the genre,popularity and rating of the movie.All this are insists that would lead as to proper insists on the kind of movie to produce.

The IMDB data proved useful as it had a very large dataset for analysis.It also contains data on movie rating and time which also are of interest in this project.

Data from BOM has important data on movie returns.Although it has no genre or any other data for comparison if combine with another data it would prove very useful.

The other two datasets appered to contain data less important to this project either from their size or their content.

### DATA PREPARATION

In this project different data will be analysed differently.Data preparation is to be done before each analysis. data preparation will inlude merging of data from different sources,dealing with missing values etc

### DATA ANALYSIS

**Analysisng Data from The Movie Database (TMDB)**

This data contains information on movie genre,movie popularity and movie rating. we are trying to see the which genre of movie has more popularity and which has better ratings in the market

**Analysis of The Internet Movie Database(IMDB)**

This data contains different tables that cointain different information on movies.In this analysis will be using just 2 tables .One contains the information about movie names and genres while the othe cointains information on movie rating.They can be joined by a common column which also happens to be the index of both tables.

**Analysis of Box Office Mojo data(BOM)**

This data contains revenue data from movies.Unfortunately the data has no genre for comparisson it is for this reason that it is merged with our later IMDB data .By changing the title column to match that of BOM data. IMDB data looks a better partner because it has a wider data range and more movies on BOM data may find their way to it.

#### CONCLUSION

At the end i was able to get several import insites that can be used for movie production recommidations

1.Movie genre average earning - this was found from a combination of IMDB data and BOM data.Science fictition had the best return followed by adventure as shown by the graph above.

2.movie genre avarage rating - this was found from IMDB and TMDB data.For our recomedations we are going to use the IMDB data as it had a wider data range therefore more likely to have a better accuracy.

3.Popularity per genre - TMDB data contained movie popularity which is also a very important instinct for remmondetions.

4.Runtime vs rating - This showed a positive correration of about 0.63294 which shows the market prefered longer movies.

#### RECOMMENDATIONS

1.Microsoft new studio should give a priority to the following genres adventure,action,animation,fantasy and sci-fiction.this genres should a very high return when also showing a wide popularity and average to good public rating

2.Microsoft new studio should avoid Horror movies as they showed poor return,poor ratings and small popurality

3.Microsoft new studio should consider longer movies as there is a positive correration between the runtime and movie rating(0.63294).

