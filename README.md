# Swahili News Classification
LSTM, CNN and Transformer Deep Learning Models for Text Classification Tasks in Swahili
# Overview
This project focuses on developing a multi-class classification model to classify Swahili news articles into specific categories. The model is designed to help Swahili online platforms automatically group news articles according to their categories, making it easier for readers to find the news they are interested in. The project also contributes to the broader goal of ensuring that the Swahili language is well-represented in digital applications and online products.
# Dataset
The dataset used in this project contains 6,439 rows of news articles from various sources in Tanzania. Each article is labeled with one of the five categories mentioned above. The dataset is sourced from Zindi.(http://zindi.africa/competitions/swahili-news-classification/data)

# Experimental Procedures
- Loading the Data: The dataset is loaded from a CSV file.
- Features and Target Variables: Understanding the content and category columns.
- Data Preprocessing: Cleaning and preparing the text data for modeling.
- WordCloud: Visualizing the most common words in each category.
- Label Encoding: Converting categorical labels into numerical values.
- Word Embedding: Transforming text data into numerical vectors.
- Model Development: Building and training classification models using:
  a) Term Frequency-Inverse Document Frequency (TF-IDF)
  b) Long Short-Term Memory (LSTM) networks
  c) Convolutional Neural Networks (CNN)
  d) Transformers
- Validation: Evaluating the model's performance using accuracy, classification reports, and confusion matrices.
- Data Visualization
- Category Distribution: A count plot showing the distribution of news articles across different categories.
- News Length Distribution: A histogram showing the distribution of article lengths.

# Dependencies
The project uses the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- sklearn
- wordcloud
- tensorflow
- keras

# Usage
Install Dependencies: Ensure all required libraries are installed.

bash
Copy
pip install pandas numpy matplotlib seaborn nltk sklearn wordcloud tensorflow keras
Load the Dataset: The dataset is loaded using pandas.

# python
Copy
import pandas as pd
train = pd.read_csv('/content/drive/MyDrive/NLP/Train (2).csv')
test = pd.read_csv('/content/drive/MyDrive/NLP/Test.csv')
Data Preprocessing: Clean and preprocess the text data.

 
