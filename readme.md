# Sentiment Analysis Project

## Overview

This project focuses on comparing the fine-tuning process and the pre-trained model on the task of sentiment analysis of Twitter data. We fine-tuned the `distilbert-base-uncased` model and compared it to a basic statistical sentiment analysis function from the TextBlob library. Additionally, we tested different preprocessing methods like stemming, lemmatization, and simple cleaning to see the impact on sentiment analysis.

## Features

- Text preprocessing (stemming, lemmatization, simple cleaning)
- Sentiment classification using fine-tuned `distilbert-base-uncased` model
- Sentiment classification using pre-trained `distilbert-base-uncased` model
- Sentiment classification using TextBlob
- Sentiment classification using Machine learning model with TF-IDF feature selection
- Comparison of results
- Visualization of results

## Installation

To install the necessary dependencies, run:

```bash
pip install -r requirements.txt
```

<!-- ## Usage

To analyze sentiments in a tweet, use the following command:

```bash
python analyze.py --input <tweet_file.txt>
``` -->

## Project Structure

<!-- - `analyze.py`: Main script for sentiment analysis
- `preprocessing.py`: Functions for text preprocessing -->

- `tweet_sentiment_analysis*/`: Directories containing finetuned models ignored becuase of the size
- `data/`: Directory for storing datasets ignored becuase of the size
- `results/`: Directory for storing analysis results
- `sentiment-analyses.ipynb`: Notebook that contains the full process

## Contact

For any questions or suggestions, please contact [LinkedIn](https://www.linkedin.com/in/oussamamahdjour/).
