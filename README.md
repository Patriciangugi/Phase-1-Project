# Phase 1 Project
## PROJECT DESCRIPTION ##

**PROJECT OVERVIEW**

In this project,the goals is to use visual data analysis to generate insights used in commercial use in the movie industry by leveraging exploratory data analysis (EDA) to uncover trends and patterns in the film sector through examining a dataset of films.

**BUSINESS PROBLEM**

Inspired by the success of major companies producing original video content, has decided to launch its own movie studio. However, with no prior experience in film production, Microsoft faces a significant challenge in understanding the dynamics of the movie industry. The goal is to explore the current film landscape, specifically focusing on what types of films are achieving the best box office results. By identifying key factors that contribute to a movie's success, Microsoft can make informed decisions about the types of films to produce, ensuring a competitive entry into the market.

**OBJECTIVES**

1. **Profitability analysis:** - Identify the most profitable and popular movie genres in the market
2. **Market Trend analysis:** Identify movies that are performing well.
3. **Creating Insights:** Translate the findings into strategic recommendations for the types of films Microsoft should create to maximize their chances of success in the competitive movie industry.


**Data Sources**
Data sources used in the analysis were:

* [IMDB](https://www.imdb.com/)
* [Box Office Mojo](https://www.boxofficemojo.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)

**Analysis Approach**

The analysis follows these steps:

**Data Understanding:** Explore the dataset, inspect the available tables, and understand the relationships between them.

**Data Cleaning and Preprocessing:** Handle missing values, remove outliers, and perform necessary data transformations.

**Feature Engineering:** Create new features from existing variables to facilitate analysis.

**Univariate Analysis:** Analyze individual variables and understand their distributions.

**Bivariate Analysis:** Explore relationships between pairs of variables using visualizations and correlation analysis.

**Multivariate Analysis:** Analyze relationships among multiple variables simultaneously.

**Insights and Recommendations:** Derive insights from the analysis and provide recommendations for Microsoft's movie production strategy.

**DATASET COLUMN DESCRIPTION**

Description is based on the columns resulted from merging two tables from the im.db.
**movie_id:** Unique identifier for each movie.

**primary_title:** The main title of the movie.

**original_title:** The original title of the movie in its native language.

**start_year:** The year the movie was released.

**runtime_minutes:** The duration of the movie in minutes.

**genres:** The categories or genres the movie belongs to (e.g., Drama, Comedy).

**averagerating:** The average rating given to the movie by viewers.

**numvotes:** The number of votes the movie has received from viewers.

**Key Findings**

Movies with shorter runtimes (around 90-120 minutes) tend to receive higher ratings and more votes.
Combining genres like action and sci-fi can captivate audiences and lead to successful movies .
Effective marketing and promotion campaigns are crucial for driving audience awareness and interest.

**Recommendations**

Based on the analysis, some key recommendations for the film sector include:

Focusing on producing films in the action, drama, and sci-fi genres or combining elements from these genres.
Maintain a balanced runtime.
Experiment with innovative genre combinations to offer unique experiences.
Invest in effective marketing and promotion campaigns.


## Conclusions 
Based on the above data analysis, the following conclusions can be drawn:
- Overall there is a strong positive correlation between the Production Budget and the Domestic and Worldwide Gross.
- Movies in the Adventure Genre Outperformed movies in other Genres.
- The Horror Genre grossed the highest amount in terms of both Domestic and Worldwide Gross. However it should be noted that the reason for this is due to the Avatar Movie, an outlier, which had significant success at the Box Office due to several reasons.
By analyzing factors such as genres, runtime, ratings, and popularity, we have identified trends and patterns that can guide Microsoft's entry into the movie production business.
The analysis revealed that genres like action, drama, and sci-fi tend to resonate well with audiences, receiving higher ratings and more votes. Additionally, movies with shorter runtimes and innovative genre combinations have the potential to captivate viewers and achieve success at the box office.
Overally, this project has provided a solid foundation for Microsoft's entry into the movie industry, equipping them with data-driven insights to make informed decisions and position themselves competitively in this dynamic and creative market.


**Clone the repository:** 

git clone https://github.com/Patriciangugi/Phase-1-Project

**License**
This project is licensed under the MIT License.
