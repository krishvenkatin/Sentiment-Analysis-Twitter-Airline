# Sentiment Analysis of Twitter Airline Tweets

## Project Overview

This project performs sentiment analysis on Twitter data related to various airlines. The goal is to classify the sentiment of tweets as positive, neutral, or negative using different machine learning models.

## Dataset

The dataset used for this project is the [Twitter US Airline Sentiment dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment). It contains tweets from February 2015 about US airlines and their sentiment labels.

## Project Structure


- **data/**: Contains the dataset used for the analysis.
- **notebooks/**: Jupyter Notebook with the entire analysis, including EDA, model training, and evaluation.
- **README.md**: Project documentation.

## Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/krishvenkatin/Sentiment-Analysis-Twitter-Airline.git
    cd Sentiment-Analysis-Twitter-Airline
    ```

2. Install the required packages:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn nltk imbalanced-learn
    ```

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook notebooks/Sentiment_Analysis_Twitter_Airline.ipynb
    ```

## Analysis

### Exploratory Data Analysis (EDA)

- **Sentiment Distribution**: Visualized the distribution of positive, neutral, and negative tweets.
- **Word Clouds**: Generated word clouds for positive and negative sentiments to identify common words.

### Model Training

- **Text Vectorization**: Used TF-IDF to convert tweet text into numerical features.
- **Class Imbalance Handling**: Used techniques like SMOTE.
- **Models**: Trained Logistic Regression, Random Forest, and SVM models.

### Model Evaluation

- **Classification Reports**: Evaluated models using precision, recall, and F1-score.
- **ROC Curves**: Plotted ROC curves for all models.

### Findings

- **Logistic Regression**: Balanced performance with 78% accuracy.
- **Random Forest**: Robust but slightly lower performance with 76% accuracy.
- **SVM**: Best performer with 79% accuracy.

## Future Work

- Explore advanced models like deep learning.
- Analyze the impact of external events on sentiment.
- Extend analysis to more comprehensive datasets.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
