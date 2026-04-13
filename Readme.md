# Cyclistic Bike-Share: Member vs. Casual Case Study 

## Project Overview

This project is part of the Google Data Analytics Professional Certificate. The goal is to analyze historical trip data from Cyclistic, a fictional bike-share company in Chicago, to identify how annual members and casual riders use the service differently. These insights will drive a new marketing strategy aimed at converting casual riders into loyal annual members.

## The Business Task

Objective: Design marketing strategies to convert casual riders into annual members by analyzing 2025 trip data to uncover distinct usage patterns.

Data Source & Integrity
Scope: 12 months of historical trip data (January 2025 - December 2025).

Scale: Over 5.55 million individual trip records.

Tools: Python (Pandas, Matplotlib, Seaborn) was utilized for data cleaning, transformation, and visualization due to the massive scale of the dataset.

Key Data Cleaning Steps
Merging: Consolidated 12 monthly CSV files into a single unified DataFrame.

Temporal Accuracy: Resolved "Negative Duration" errors by localizing timestamps to America/Chicago and converting to UTC to handle Daylight Savings Time (DST) shifts.

Feature Engineering: Calculated trip durations and extracted day-of-week attributes for behavioral analysis.

## Key Insights
The Duration Gap: Casual riders maintain significantly longer trips, averaging 22.60 minutes, compared to members who average 12.33 minutes.

The Saturday Surge: Casual ridership peaks on Saturdays (413,676 rides), while members show steady utility usage throughout the workweek.

User Split: While 64% of users are members, the 36% casual segment represents nearly 2 million potential conversion targets.

## Data Visualizations
The analysis includes three primary visualizations:

Member vs. Casual User Split: A pie chart highlighting market composition.

Average Ride Length: A bar chart comparing the leisure vs. utility nature of trips.

Weekly Usage Trends: A line graph and grouped bar chart identifying peak engagement windows.

## Top Recommendations
Weekend-Specific Membership: Introduce a "Weekend Warrior" pass to target the high-volume, long-duration casual usage on Saturdays.

Value-Based Marketing: Create campaigns highlighting the cost-savings of membership for rides exceeding 20 minutes.

Strategic Geofencing: Deploy digital advertisements near recreational hubs (parks/waterfronts) during weekend peak hours.