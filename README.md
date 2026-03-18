# Movie Dataset Analysis 📽️🎬

An exploratory data analysis of 58,788 IMDb movies using the `ggplot2movies` 
dataset in R. The project cleans, visualizes, and models the data to uncover 
what makes a movie highly rated.

## Key Findings
- Genre is the strongest predictor of rating — Animation rates highest, Action lowest
- Budget has virtually no effect on rating (correlation = 0.02)
- Older movies tend to rate higher due to survivorship bias

## Analysis Covers
- Rating distribution across 46,939 cleaned entries
- Average rating and movie count by genre
- IMDb rating trends over time (1920–2005)
- Budget vs rating relationship
- Linear regression model for predicting ratings

## Tools & Libraries
- R
- ggplot2, dplyr, tidyr, broom
- ggplot2movies dataset

## How to Run
1. Open `movie_analysis.Rmd` in RStudio
2. Install dependencies: `install.packages(c("ggplot2movies", "ggplot2", "dplyr", "tidyr", "broom"))`
3. Click **Knit** to generate the HTML report
