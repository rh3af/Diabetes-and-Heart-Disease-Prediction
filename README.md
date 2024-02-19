# Health Prediction Projects

This repository contains two projects focused on predicting health-related outcomes using Apache Spark in Databricks. The first project is aimed at predicting diabetes, and the second focuses on predicting heart disease. Both projects are implemented in Scala, leveraging Apache Spark's data processing and machine learning capabilities.

## Projects Overview

### 1. [Diabetes Prediction Project](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6194666043422105/4345123456434117/5294499192919113/latest.html)

#### Introduction
The Diabetes Prediction project analyzes health metrics to predict diabetes onset. It utilizes features such as Pregnancies, Glucose, and BloodPressure, showcasing Apache Spark's capabilities in handling and analyzing large datasets.

#### Dataset Overview
Key features include:
- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration
- BloodPressure: Diastolic blood pressure (mm Hg)

#### Spark Libraries and Functions
- **DataFrame API**: For data processing and manipulation.
- **MLlib**: For building and evaluating machine learning models.
- **Spark SQL**: For structured data querying.

### 2. [Heart Disease Prediction Project](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6194666043422105/3716569565419749/5294499192919113/latest.html)

#### Introduction
This project predicts heart disease using medical indicators, employing Apache Spark within Databricks for data analysis and machine learning.

#### Dataset Overview
Features include age, cholesterol levels, and chest pain type, loaded and processed efficiently using Spark.

#### Spark Libraries and Functions
- **DataFrame API**: Utilized for data handling and preprocessing.
- **MLlib**: Employed for machine learning model creation and evaluation.
- **Spark SQL**: Used for querying and analyzing data.

## Setup and Execution
To run these projects in Databricks:
1. Import the respective Databricks notebook into your workspace.
2. Ensure your cluster is configured with Apache Spark.
3. Execute the notebook cells sequentially to perform the analysis and view predictions.

## Requirements
- Databricks workspace
- Apache Spark cluster

## Authors
- Hemanth C

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- Apache Spark Community
- Databricks
