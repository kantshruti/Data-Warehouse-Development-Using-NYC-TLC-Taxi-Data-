🚕 TLC Taxi Data Warehouse & Data Mining Project
This repository presents a comprehensive approach to building a modern data warehouse and implementing data mining models using NYC's open Taxi and For-Hire Vehicle (FHV) trip data. The goal is to derive insights from Yellow Taxi, Uber, and Lyft data across 2023–2024 for strategic analysis and predictive modeling.

📁 Project Files
Data Warehouse Using Open Data TLC Taxi Data.docx
Detailed documentation of the data warehousing process, data mart designs, ETL pipeline, and predictive modeling methodology.

Data Warehousing and Data Mining Approach for TLC Taxi Data.pptx
A slide deck summarizing the project architecture, key insights, regression and clustering models, and visualizations.

🧠 Objectives
Build a star-schema-based data warehouse using Google Cloud Platform (BigQuery).

Create data marts to analyze:

Trip metrics by time and location.

Ride type performance and driver efficiency.

Apply data mining techniques:

📈 Multiple Linear Regression for trip demand forecasting.

📊 K-Means Clustering to identify trip pattern segments.

⚙️ Tools & Technologies
Google Cloud Platform (BigQuery, Cloud Storage)

SQL (for ETL, modeling, querying)

Python (scikit-learn) (optional for modeling outside SQL)

Excel / Google Sheets (for data visualization)

NYC TLC Trip Record Data (2023 & 2024 Yellow Taxi, Uber, Lyft)

📊 Data Warehouse Design
Fact Table: fact_trips — trip-level metrics (trip count, distance)

Dimensions:

dim_time — year, month, day, hour

dim_geography — pickup/drop-off boroughs and zones

dim_ride_type — Taxi, Uber, Lyft

dim_driver (optional) — driver-level metrics (anonymized)

🔍 Data Mining Models
1. Multiple Linear Regression
Goal: Predict trip volume using time, borough, and ride type features.

Framework: CRISP-DM

Features Used: hour of day, day of week, pickup/drop-off boroughs, ride type

Tools: BigQuery ML / scikit-learn

2. K-Means Clustering
Goal: Group pickup locations based on trip volume and distance

Features: Trip volume, average distance, borough

Outcome: Segmentation for operational targeting or resource allocation

📈 Visualizations
Bar charts for feature importance

Line charts for prediction vs. actual trips

Heatmaps and cluster maps of NYC zones

Top 10 trip locations and distances by borough

🔮 Future Enhancements
Integrate real-time variables (e.g., weather, fares)

Automate prediction pipelines via BigQuery ML

Expand with historical data for deeper time-series analysis

🔗 Data Source
NYC TLC Trip Data:
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

🧑‍💻 Author
Shruti Kant
MIS Senior | Data Analytics Enthusiast
Email: sk852shruti@gmail.com

