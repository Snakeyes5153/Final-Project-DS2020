
# Analysis of Video Game Sales

### Jacob Bartlett

## Introduction

## Data

### Structure

### Variables

- Name: The title of the video game.
- Platform: The gaming platform that the game was released.
- Year_of_Release: The year the video game was released.
- Genre: The main genre of the video game.
- Publisher: The name of the company or corporation that released the
  game.
- NA_Sales: The total number of units sold in millions for North
  America.
- EU_Sales: The total number of units sold in millions for Europe.
- JP_Sales: The total number of units sold in millions for Japan.
- Other_Sales: The total number of units sold in millions for the rest
  of the world.
- Global_Sales: The total number of units sold in millions.
- Critic_Score: Aggregate score compiled by Metacritic staff.
- Critic_Count: The number of critics used in coming up with the
  Critic_score.
- User_Score: Score by Metacritic’s subscribers.
- User_Count: Number of users who gave the user_score.
- Developer: Party responsible for creating the game.
- Rating: The ESRB rating.

## Results

``` r
library(readr)
library(tidyverse)
game_sales <- read_csv('Video_Game_Sales.csv')
```

### Question 1

## Conclusion
