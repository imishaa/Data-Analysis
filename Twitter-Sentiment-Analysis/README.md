# Twitter Sentiment Analysis Project

## Overview

This project focuses on performing sentiment analysis on Twitter data to categorize tweets as positive, negative, or neutral. The analysis is conducted using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool. The dataset used for this analysis is sourced from Twitter and contains tweet information.

## Dataset

The dataset is obtained from the following link: [Twitter Dataset](https://raw.githubusercontent.com/amankharwal/Website-data/master/twitter.csv). It includes the following key columns:

- `tweet`: Text content of the tweet.
- `Positive`: Positive sentiment score assigned to the tweet.
- `Negative`: Negative sentiment score assigned to the tweet.
- `Neutral`: Neutral sentiment score assigned to the tweet.

## Code

The provided Python script utilizes various libraries, including pandas, numpy, scikit-learn, and nltk, to perform sentiment analysis. The key steps include:

1. Loading the Twitter dataset.
2. Cleaning and preprocessing the tweet text.
3. Using the VADER sentiment analysis tool to assign sentiment scores (positive, negative, and neutral) to each tweet.
4. Summing the sentiment scores and determining the overall sentiment of the dataset.
5. Printing the cleaned dataset with sentiment scores and displaying an overall sentiment emoji based on the sum of positive, negative, and neutral scores.

## Results

The results of the sentiment analysis are displayed in the cleaned dataset, showing the tweet text along with positive, negative, and neutral sentiment scores. Additionally, an overall sentiment emoji is printed based on the sum of sentiment scores, indicating whether the overall sentiment is positive, negative, or neutral.

## Usage

1. Ensure you have the required libraries installed:

   ```bash
   pip install pandas numpy scikit-learn nltk
   ```

2. Run the provided Python script:

   ```bash
   python script.py
   ```

3. Explore the sentiment scores and overall sentiment emoji generated for the Twitter dataset.


Happy learning !
