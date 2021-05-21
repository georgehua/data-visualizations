# Movie Data Visualization


## 1. Dataset

- id:  unique ID
- imdb_id: IMDB ID
- popularity: Revelative views counts on Movie Database
- budget: USD
- revenue: USD
- original_title: 电影名称
- cast：Names of actors, seperated by |
- homepage: Moive homepage URL
- director: Names of directors, seperated by |
- tagline: tag line of the movie
- keywords：Movie keywords, seperated by |
- overview：summary of movie storyline
- runtime：length of the movie
- genres：movie genre, seperated by |
- production_companies：producers, seperated by |
- release_date：On air date
- vote_count：Number of votes
- vote_average：Average of votes
- release_year：On air year
- budget_adj：Budges adjusted by inflation rate (2010, USD)
- revenue_adj：Revenue adjusted by inflation rate (2010, USD)

## 2. Preprocessing

Notebook: 

Steps:
- Clean missing values
- Split Genre column
- Split Production companies column
- Create if "based on novel" column
- Split director column

## 3. Visualization

### 3.1. Movie Genre change by year

<img src="../docs/Movie/genre_dashboard.png">

View on Tableau Pubilc: https://public.tableau.com/profile/george.hua2456#!/vizhome/MovieGenreTrend/MovieGenreTrends?publish=yes

### 3.2. Universal Pictures vs. Paramount Pictures

<img src="../docs/Movie/producer_dashboard.png">

View on Tableau Pubilc: https://public.tableau.com/profile/george.hua2456#!/vizhome/Movieproducerscomparison/Movie_Producer_Comparison

### 3.3. Popularity of Film adaptation

<img src="../docs/Movie/adapted_dashboard.png">

View on Tableau Pubilc: https://public.tableau.com/profile/george.hua2456#!/vizhome/MovieAdaptionProfit/MovieAdaptionAnalysis

### 3.4. Who is the best director?

