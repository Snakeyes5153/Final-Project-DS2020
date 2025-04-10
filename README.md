
# Analysis of Video Game Sales

### Jacob Bartlett

## Introduction

Video Games are a popular form of entertainment enjoyed by billions of
people worldwide. The games produced range a wide variety of genres and
are available to a variety of ages where there’s a game for anyone to
enjoy. The goal of this analysis is to explore a dataset of video game
sales to better understand the consumer market for video games.

In pursuit of the stated goal, I will explore the following questions:

1.  Which genres tend to sell more units? Which genres are popular in
    different regions of the world?

2.  How is the ESRB rating related to the number of sales? Does the
    rating affect the amount of sales?

3.  How is the critic rating related to the number of sales? How does
    the user rating relate?

4.  How does the amount of global sales change over the years? Is this
    affected by the release of new gaming systems/platforms?

These are the main questions I am looking to answer through the
completion of this project. With the findings I’ll be able to draw
meaningful conclusions on the consumer market of video games throughout
the world.

## Data

### Structure

The link to the data set is
[here](https://www.kaggle.com/datasets/sidtwr/videogames-sales-dataset/data?select=Video_Games_Sales_as_at_22_Dec_2016.csv).
The website contains a csv file of video game sales up until late 2016
with over 16,000 games in the dataset. The number of variables in the
dataset is 16. According to the website, the Metacritic scores come from
a web scrape of their website. Since Metacritic only reviews games on
certain platforms, over half of the games in the dataset are missing
values for the critic and user ratings as well as the developer and ESRB
rating.

### Cleaning

### Variables

- Name: The title of the video game.
- Platform: The gaming platform that the game was released.
- Year_of_Release: The year the video game was released.
- Genre: The main genre of the video game.
- Publisher: The name of the company or corporation that released the
  game.
- NA_Sales: The total number of physical units sold in millions for
  North America.
- EU_Sales: The total number of physical units sold in millions for
  Europe.
- JP_Sales: The total number of physical units sold in millions for
  Japan.
- Other_Sales: The total number of physical units sold in millions for
  the rest of the world.
- Global_Sales: The total number of physical units sold in millions.
- Critic_Score: Aggregate score compiled by Metacritic staff.
- Critic_Count: The number of critics used in coming up with the
  Critic_score.
- User_Score: Score by Metacritic’s subscribers.
- User_Count: Number of users who gave the user_score.
- Developer: Party responsible for creating the game.
- Rating: The ESRB rating.

## Results

``` r
library(tidyverse)
game_sales <- read_csv('Video_Game_Sales.csv')
```

#### Which genres tend to sell more units? Which genres are popular in different regions of the world?

#### How is the ESRB rating related to the number of sales? Does the rating affect the amount of sales?

#### How is the critic rating related to the number of sales? How does the user rating relate?

#### How does the amount of global sales change over the years? Is this affected by the release of new gaming systems/platforms?

## Conclusion
