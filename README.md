# Monte_Carlo_Astros_R


## Goal/Overview
This project simulates the 2022 World Series matchup between the Houston Astros and the Philadelphia Phillies using the Monte Carlo method in R. The goal is to model and predict series outcomes based on historical team performance data.

## Data/EDA:
The data for this project is sourced from the Lahman package, which contains comprehensive historical baseball statistics. The analysis begins by examining all MLB teams from 2010 through 2022 to establish baseline performance patterns across the league. From there, the focus narrows to a direct comparison between the Houston Astros and the Philadelphia Phillies.

To evaluate the impact of different factors on game outcomes, correlation analysis is performed between various performance variables and win/loss results. P-values are then ranked to determine which variables are most strongly associated with winning. These top predictors are selected for use in the subsequent simulation model.

## Simulation:
Using the five most significant variables identified from the EDA, a formula is constructed to model game outcomes. A Monte Carlo simulation is then applied to replicate the dynamics of a seven-game World Series matchup between the Astros and the Phillies.

The results demonstrate that while the model does not consistently predict the outcome of individual games, it performs effectively in forecasting the overall series winner. This finding is consistent with expectations, as individual baseball games can be highly variable, but outcomes across a series tend to stabilize and reflect underlying team strengths more reliably.

## Libraries:
* tidyverse
* Lahman
* Patwork
* dplyr
* ggcorrplot
* Car

