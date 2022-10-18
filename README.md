# TMDb Movie Analysis
 I will be analysing TMDb movie data This data set contains information on movies collected from The Movie Database (TMDb), including user ratings and revenue
 
 The dataset can be downloaded [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
 
 ### Question(s) for Analysis
1. Which genres are popular over time? 
2. Which movie(s) made the most profit?
3. Which movie(s) were the longest?
4. What is the relationship between movie duration and votes?
5. How does popularity affect votes and performances?
6. How has movie(s) costing increased over the years?

### Data source Limitations
- There was no clear definitions of the columns and what they were measuring. Some column headers like now we have **revenue** and **revenue_adj** where we dont know what revenue_adj measures and what is the difference between the two columns. This is also seen on **budget** column and **budget_adj** column
- There was also no clear definitions on the SI unit for revenue which I assumed to be in dollars. Some other columns like **vote_average** and **popularity** are not clear what measurement they are measure in. Is it by percentage or on a scale?

## Conclusions
1. We can find out that **Drama**, **Comedy**, **Thriller** and **Action** were the most popular movies.
2. We also noticed that **Avatar** and **Star Wars: The Force Awakens** made highest profits of over 2Billion dollars
3. The average runtime for movies is **102 Minutes**
4. Between 1990 and 2000 the cost of producing a movie increased significantly.
