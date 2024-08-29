# YouTube-Data-Processing-and-Analytics-Pipeline


## Project Overview
This project focuses on developing a data pipeline to analyze performance metrics of YouTube channels, aiming to understand engagement patterns and optimize content strategies specifically for data science-related channels.

## Data Collection and Preparation
- **Data Sources**:Gathered data from top 10 data science channels such as Corey Schafer, Sentdex, and others.
- **Data Extraction**: Used the YouTube API for real-time data retrieval.
- **Automation**: Implemented Google Cloud Functions and Pub/Sub for automated data extraction at 5-minute intervals.
- **Storage**: Stored raw data as CSVs in Google Cloud Storage.

## Data Pipeline
- **Processing**: Leveraged PySpark on Google Cloud Dataproc for data cleaning and transformation.
- **Loading**: Loaded processed data into Google BigQuery for seamless querying.
- **Transformation**: Addressed null values, created new features, normalized data, and stored it in BigQuery tables.

## Visualization and Tools
- **Visualization**:Developed interactive dashboards with Looker Studio. [View the dashboard here](https://lookerstudio.google.com/u/2/reporting/fbc1810b-9126-4f16-b37e-ad9d751dfccb/page/D4Y2D)

- **Tools Used**:
  - Google Cloud Functions
  - Google Cloud Pub/Sub
  - Google Cloud Storage
  - Google Cloud Dataproc
  - PySpark
  - Google BigQuery
  - Looker Studio

## Key Insights
- Identified channels with the highest average views.
- Highlighted the most viewed videos by channel.
- Analyzed videos with the lowest engagement.
- Explored view patterns by day and time.
- Recognized the most popular upload days for content creators.

## Recommendations
- Align video uploads with peak engagement times.
- Prioritize content types that boost viewer interaction.
- Adjust strategies to capitalize on optimal viewing days and times.
