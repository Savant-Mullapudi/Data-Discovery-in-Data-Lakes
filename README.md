# Data Discovery in Data Lakes

## Introduction

This project focuses on the process of data discovery within a data lake, where data is often stored in a schema-less manner. The objective is to explore, join, and analyze data from various heterogeneous tables to build a cohesive dataset. The project is divided into two main parts: finding join paths and building a new dataset for training a regression model.

## Part 1: Finding Join Paths

In this part, the goal is to identify plausible join paths between various tables within the data lake. Since data lakes typically lack a predefined schema, the challenge is to discover connections between tables by:

- **Identifying Common Attributes**: Determine the columns that can be used to join tables.
- **Using Similarity Metrics**: Apply metrics such as edit distance, Jaccard similarity, and TF-IDF with cosine similarity to justify the selection of columns for joins.
- **Justification**: Provide reasons for the chosen join paths based on the nature of the data and the metrics used.

## Part 2: Building a New Dataset and Model Training

After finding the join paths, the next step is to build a comprehensive dataset and train a regression model. This involves:

- **Table Joining**: Combine the tables based on the identified join paths to create the final dataset.
- **Feature Engineering**: Create new features from the joined tables to enhance the dataset.
- **Data Cleaning**: Clean and preprocess the feature columns to ensure data quality.
- **Data Splitting**: Split the dataset into training and test sets for model training.
- **Model Training**: Train a regression model using the cleaned dataset.
- **Evaluation**: Evaluate the model's performance using Mean Squared Error (MSE).


