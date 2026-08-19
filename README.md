# Kickstarter Crowdfunding Analysis

This project analyzes a Kickstarter dataset in a notebook. The workflow covers cleaning and preparing the data, creating business metrics, loading it into MongoDB, and then exporting it to Apache Cassandra for additional analysis.

## Project Goal

The notebook explores Kickstarter campaign success patterns and answers practical questions such as:

- Which categories have the highest success rate?
- Which countries receive the highest average funding?
- Which projects have the best funding ratios?
- Which categories produce the most failed campaigns?
- How does campaign duration affect project outcomes?
- Which month is best for launching successful campaigns?

## Contents

- Data loading and inspection
- Handling missing values and duplicate records
- Converting date fields to proper datetime format
- Feature engineering such as campaign duration and funding ratio
- Exporting the cleaned dataset to CSV
- Loading data into MongoDB for aggregation queries
- Connecting to Cassandra using a secure connect bundle
- Creating a Cassandra table and inserting cleaned records
- Running analytical queries in MongoDB and Cassandra
