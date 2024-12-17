# IMDB-project
IMBD Movie Data Cleaning and EDA

Project background:
This project involves cleaning and analyzing IMDB data to uncover insights into movie trends, ratings, and other key metrics. By leveraging Python and libraries like Pandas, NumPy, Matplotlib, and Seaborn, I perform data preprocessing and exploratory data analysis (EDA) to understand patterns in the IMDB dataset. The data set has movies from 1960-2015.

Objective:
1. Clean and preprocess raw IMDB data for analysis.
2. Perform an exploratory data analysis (EDA) to identify trends and insights about movies, such as:
    Top-rated movies and genres
    Trends in movie releases over time
    Relationship between ratings and other movie attributes

Research Questions:
1. which genres are the most common(Number of moves made)?
2. Which genres have high average budget and revenue?
3. which genres have high average popularity?
4. Which genres have the highest number of movies with a voting average >= 8?

Hypotheses:
1. The best movies according to voting average return high profit and revenue.
2. the best movies according to popularity return high profit and revenue.
3. Highly budgeted movies return high revenue and profit.
4. Highly budgeted movies have a high popularity.

Data set:

imdb_movies.csv

Fields:

Id: [Primary Key] Key Signifier of row ID for each movie entry
imdb_id: signifier of movie within Imdb website
popularity: popularity rating of movie
budget: budget of movie
revenue: revenue of movie
original_title: full title of the movie
cast: list of main cast of movie, each cast member split by "|"
homepage: movies website
Director: director credited with directing film
tagline: tagline presented for movies "essence" to draw in audience
keywords: words used to describe themes of the film, each keyword seperated by "|"
overview: short summary of film
runtime: length of film in minutes
genre: types of genre used to describe the film, each genre seperated by "|"
production companies: main companies credited to the production of the film, each company seperated by "|"
release date: date of films release
vote count: number of votes that rated the film on IMDB
vote average: average vote rating based on a scale 1-10
release year: year the film was released
budget_adj: films budget adjusted for inflation
revenue_adj: films budget adjusted for inflation

Key Findings: 
1. Drama films are the most created films, making up 17.9% of all movies within the dataset
2. Adventure films produce the highest profit out of any genre
3. there is a moderate correlation between movie popularity and profit, as well as budget and popularity
5. Adventure films are the most popular genre
6. Around the start of the 2000s action, family, science fiction, and adventure appear to be the best highest profiting genres of movies

Insights: 
1. High budgets tend to lead to higher popularity and profits
     - this could be why we see fewer mid budget studio movies
     - could also be related to the lower volume of movie released after the data set ends in 2015
2. 
