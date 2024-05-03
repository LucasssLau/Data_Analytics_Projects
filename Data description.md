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


## Data Limitations

- The data does not include personally identifiable information due to privacy concerns, which limits the ability to analyze user demographics.
- Additionally, pricing data is not available.
