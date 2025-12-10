🚲 Optimizing Bluebikes Operations through Spatial and Demand Forecasting

📌 Overview

This project analyzes Bluebikes trip data from 2018–2024 to identify operational challenges and uncover opportunities for improving system efficiency. Using BigQuery, Python, and spatial analytics, we examined ridership patterns, user behavior, station usage, and demand fluctuations across the Boston–Cambridge area. The goal is to support better rebalancing, capacity planning, and infrastructure decisions.

🎯 Objectives

-Understand long-term ridership growth and seasonality

-Compare behavior between member and casual users

-Analyze station-level performance and identify high-throughput hubs

-Study trip durations, distances, and time-of-day demand

-Use spatial analytics to explore patterns by geography and station density

-Provide actionable insights to support Bluebikes operations

🗂️ Data Sources

-Bluebikes Open Data (2018–2024)
Trip-level records including start/end stations, times, durations, and bike type

-Bluebikes Station Information
Geographic coordinates and capacity for all stations

-Optional contextual datasets (weather, MBTA proximity)

All processing was performed using Google BigQuery and Python notebooks.

🔍 Methodology

1. Data Extraction & Cleaning

-Loaded 30M+ rows of trip data from 2018–2024

-Handled missing station values and removed incomplete records

-Standardized timestamps and calculated durations, distances, and ride speeds

2. Exploratory Data Analysis (EDA)

-Yearly and monthly ridership trends

-Trip duration distributions by user type

-Identification of busiest stations

-Time-of-day and weekday/weekend usage patterns

3. Spatial Analysis

-Mapped station density across Boston/Cambridge

-Classified stations as high-, medium-, and low-traffic

-Examined ridership hotspots around universities and business districts

4. Demand Insights

-Member vs. casual behavior comparison

-Seasonal spikes in summer for casual users

-Strong commuter patterns for members during morning/evening peaks

-Identification of stations that frequently exceed or fall below capacity

📈 Key Findings
📌 1. Ridership grew nearly 3× since 2018

-4.5M trips in 2024

-Clear COVID dip in 2020 followed by strong recovery

-Growth driven primarily by members (65–85% of all trips)

📌 2. Clear divide between member vs. casual users

-Members: shorter trips (13–15 min), consistent year-round usage

-Casual users: longer trips (20–25 min), strong summer peaks

📌 3. Station usage is highly concentrated

Top stations are clustered around:

-MIT

-Harvard

-Kendall Square

-Back Bay

The busiest station (MIT Mass Ave) handled over 517K rides.

📌 4. Spatial patterns matter

-Station density strongly correlates with ridership

-University and business districts act as demand anchors

-High-throughput stations indicate potential rebalancing pressure

📌 5. Operational implications

-Summer requires more bikes available for casual riders

-Member-heavy areas need reliable weekday morning/evening rebalancing

-High-traffic stations may require future capacity expansion

🛠️ Technologies Used

-Google BigQuery (SQL, data processing)

-Python (Pandas, Geopandas, Matplotlib)

-Jupyter / BigQuery Notebooks

-Looker

✨ Conclusion

This project provides a data-driven foundation for improving Bluebikes' operational efficiency. By understanding ridership trends, spatial demand patterns, and user behavior, the system can make smarter decisions about bike allocation, station capacity, and future expansions.

📬 Team

Marcus Shi

Mohamad Gong

Arshdeep Oberoi

Tianqi Sun

Tzu-Jen Chen

Xiaoqing Ye
