# IMDB_250_ANALYSIS

## Goal 
  The goal is to uncover insights of top 250 rated IMDB movies by providing descriptive analysis using only SQL and recommending few inferences on what makes it to top 250.

## About 
  `Data:` The titles has been scraped from the imdb website [Link](https://www.imdb.com/chart/top/) and using the OMDB api [link](https://www.omdbapi.com) on the required titles the necessary data was pulled.

## Workflow

## Summary and recommendations
### Insights 
#### 1. Summary
The data consists of
-  total 224 movies.
-  565 actors.
-  159 directors.
-  36 different genres.
-  65 languages.
-  38 country releases.
-  with average runtime being 152.10 minutes.
-  and average box office collection is  25102172.69$.

### Geographic distribution of movies
United States, United Kingdom, France, Germany, Japan are top producers with US and UK having 86% share.
### Genre
- Genre distribution

    Drama being the most popular followed by Adventure, Action, Crime, Comedy.
- Top combination of Genres.

    The following list explains the most occured combinations of genres in the imdb top 250 movies.
   1. (Drama)
   2. (Drama,Crime)
   3. (Comedy,Animation,Adventure)
   4. (War,Drama)
   5. (Mystery,Drama,Crime)

### Directors
- Most directed 
    
    The following are the list of directors who directed most top imdb 250 listed movies.
    1. Steven Spielberg
    2. Christopher Nolan
    3. Stanley Kubrick
    4. Martin Scorsese
    5. Alfred Hitchcock
- Top 5 directors who have ventured into most genres.
    1. Alfred Hitchcock
    2. Steven Spielberg
    3. Quentin Tarantino
    4. Billy Wilder
 - Directors who were consistent in their genres.
    1. Lee Unkrich
    2. Satyajit Ray
    3. Christopher Nolan
    4. KenzÃ´ Kubokawa
    5. Pete Docter
    6. James Cameron
 
 **Lee Unkrich** is the `only` director who topped the list with 4 movies with least number of genres (3 genres).
 
 ### Seasonality 
 
1. Year
    - 1994 and 2010 produced most number of movies 
2.  Month
    - most number of movies were released in the end of the year (Nov, Dec)
    - Least number of movies were released during the mid-year with APRIL being the least of all.

### Actors

1. Actors with most screen presence
    1.  Robert De Niro
    2.  Tom Hanks
    3.  Charles Chaplin
    4.  Leonardo DiCaprio
2. Actor with strong screen presence over the years irrespective of age
    1. Charles Chaplin
    2. Tom Hanks
    3. Robert De Niro
    4. Leonardo DiCaprio

### Languages

1.  There are 23 non-english movies that actually topped the list of imdb 250.
2.  Non-English languages ordered by their average box office potential.
    1. Arabic 
    2. Sindarin 
    3. Mandarin
    4. Latin
    5. Portuguese
