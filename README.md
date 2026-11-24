# Sentiment Analysis on Customer Reviews (Python)

## Overview
Classifies customer review sentences as Positive, Negative, or Neutral using
Python and TextBlob, then visualizes the most common negative words.

## Dataset
- `Sentiment_Analysis.csv`: a small set of customer review sentences about
  product quality, performance, and customer service.

## Tools Used
- Python, Pandas, TextBlob, WordCloud, Matplotlib, Seaborn
- Google Colab (Jupyter Notebook)

## What I Did
- Loaded and explored the review data with Pandas
- Used TextBlob polarity to score the tone of each sentence
- Labeled each sentence: polarity above 0 = Positive, below 0 = Negative, 0 = Neutral
- Filtered the negative reviews and joined them into one text
- Built a word cloud to show the most common negative words
- Exported the labeled data to Excel

## Key Insights
- Reviews with words like "poor", "faulty", and "frustration" were labeled Negative
- Negative reviews mostly talk about poor customer support and product defects

## How to Run
1. Download `Sentiment_analysis.ipynb` and the CSV file
2. Open the notebook in Google Colab or Jupyter
3. Install the libraries: `pip install textblob wordcloud`
4. Run all cells

## Future Improvements
- Try a larger dataset
- Compare TextBlob with other models such as VADER
