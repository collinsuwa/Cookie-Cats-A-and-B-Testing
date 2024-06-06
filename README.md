# Cookie-Cats-A-and-B-Testing
# AB Cookie Cats Analysis

This repository contains the analysis of the AB test performed for the Cookie Cats mobile game to evaluate the impact of different game mechanics on player engagement and retention.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Objectives](#objectives)
- [Analysis Process](#analysis-process)
- [Results](#results)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Introduction

Cookie Cats is a popular mobile puzzle game developed by Tactile Entertainment. In this analysis, we conducted an A/B test to determine the effect of a new game feature on player retention and engagement. The goal is to analyze the data collected from the test and draw actionable insights to inform future game design decisions.

## Dataset

The dataset consists of player interaction logs, which include information such as:
- `user_id`: Unique identifier for each player
- `variant`: A/B test group identifier (control or variant)
- `day_1_retention`: Boolean indicating if the player was retained on day 1
- `day_7_retention`: Boolean indicating if the player was retained on day 7
- `install_date`: Date when the player installed the game
- `game_events`: Events logged by players during gameplay

## Objectives

1. **Evaluate Retention Rates**: Compare day 1 and day 7 retention rates between the control group and the variant group.
2. **Analyze Player Engagement**: Measure the level of engagement by analyzing in-game events and session duration.
3. **Identify Trends and Insights**: Identify any trends or patterns in the data that could explain the impact of the new game feature.

## Analysis Process

1. **Data Cleaning**: Preprocessing the data to handle missing values, duplicates, and incorrect entries.
2. **Exploratory Data Analysis (EDA)**: Visualizing and summarizing the data to understand the distribution and relationships between variables.
3. **Hypothesis Testing**: Conducting statistical tests to determine if there are significant differences in retention and engagement metrics between the control and variant groups.
4. **Modeling**: Using machine learning models to predict player retention and identify key factors influencing player behavior.
5. **Visualization**: Creating visualizations to effectively communicate the findings and insights from the analysis.

## Results

- **Day 1 Retention**: The variant group showed a slight increase in day 1 retention compared to the control group.
- **Day 7 Retention**: There was no significant difference in day 7 retention between the two groups.
- **Player Engagement**: The variant group exhibited higher engagement levels, with more in-game events and longer session durations.

## Conclusion

The A/B test results suggest that the new game feature positively impacts day 1 retention and player engagement, although it does not significantly affect day 7 retention. These findings can help guide future game design and feature implementation decisions.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scipy
- github
