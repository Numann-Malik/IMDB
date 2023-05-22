# IMDB Movie Analysis
 
Main Objective: We produced a MySQL database on Movies from a subset of IMDB's publicly available dataset. We used this database to analyze what makes a movie successful, and provide recommendations on how to make a successful movie.

## Key Steps

- Downloaded several files from IMDB’s movie dataset and filtered out a requested subset of movies.
- Used an API to extract box office revenue and profit data to add to our IMDB data and perform exploratory data analysis.
- Constructed and exported a MySQL database using our data.
- Applied hypothesis testing to explore what makes a movie successful (after cleaning data appropriately).
- Produced a Linear Regression model to predict movie performance.

Data Sources:

https://www.imdb.com/interfaces/

https://datasets.imdbws.com/

Data Dictionary:

https://developer.imdb.com/non-commercial-datasets/

## Statistical Analysis

### Does the MPAA rating (G/PG/PG-13/R) affect how much revenue a movie generates?

Null Hypothesis: There is no significant statistical difference between the revenue generated by movies with different MPAA ratings.

Alternate Hypothesis: There is a significant statistical difference between the revenue generated by movies with different MPAA ratings.
