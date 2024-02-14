![Headerimage](./Charts%20%26%20Images/cinema-4153289_1280.webp)

# Phase 1 Project - Microsoft's Cinematic Exploration: A Box Office Analysis

**Author:** [Rhoda Musyoki](rhoda.musyoki@student.moringaschool.com)


## Overview

Microsoft is venturing into the world of movie production and aims to establish a successful movie studio. This data analysis project is done to gain some insights on the industry and involves analyzing data on box office performance, including factors such as genre, production budget, ROI, release day/ month and viewer ratings. Various data analysis methods were employed to uncover insights from the data. The results reveal trends and patterns in successful movies which allows Microsoft to make data-driven decisions on the types of movies to produce. Recommendations are provided to guide the studio in creating content that is likely to be well-received by audiences and financially successful in the competitive film industry. 

## Business Problem

Microsoft has decided to venture into the movie production industry with the establishment of a new movie studio. Microsoft however lacks prior experience in this field and needs to make informed decisions about the types of films to create in order to achieve success at the box office.

*** Questions to consider:***
1. What genre yields the highest return on investment (ROI) in the context of box office performance?
2. What is the best day and month for movie release to maximize box office revenue and audience reception?
3. Is there a statistically significant correlation between production budget and worldwide gross revenue for movies?

## Data 

The data sources for this analysis include IMDb's title and ratings data, Box Office Mojo's movie gross data, and The Numbers' movie budgets data.

***
Datasets Used:

1. imdb.title.basics: This dataset contains information about movie titles, including genres, release year and runtime. It  will be used to understand the genres and general characteristics of the movies in the analysis

2. imdb.title.ratings: This dataset provides movie ratings for an assessment of audience reception. These ratings help in evaluating the success of movies

3. bom.movie_gross: This dataset includes information on the domestic and foreign box office gross revenue for movies

4. tn.movie_budgets: This dataset provides data on the production budgets and worldwide gross revenue of movies for the 
   analysis of the relationship between budgets and revenue ***
   
   
## Methods

This project uses descriptive statistics to understand box office trends such as correlation to identify predictive factors for a movie's success


## Conclusions

Based on the insights from the analysis, the following recommendations are made:

1. To maximize return on investment (ROI), focus on producing movies in the 'Horror, Mystery, Thriller' genre.

![GenrevsROI](./Charts%20%26%20Images/genreroi.png)

2. November & December are preferable for boosting popularity while May, June & July (summer time) are the ideal months for high ROI movie releases.

![MonthvsRating](./Charts%20%26%20Images/monthrating.png)

![MonthRevenue](./Charts%20%26%20Images/monthrevenue.png)

3. The positive correlation between the production budget and worldwide gross for the top 100 movies suggests that higher budgets tend to result in higher revenues. Further analysis can however be made to ascertain the extent of this correlation

![BudgetRevenue](./Charts%20%26%20Images/budgetrevenue.png)


## What Next?

In order enhance the quality of the recommendations herein, I suggest exploring additional data sources and conducting further analysis in various other areas including but not limited to:

1. Streaming and Home Entertainment Revenue: With the growing importance of streaming platforms such as Netflix, including data on revenue from digital and streaming services, can provide a more comprehensive picture of a film's overall financial performance.]

2. Marketing and Promotion: Examining data related to marketing and promotional strategies employed by successful movies can help Microsoft understand how to effectively market their films

3. Impact of Cast on Movie Performance. This analysis can help identify talent with a strong track record of contributing to successful films 


## For More Information

See the full analysis in the [Project Jupyter Notebook](./DSC-PHASE1-PROJECT.ipynb) or review this [Project Presentation](./DSC-Phase1-Project-Presentation.pdf)


## Repository Structure

```
├── Charts & Images
├── Data
├── DSC-PHASE1-PROJECT.ipynb
├── DDSC-Phase1-Project-Presentation.pdf
└── README.md
```
