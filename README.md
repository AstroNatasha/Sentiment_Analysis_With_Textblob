# Sentiment Analysis Using TextBlob on Amazon Fine Food Reviews

## Abstract
This project aims to conduct sentiment analysis on a subset of the Amazon Fine Food Reviews dataset obtained from Kaggle. The dataset, titled "Review.csv," contains user reviews of food products on Amazon. The sentiment analysis is performed using the TextBlob library, which offers a straightforward API for natural language processing tasks.

## About the Repository
food_review_sentiment_analysis.ipynb: Python code for sentiment analysis
Reviews.csv: dataset file

## Dependencies
- pandas
- matplotlib
- textblob


## How to Use the Code
1. Clone this repository or download the SentimentAnalysisAmazonReviews.ipynb file to your working environment.
2. Execute the Python code in your environment, using a Python environment of your choice, such as Jupyter Notebook or an integrated development environment (IDE).

Ensure that the Review.csv file is present in the same directory as the Python file. Also, make sure the required libraries are installed in your Python environment.

## Code Overview
### Read Data:

The script reads the Amazon Fine Food Reviews dataset using the pandas library and limits the analysis to the first 100 rows for demonstration purposes.
### Sentiment Analysis:

- TextBlob's sentiment analysis is applied to the "Text" column of the dataset to obtain polarity scores.
- The sentiment scores are then scaled to a user-defined range (1 to 5) using linear transformation.
  
### Visualization:

- A histogram is created to visualize the distribution of sentiment scores.
- The histogram shows the frequency of sentiment scores within the specified range.

## Output:

- The script saves the first 100 rows of the dataset with added sentiment scores to an Excel file (ReviewOutputLimited.xlsx).
- A PNG file (SentimentReview.png) is generated to visualize the sentiment distribution.

## Adjustments

- Users can adjust the csv_file variable to point to their specific dataset file.
- The code allows users to modify the scaling range for sentiment scores by adjusting the NewRange variable.

## Conclusion

This script provides a basic example of sentiment analysis using TextBlob on a subset of the Amazon Fine Food Reviews dataset. Users can further customize the script based on their specific dataset and analysis requirements.

### Note:
Kaggle. (2023). Amazon Fine Food Reviews. Kaggle. https://www.kaggle.com/snap/amazon-fine-food-reviews
