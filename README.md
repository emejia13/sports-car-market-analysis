# Sports Car Market Analysis: Similarity & Clustering

This project provides a data-driven framework for an independent automotive broker to identify performance-based alternatives to popular sports cars. It combines one-to-one similarity matching with macro-level market segmentation.

## Project Structure
* `sport_car_prices_cleaned.csv`: The cleaned sports car dataset containing vehicle specifications and pricing.
* `analysis.py`: The Python script containing the data scaling, Cosine Similarity matching, and K-Means clustering implementation.
* `elbow_method.png`: Visual output of the Elbow Method used to determine the optimal number of clusters.
* `market_clusters.png`: Scatter plot visualizing the final market segmentation (Horsepower vs. Price).

## Technical Requirements
To run the code, you need Python installed along with the following libraries:
* pandas
* numpy
* scikit-learn
* matplotlib
