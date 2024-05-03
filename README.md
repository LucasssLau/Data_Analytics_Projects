# Cyclistic Bike Share Analysis

This repository contains the analysis of bike-share data from the Cyclistic company. The goal of this project is to provide insights into the usage patterns of Cyclistic's bike share system and to identify opportunities to convert casual riders into annual members.

## Repository Structure

- `main.ipynb`: Jupyter notebook containing the full analysis workflow, from data preparation to exploratory data analysis and data visualization.
- `Data Analysis Cyclistic Bike-Share Analysis Case Study.pptx`: A PowerPoint presentation that summarizes the findings of the analysis. It includes visualizations and dashboards that highlight key patterns and trends observed in the data, making it easier to communicate the insights to stakeholders.

## Data Description

The data used in this project includes details of every ride logged by Cyclistic customers from April 2023 to March 2024. The data ranges from 2013 to March 2024, but only the last 12 months are used for this project.

### Data Fields

#### Original
- `ride_id`: Unique identifier for each ride.
- `rideable_type`: Type of bike used (classic, docked, electric).
- `started_at`: Start time of the ride.
- `ended_at`: End time of the ride.
- `start_station_name`: Name of the starting station.
- `start_station_id`: Identifier for the starting station.
- `end_station_name`: Name of the ending station.
- `end_station_id`: Identifier for the ending station.
- `start_lat`: Latitude of the starting point.
- `start_lng`: Longitude of the starting point.
- `end_lat`: Latitude of the ending point.
- `end_lng`: Longitude of the ending point.
- `member_casual`: Type of rider (casual or member).

#### Processed
- `ride_length`: Duration of each ride.
- `ride_length_minutes`: Duration of each ride in minutes.
- `start_hour`: Hour of the day when the ride started.
- `weekday_name`: Day of the week when the ride occurred.
- `ride_length_minutes_category`: Categorization of rides based on their duration in minutes to analyze usage patterns.
- `ride_length_category`: Categorization of rides based on their duration to understand the purpose of usage.

#### Considered but Not Used
- `trip_distance`: Distance of each trip was considered, but not used due to the possibility of circular rides where the start and end points are close, such as riding in a park.

## Tools Used

- **Python**: For data cleaning, manipulation, and analysis.
- **Tableau**: For creating interactive visualizations and dashboards

- ### Python Libraries
- `pandas`: Used for data manipulation and analysis.

## Data Limitations

- The data does not include personally identifiable information due to privacy concerns, which limits the ability to analyze user demographics.
- Additionally, pricing data is not available.

## Contributions

Contributions to this project are welcome. You can contribute in the following ways:

- **Issues**: Submit issues for bugs or feature requests.
- **Pull Requests**: Submit a pull request to improve the analysis or documentation.
