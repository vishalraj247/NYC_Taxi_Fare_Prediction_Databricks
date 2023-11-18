# NYC Taxi Fare Prediction Using Databricks

## Overview
This project aims to predict taxi fares in New York City using machine learning and deep learning techniques. The data is sourced from the New York City Taxi and Limousine Commission (TLC), which includes extensive records from yellow and green taxi cabs.

## Dataset
- **Source:** New York City Taxi and Limousine Commission (TLC)
- **Scope:** Records from Jan 2019 to Apr 2022, including pick-up and drop-off dates/times, locations, distances, fares, and more.
- **Yellow Cabs:** Iconic NYC taxis with comprehensive city coverage.
- **Green Cabs:** Taxis operating in designated areas outside the central city.

## Objectives
- **Fare Prediction:** Develop accurate models to predict taxi fares using historical data.
- **Data Challenges:** Address data type issues, such as the 'airport_fee' field in the yellow taxi dataset.

## Key Features
- **Data Ingestion and Preparation:** Download and load datasets into Azure Blob Storage, followed by processing on Databricks.
- **Machine Learning Models:** Utilize Random Forest and Gradient-Boosted Trees Regressor models using PySpark.
- **Deep Learning Integration:** Apply deep learning techniques to enhance fare prediction accuracy.
- **Cyclical Feature Encoding:** Use cyclical feature encoding for time-series data to capture temporal patterns in fares.

## Technologies Used
- Azure Blob Storage
- Databricks
- Apache Spark (PySpark)
- Machine Learning (Random Forest, Gradient-Boosted Trees)
- Deep Learning Techniques
- Cyclical Feature Encoding

## Repository Contents
- Data ingestion and preparation scripts
- Machine learning model development and tuning notebooks
- Deep learning model integration scripts
- Evaluation and testing scripts
- Documentation and results

## Contributions
Contributions to improve the model's accuracy and efficiency are welcome. Please see the contributing guidelines for more details.

## License
This project is open-source and available under the MIT License. See the LICENSE file for more information.