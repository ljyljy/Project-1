# What factors can make a financial success? And how to recommand a movie with keyword?


1. correlation between each factors for heatmap

![fig1. correlation](Output/png/correlation_heap.png)

Conclusion: runtime and rating of the movie have no relationship with revenue


1. Time series analysis compared by revenue, voting rating and number of movie

a. Analysis most successful season in the year (Month)

![fig2](Output/png/month_vs_revernueAndRate.png)

Conclusion: In decade average of revenue is not increased with time going but total number is

b. Analysis releasing time periods, adjusted for inflation (70s, 80s, 90s) (not necessary for presentation)

![fig3](Output/png/years_vs_revernueAndRate.png)

Conclusion: Summer and winter win


2. Directors and actors

Conclusion: help the companies to choose the director and actors based on genres

![fig4](Output/png/genres_vs_revernueAndRate.png)

a. Most appearances

b. Revenue and rating

![fig5](Output/png/Actor's_revenue_in_genres.png)

![fig6](Output/png/Director's_revenue_in_genres.png)

c. genres related for famous actors and directors (done for actors and deleted stan lee)


3. Genres related

Conclusion: Top 6 is animation, adventure, fantasy, family, science fiction and action. And a gap exists then

a. Classify highest rated movies by genre


b. Average and total revenue by genres


4. vote rating related

a. compare vote rating and number of movies (normal distribution)

Conclusion: it is a normal distribution appoximately


5. Keywords related

Conclusion: help the companies to choose the keywords based on genres

a. Most-used keywords

![fig7](Output/png/keyword_wordcloud.png)

b. keywords compared with rating and profit

![fig8](Output/png/keyword_wordcloud.png)

Possible source for such data

Recommandation of keyword:

![fig8](Output/png/123.png)

TMDB 5000 dataset from kaggle