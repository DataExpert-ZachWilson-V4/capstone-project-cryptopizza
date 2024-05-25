# Crypto Price Prediction Project

## Overview

The Crypto Price Prediction Project aims to create a robust pipeline for collecting, processing, and analyzing data to predict the prices of various cryptocurrencies. This project integrates macroeconomic data, market data, sentiment analysis, and geopolitical factors to enhance prediction accuracy. Leveraging cutting-edge technologies such as Trino, Apache Iceberg, Apache Airflow, and DBT (Data Build Tool), we ensure scalability, efficiency, and reliability in data handling and model deployment. The core of our prediction model will be based on Long Short-Term Memory (LSTM) networks, which will be developed in future phases due to the project delivery timeline constraints.

## Differentiation

While there are existing projects with similar objectives, our project differentiates itself in several key ways:

1. **Integration of Geopolitical Data**: We incorporate geopolitical data and political risk factors, which are not commonly used in similar projects. This allows us to capture the broader economic and political context that can influence cryptocurrency prices.
2. **Advanced Data Management**: Using Apache Iceberg for data storage ensures scalability and high performance in managing large datasets. Trino provides fast and efficient distributed SQL querying capabilities, enhancing our data processing capabilities.
3. **Full Automation with Apache Airflow and DBT**: Our project includes a fully automated pipeline using Apache Airflow and DBT, ensuring timely and accurate data updates and model predictions. This level of automation is crucial for maintaining up-to-date predictions in a rapidly changing market.
4. **Comprehensive Data Sources**: We gather data from a diverse set of sources, including macroeconomic indicators, market data, sentiment analysis from social media, and direct blockchain data. This comprehensive approach allows for more robust and accurate predictions.
5. **Visualization and Insights**: Advanced dashboards and visualizations using PowerBI or Tableau provide real-time insights into the predictions and underlying data trends, offering more value to users.

## Project Objectives

- **Data Collection**: Efficiently gather and store historical and real-time data on cryptocurrency prices, macroeconomic indicators, market sentiment, and geopolitical factors.
- **Data Processing**: Clean, transform, and integrate data from multiple sources to prepare it for analysis.
- **Pipeline Automation**: Automate data workflows using Apache Airflow and DBT to ensure timely and accurate updates.
- **Data Storage**: Utilize Apache Iceberg for scalable and performant data storage.
- **Query Optimization**: Use Trino for fast and efficient data querying and analysis.
- **Deep Learning Integration**: Plan to integrate deep learning models to predict cryptocurrency prices using various data inputs.

## Data Sources

- **Cryptocurrency Market Data**: Sources like CoinGecko and CoinMarketCap for market data, including historical prices and trading volumes.
- **Macroeconomic Data**: Sources such as FRED and World Bank for economic indicators like interest rates, inflation, and GDP.
- **Market Data**: Yahoo Finance and Alpha Vantage for data on stocks, bonds, exchange rates, and other financial instruments.
- **Sentiment Data**: Twitter and Reddit for sentiment analysis, and Google Trends for search trends data.
- **Blockchain Data**: Blockchain.com for data on cryptocurrency transactions and other blockchain metrics.
- **Geopolitical Data**: Global Conflict Tracker and Political Risk Services for geopolitical risk and policy uncertainty.

## Motivation

The motivation behind this project is to leverage the vast amount of available data to make accurate predictions in the highly volatile cryptocurrency market. By integrating diverse data sources and employing advanced data processing and analysis tools, we aim to provide valuable insights and predictions that can assist traders, investors, and analysts in making informed decisions. The inclusion of geopolitical and macroeconomic factors adds a unique dimension to our analysis, reflecting the real-world influences on the cryptocurrency market.

## Architecture

The architecture of the Crypto Price Prediction Project is designed to be modular, scalable, and robust. It includes the following components:

1. **Data Ingestion**: Collect data from various sources using APIs and web scraping tools.
2. **Data Storage**: Store raw and processed data in Apache Iceberg tables.
3. **Data Processing and Transformation**: Clean and transform data using Python, Apache Spark, and DBT.
4. **Workflow Orchestration**: Automate the entire pipeline using Apache Airflow.
5. **Data Querying**: Use Trino to perform efficient and fast queries on the data stored in Iceberg tables.
6. **Deep Learning (Future Integration)**: Plan to develop prediction models using Python, TensorFlow, and Keras.
7. **Visualization**: Create dashboards and visualizations using tools like PowerBI or Tableau.

## Technologies Used

- **Trino**: A distributed SQL query engine for running fast, interactive analytic queries.
- **Apache Iceberg**: A high-performance format for huge analytic tables.
- **Apache Airflow**: A platform to programmatically author, schedule, and monitor workflows.
- **DBT**: A tool for transforming data inside data warehouses more effectively.
- **Python**: The primary programming language for data processing and deep learning.
- **TensorFlow and Keras (Future Integration)**: Libraries for building and training deep learning models.
- **PowerBI/Tableau**: Tools for data visualization and dashboard creation.

## Data Pipeline

### Data Ingestion
- Collect data from various sources using APIs (CoinGecko, CoinMarketCap, FRED, etc.).
- Use Airflow DAGs to schedule and automate the data collection process.

### Data Storage and Processing
- Store raw data in Apache Iceberg tables.
- Clean and transform data using Python, Apache Spark, and DBT.
- Use Trino to query and analyze the processed data.

### Automation and Orchestration
- Use Apache Airflow to orchestrate the data ingestion, processing, and storage workflows.

## Future Integration: Deep Learning

### Feature Engineering
- Create features from the processed data, such as moving averages, volatility, sentiment scores, and macroeconomic indicators.

### Model Development
- Plan to develop and train models using algorithms like LSTM, GRU, and other neural networks.

### Model Evaluation
- Evaluate model performance using metrics such as MAE, MSE, RMSE, and MAPE.
- Optimize model parameters to improve prediction accuracy.

### Deployment
- Implement a pipeline to use the trained model for making predictions on new data.
- Use visualization tools like PowerBI or Tableau to display the predictions and insights.
