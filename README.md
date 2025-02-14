# DSA210-MARTI-PROJ

## Description

Sabancı University CS210 Introduction to Data Science Course Fall 2023-2024 Term Project.
This project analyzes my personal transportation data using Martı scooters, focusing on the trade-off between time savings and financial costs compared to walking. I will be using the database of my Martı account which includes the distances, times and prices of each ride between 2020 and 2024.

## Table of Contents
1-Motivation

2-Data Source

3-Data Processing

4-Data Visualizations

5-Data Analysis

  * Time Saved Using Scooters
  * Cost Analysis of Scooter Usage
  * Walking vs. Scooter Comparisons
    
6-Limitations


## Motivation

Transportation is an essential part of daily life, and finding efficient ways to travel can have significant impacts on both time and money. With Martı scooters becoming a popular mode of transportation in urban areas, this project aims to analyze whether using scooters instead of walking is a cost-efficient and time-saving option. The goal is to quantify the time saved by using scooters and evaluate the associated financial costs. I will try to prove "Martı scooter usage reduced my daily transportation time but proved to be a more expensive option compared to walking."

## Data Source
I am using two primary data sources:

1-Martı Scooter Data

Exported from the Martı app, this dataset includes:

* Ride durations (minutes)
* Distances traveled (kilometers)
* Costs (₺)
  
2-Walking Reference Data

Based on publicly available metrics, the average walking speed for a healthy adult is approximately 5 km/h (or 12 minutes per kilometer). This data will be used to calculate the time it would have taken to walk the same distances as the scooter rides.

## Data Processing

The raw data requires preprocessing to enable meaningful comparisons between scooter usage and walking. The key steps include:

1- Martı Scooter Data

 * Convert ride durations and distances into consistent units.
 * Calculate cost per kilometer and cost per minute for each ride.
   
2- Walking Data

 * Use the average walking speed (5 km/h) to estimate the time it would have taken to walk the distances covered by Martı scooters.

3- Combined Data

 * Merge the scooter data with the walking data for direct comparisons.
 * Calculate time saved and extra costs incurred by using scooters instead of walking.

## Data Visualizations

Key visualizations will be created to support the analysis, including:

1- Time Saved vs. Distance Traveled: A scatter plot showing how much time was saved by using a scooter compared to walking.

2- Cost Efficiency: Bar charts comparing cost per kilometer and per minute for scooter rides.

3- Daily Summary: Line graphs showing total transportation time and costs for both modes of transportation.

## Data Analysis
The analysis will focus on the following key questions:

1. Time Saved Using Scooters
 * Calculate the difference in time between walking and scooter rides:

     Time Saved (min) = Walking Time − Scooter Time

 * Assess how the time saved changes with distance.
2. Cost Analysis

 * Calculate the cost per kilometer and per minute for scooter rides:

     Cost per km (₺/km) = Scooter Cost(₺) / Scooter Distance(km)

     Cost per min (₺/min) = Scooter Cost(₺) / Scooter Time(min)
​
 
 * Compare these costs to walking, which is effectively free.
   
3. Walking vs. Scooter Usage

 * Quantify the trade-off between financial cost and time saved:

    Cost per time saved (₺/min) = Scooter Cost(₺) / Time Saved(min)
​
 * Identify whether scooter usage is justified for specific distances.

## Limitations

1. Data Limitations

 * The analysis assumes a constant walking speed of 5 km/h, which may not accurately reflect real-world conditions.
 * Martı data does not account for potential discounts or promotions, which could affect cost calculations.

2. Personal Limitations

 * As this analysis is based on personal transportation data, the findings may not generalize to other users.
 * The project does not account for environmental or health benefits of walking



