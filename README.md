# TMDb-movie-data-analysis
### I wrangled and analynized the TMDb data to investigate two reseach questions:

##### 1.What are the top 3 popular genres in the past 5 years?
##### 2.What kinds of properties are associated with movies that have high revenues?

### Belows are explanations of wrangling and Analysis parts:

##### Wrangling:
1. drop useless columns
2. remove rows with missing values
3. remove the data have 0 value in budget or revenue (because it doesn't make sense in real world)

##### Analysis:

### 1.What are the top 3 popular genres in the past 5 years?

Top 1 is 'Science Fiction' got 3.652345 avaerage popularity per film.

Top 2 is 'Adventure' got 3.324471 avaerage popularity per film.

Top 3 is 'Western' got 2.721777 avaerage popularity per film.**

But, Popularity growth rate Ranking: 'Western' > 'Science Fiction' > "'Adventure'"

- Average YoY growth rate by popularity of 'Adventure' is 33.8% (2010-2015)

- Average YoY growth rate by popularity of 'Science Fiction' is 62.9% (2010-2015)

- Average YoY growth rate by popularity of 'Western' is 113.4% (2010-2015)

### 2.What kinds of properties are associated with movies that have high revenues?

high revenues is in positive correlation with "release_year", "vote_average", "vote_count", "budget", 'popularity','genres', 'director', 'production_companies' and 'cast'

- About detailed relation between revenue and genres:

The top 1 genre, Animation, are 3 times bigger as forteenth place genre, Crime.

- About detailed relation between revenue and directors:

the directors had filmed more movies are related to the high revenue per movie. The average revenue of a film made by directors who had filmed at least 7 films is 3 times as much as directors who had filmed under 2 films

- About detailed relation between revenue and production companies:

Marvel Studios had earned most revenue, and it's twice as much as Eon production.

Top 10 ranking by revenue: 'Marvel Studios' > 'Lucasfilm' > 'DreamWorks Animation' > 'Eon Productions' > 'Walt Disney Animation Studios' > 'Jersey Films' > 'DNA Films' > 'DreamWorks' > 'Davis-Films' > 'Geffen Pictures'

Films were produced by muti companies usually made more one third revenue than films made by single company.**

- About detailed relation between revenue and casts:

the revenue of cast, Daisy Ridley's movie is almost 2 times as much as the average of the rest casts' on the top 10 list.
