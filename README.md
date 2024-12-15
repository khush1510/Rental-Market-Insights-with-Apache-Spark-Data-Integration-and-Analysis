# Rental-Market-Insights-with-Apache-Spark-Data-Integration-and-Analysis
Analyzed Alberta's rental market using Apache Spark SQL, exploring trends, correlations, and integrating Yelp data for actionable insights.

## Project Overview
This project focuses on analyzing rental market data from platforms like Kijiji, Rentfaster, and Yelp using **Apache Spark SQL**. The goal is to gain actionable insights into rental price trends, the impact of local amenities, and data quality issues while exploring correlations between various attributes.

---

## Features of the Project
1. **Data Collection and Management**:
   - Collected data from **Kijiji**, **Rentfaster**, and **Yelp**.
   - Integrated data sources using Spark DataFrames and enhanced datasets with geographic and quality data from Yelp API.

2. **Data Preprocessing**:
   - Standardized and cleaned data for improved analysis.
   - Established a Spark Cluster for distributed data handling and scalability.

3. **Exploratory Data Analysis (EDA)**:
   - Conducted correlation analysis to identify relationships between rental prices, amenities, and geographic features.
   - Visualized data trends and relationships using Spark visualization tools.

4. **Key Insights**:
   - Evaluated factors influencing rental prices and their connection to amenities.
   - Analyzed correlation matrices between datasets:
     - Yelp and Kijiji listings.
     - Yelp and Rentfaster data.
   - Highlighted areas with weak or no correlation between distance, ratings, and pricing.

---

## Tools and Technologies
- **Data Tools**: Apache Spark, Spark SQL
- **Data Sources**: Kijiji, Rentfaster, Yelp
- **Programming**: Python, PySpark
- **APIs**: Yelp API for additional data enrichment
- **Visualization**: Correlation matrices, Spark tools

---

## Challenges Encountered
- Managing large datasets efficiently for distributed processing.
- Integrating diverse data sources and addressing data quality issues.
- Handling missing or incomplete information for enriched datasets.

---

## Next Steps
1. Enhance datasets with detailed restaurant pricing data for further analysis.
2. Conduct advanced correlation analysis with the enriched dataset to gain deeper insights into rental market dynamics.
3. Explore predictive models for rental price forecasting.

---

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/rental-market-analysis.git
