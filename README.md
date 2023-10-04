# Twitter Sentiment Analysis

![Twitter Logo](https://cdn4.iconfinder.com/data/icons/social-media-2210/24/Twitter-512.png)

The project utilizes a dataset called Twitter Sentiment Analysis, sourced from Kaggle, containing a total of 27,480 tweets. This dataset includes various attributes such as TextID, Text, Selected_text, Sentiment, Time of Tweet, Age of user, Country, Population of the country, Land area, and Density.

## Introduction

Twitter is a widely popular social media platform with approximately 450 million monthly active users as of 2023. Users can express their thoughts and ideas in tweets of up to 280 characters. Twitter serves as a hub for exchanging information, networking, marketing, and promoting organizations and products. 

The objective of sentiment analysis, a Natural Language Processing (NLP) technique, is to identify and extract subjective information from text sources. Twitter sentiment analysis specifically involves analyzing the sentiments expressed in tweets to gain insights into public opinion. This analysis is valuable not only for understanding public sentiment but also for political analysis, public opinion research, and various other fields where understanding people's thoughts and emotions is crucial.

## Preprocessing

To ensure the accuracy of sentiment analysis, the following preprocessing steps were applied to the Twitter Sentiment Analysis dataset:

1. **URL Removal**: A regular expression was used to eliminate URLs from tweets, replacing them with blank spaces.

2. **Tokenization**: The NLTK library packages, including `word_tokenize`, were used to tokenize the words in the tweets.

3. **Stopword Removal**: Stopwords, punctuation, and special characters were removed to focus on meaningful content.

4. **Lemmatization**: The NLTK `WordNetLemmatizer` was employed for lemmatization, and Universal POS tagging was utilized to accurately lemmatize words.

The ultimate goal was to transform the text data into numerical feature vectors using the Bag of Words strategy and TF-IDF Vectorization.

## Repository Structure

The repository consists of two main folders:

- **code**: This folder contains the Jupyter Notebook file (`.ipynb`) and an HTML version of the code for the sentiment analysis project.
- **data**: Here, you'll find the dataset files:
  - `train.csv`: The training dataset used for model development.
  - `test.csv`: The testing dataset used for evaluating the model.
  - `project_presentation.ppt`: A PowerPoint presentation summarizing the project.

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/NikhilJamma/Twitter-Sentiment-Analysis.git
```

2. Navigate to the `code` folder and open the Jupyter Notebook to explore the code and analysis.

3. The dataset files are available in the `data` folder for your reference.

4. Feel free to explore, modify, or enhance the code and analysis as needed for your specific requirements.

## Dependencies

Ensure you have the following libraries installed:

- Python 3.x
- Jupyter Notebook
- NLTK
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

*Disclaimer: This project is for educational and research purposes only. The sentiments expressed in the dataset do not reflect the views of the repository owner.*
