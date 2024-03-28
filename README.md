# Lights, Camera, Data: Building a Profitable Movie Studio

![image](https://cdn.discordapp.com/attachments/1220454419032702979/1222963174245138485/background_image.jpg?ex=66182036&is=6605ab36&hm=ea721a2a737e3dd215bbc3a1811a7102bcd4b3d5ce2f7abe74b778263eba9a81&)

## Project Overview
This project offers a comprehensive analysis of historical movies' financial performance, examining factors such as movie rating, genre, and budget. Additionally, it employs a simple linear regression model to forecast profit based on budgetary allocations.

The insights derived from this analysis aim to provide valuable guidance to the leadership team of S-Trio Entertainment's new movie studio, empowering them to make informed and strategic investment decisions for their upcoming projects.


## Business Understanding
With limited industry expertise and knowledge, S-Trio Entertainment has decided to create a new movie studio. To make informed and strategic investment decisions for their upcoming projects, the company's C-suite has tasked the team with delving into various movie databases for key insights.

Specifically, the leadership seeks answers to the following questions:

1. Which movie rating category - R-rated or non-R-rated - demonstrates superior financial performance?
2. Amongst different movie genres, which exhibits the highest profitability?
3. What is the correlation between production budget and profit?

## Data Understanding
For the project, following database and datasets were utilized for the analysis:

- IMDB
- Rotten Tomatoes
- The Numbers
  
Each database or dataset encompasses mostly distinct categories of movie information. For instance, the Rotten Tomatoes dataset includes movie ratings while the The Numbers dataset provides data on domestic and worldwide gross revenue. Given the variations in data structure and content across these datasets, selected tables were utilized either independently or in conjunction with others.

## Data Analysis
Our analysis shows following observations:

1. Mean box office revenue of non-R rated movies is greater than that of R-rated movies  *[Exhibit 1]*
2. The top three most profitable genres are: Adventure, Musical, and Action. Adventure movies exhibits the highest median profit, followed by Musical and Action genres  *[Exhibit 2]*
3. Team's simple linear regression model on production budget vs profit explains approx. 37.1% of the variance in profit. An increase of $1.00 in production budget is associated with an increase of $2.13 in profit.  *[Exhibit 3]*

Exhibit 1

![image](https://github.com/sangwon224/Movie_Studio_Strategy_Recommendation/blob/main/image/screenshot%201.png)

Exhibit 2

![image](https://github.com/sangwon224/Movie_Studio_Strategy_Recommendation/blob/main/image/screenshot%202.png)

Exhibit 3

![image](https://github.com/sangwon224/Movie_Studio_Strategy_Recommendation/blob/main/image/screenshot%203.png)

## Conclusion
We recommend the following to the leadership of S-Trio Entertainment:

1. Focus on non-R rated movies
2. Embrace Adventure genre
3. Approach production budget allocation strategically

## For More Information
1. Detailed Analysis:  ([Jupyter Notebook] ())
2. Presentation Slide: ([Presentation Deck] ())
3. Tableau Dashboard:  ([Tableau Dashboard] ())

## Contributors:
1. [Sam Choe](https://github.com/schoe4208)
2. [Sangwon Shim](https://github.com/sangwon224)
3. [Sarah Prusaitis](https://github.com/sarahprusaitis)

## Repository Structure
```
|— data                                                      <- Original dataset and database
    |— bom.movie_gross.csv.gz                                <- Raw data
    |— rt.movie_info.tsv.gz                                  <- Raw data
    |— rt.reviews.tsv.gz                                     <- Raw data
    |— tmdb.movies.csv.gz                                    <- Raw data
    |— tn.movie_budgets.csv.gz                               <- Raw data
|— image                                                     <- Screenshots
    |— screenshot 1.png                                      <- Screenshot
    |— screenshot 2.png                                      <- Screenshot
    |— screenshot 3.png                                      <- Screenshot
|— README.md                                                 <- Overview of the Project
|— .gitignore                                                <- List of files to exclude
|— Movie Studio Strategy Recommendation.ipynb                <- Detailed analysis in Jupyter Notebook
|_ presentation.pdf                                          <- PDF version of the project presentation slides
```


