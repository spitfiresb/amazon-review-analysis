# Amazon Customer Review Analysis

## Project Overview

This project focuses on analyzing Amazon product reviews for a set of automotive jumper cables. The analysis includes the identification of the most helpful reviews by calculating the helpfulness ratio (helpful votes / total votes). This project uses Apache Spark, running on Databricks, to efficiently process and analyze large datasets. The dataset was sourced from the following website: [Amazon Review Dataset](https://jmcauley.ucsd.edu/data/amazon/).

## Dataset Information

The dataset contains JSON records for Amazon product reviews. Each record includes various fields, such as:
- reviewerID: The unique ID of the reviewer.
- asin: The unique product identifier (ASIN).
- reviewText: The review written by the customer.
- overall: The rating given by the customer (1-5 scale).
- helpful: A list indicating the number of people who found the review helpful and the total number of votes.
- reviewTime: The time the review was submitted.

This project processes this data using Apache Spark and Databricks to compute the helpfulness ratio for each review and identify the most helpful ones.

## Technologies Used
- Apache Spark (with Databricks)
- Python
- JSON Data Processing
- Databricks Community Edition

## How to Run the Code
1. Clone this repository to your local machine.
2. Upload the dataset (Automotive_5.json) to Databricks.
3. Follow the notebook for step-by-step instructions on analyzing the dataset.
4. The code will compute the helpfulness ratio for reviews and display the top reviews based on this metric.

## License
This project is licensed under the MIT License.
