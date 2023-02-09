# Phase 1 Project Carolyne Kambura

I have made it all the way through the first phase of this course (First Project) - taking a minute to celebrate my awesomeness!

![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project/master/awesome.gif)

## Project Overview

This project analyzes the movie industry from 2010 to 2018. The descriptive analytics provides insights on genres that are highly rated, have high production budgets and grossing. The projects also helps explore the relationships between different features including production budget and runtime, production budget and grossing, and domestic and foreign grossing. Microsoft can use the information to make data driven decision on the content that they should focus on.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

 Questions asked during the analytics:

  1. What were the movie trends from 2010 - 2018 (i.e. how many movies per genre were produce each year)?
  2. Which were the highest rated genres?
  3. Which genres had the highest production budget?
  4. Was there a correlation betwee production budget and runtime?
  5. Was there a correlation between production budget and World wide gross profit?
  6. Which genre had the highest Estimated gross profit?
  7. Was there a correlation between domestic gross profit and foreign gross profit?
 
 From the analysis, the results will help Microsoft understand:

  1. Which genres to focus on in terms of averageratings and estimated gross profit
  2. Production budgets for each genres
  3. How production budget translates to gross profit
  4. The correlation between how a movie performs domestically and internationally

### Data Sources

The datasets applied in this project were sourced from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)


### Methods
Steps followed:

Importing relevant packages used Pandas, Numpy, Matplotlib, Seaborn and Scipy

### Data Preparation
  1. Data Extraction :
  
The below datasets were extracted for this analysis:
   - tn.movie_budgets.csv.gz 
   - bom.movie_gross.csv.gz 
   - imdb.title.basics.csv.gz 
   - imdb.title.akas.csv.gz 
   - rt.movie_info.tsv.gz
   
  2. Data cleaning
  
 To ensure that data was clean for analysis, the following was done
 
  - Removed duplicates
  - Used built-in methods to identify and deal with missing values (NaN) 
  - Removed irrelevant columns and rows

 3. Data Wrangling
 
 For easy data analysis and visualization the following was done to form one dataframe especially for the imdb datasets
  - Combining Data
  - Indexing Data
  - Dealing with Categorical Data
  
  4. Data Analysis
This project used descriptive analytics including changes in trends over time & comparitive analysis between film features. This provides meanigul insight in movie industry trends that could help the Microsoft team make well informed decision in their new potencial venture in the film industry.
 
### Results

Qn1: What are the movie trends from 2010 to 2018?
There has been a reduction in the number of movies produced from 2015 to 2018

![image](https://user-images.githubusercontent.com/119498882/217743292-c47d050b-4fa9-49c8-aa6a-d90f3c01dd5f.png)

Qn2: Which top 10 single-genre had the highest averagerating?
The top 10 single-genre films had mostly an averagerating of 6.5 - 7.3, with the highest being Short films with a rating of 8.8 and the lowest being Animation with a rating of 6.5

![image](https://user-images.githubusercontent.com/119498882/217744104-e1827757-4fc3-4ade-a81e-09ec5ed5dacb.png)

Qn3: Which top 10 single-genre had the highest averagerating?
The below results shows that films with multi-genre have higher averagerating compared to single-genre films with the highest being Comedy,Documentary,Fantasy with a rating of 9.4, and the lowest being Drama,Fantasy,War with a rating of 8.8

![image](https://user-images.githubusercontent.com/119498882/217744783-e5647aaf-aebf-4651-98ab-9c5b4d3093a4.png)

Qn3: Which genres had the highest production budget?
Action|Adventure|Classic|Drama genre films had the highest production budget of $425,000,000 with Drama|Romance, Drama|Kids and Family and Comedy having the same production budget of $300,000,000

![image](https://user-images.githubusercontent.com/119498882/217745947-39766a6c-f9a6-4d1b-955b-42c11ffa2b5c.png)

Qn4: Does runtime affect production budget?
Hight production budget does not really equal runtime of the film and vice versa

![image](https://user-images.githubusercontent.com/119498882/217747351-fd351817-d402-4b01-9468-b49b84a983cf.png)

Qn5: How does production budget correlate with Gross profit
There's a strong correlation between production budget and Gross profit i.e. if you use more you're guaranteed higher grossing

![image](https://user-images.githubusercontent.com/119498882/217747688-c93409bc-b6ec-4702-ab24-ed87c069279c.png)
Action and Adventure|Classics|Drama had the highest estimated gross profit of $ 235,1345,000
Qn6: Which are the top most profitable genres?

![image](https://user-images.githubusercontent.com/119498882/217748059-7ccab7e9-97a8-45cc-ac54-45ddbc0e0983.png)

Qn7: What's the relationship between Domestic gross and Foreign gross?
The results show a strong linear relationship between domestic and foreign gross. i.e. a movie that performs well locally will perform well internationally.

![image](https://user-images.githubusercontent.com/119498882/217748678-769aaae0-fbc2-4679-8e1c-dce998afbc94.png)

### Conclusion

Key takeaways:

1. Multi-genre films perform well than single-genre films
2. Action and Adventure|Classics|Drama had the highest production budget and estimated gross profit
3. There's no relationship between runtime for a movie and production budget and vice versa
4. Films that perform well domestically will perform well internationally
5. There's a positive correlation between production budget and gross profits

### Recommendation

1. Microsoft should target to produce more multi-genre films with a key focus on Action and Adventure|Classics|Drama

### Further Work
1. Compare studio productions and identify those that have successfully done low-budget films with high grossing
2. Analyze how many movies Microsoft should produce per year
3. Analyze the best time of the year (month) to release different film genres

