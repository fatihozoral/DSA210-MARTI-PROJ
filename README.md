# DSA210-MARTI-PROJ

## Description

Sabancı University CS210 Introduction to Data Science Course Fall 2023-2024 Term Project.
This project analyzes my personal transportation data using Martı scooters, focusing on the trade-off between time savings and financial costs compared to walking.

## Table of Contents
1-Motivation

2-Tools

3-Data Source

4-Data Processing

5-Data Visualizations

6-Data Analysis

  * Time Saved Using Scooters
  * Cost Analysis of Scooter Usage
  * Walking vs. Scooter Comparisons
7-Findings

8-Limitations

9-Future Work

## Motivation

Transportation is an essential part of daily life, and finding efficient ways to travel can have significant impacts on both time and money. With Martı scooters becoming a popular mode of transportation in urban areas, this project aims to analyze whether using scooters instead of walking is a cost-efficient and time-saving option. The goal is to quantify the time saved by using scooters and evaluate the associated financial costs.

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




