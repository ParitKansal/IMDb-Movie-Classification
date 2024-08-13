# IMDb Movie Classification 
"A Kaggle notebook for the IMDb Movies classification into different category using NLP and deep learning models."   

![](https://paritkansal121.odoo.com/web/image/332-420a8530/dataset-cover2.webp)



​
## Kaggle Notebook:
**Link**: https://www.kaggle.com/code/paritkansal/movie-classification

## Project Overview: 
The goal of this project is to develop a system that can accurately classify IMDb movies into various classes using NLP techniques, machine learning, and deep learning models. The dataset used is the IMDb Movies Dataset, which contains a set of movies with their descriptions and the classes to which they belong.

### Dataset:

**​Source**: [Genre Classification Dataset IMDb](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)

### Project Steps:

**Data Loading and Exploration**:
- Load and inspect the dataset.
- Clean the data by removing unnecessary columns and handling missing values.

**Data Preprocessing**:
- Convert text to lowercase.
- Remove special characters, stopwords, and perform lemmatization to standardize the DESCRIPTION.

**Feature Extraction**:
- Map each word in DESCRIPTION to an integer and then replace each word with its corresponding vector from the pretrained Word2Vec model.

**Model Training and Evaluation**:
- **Approach 1**: Average the vectors to get a single vector and then use ML models such as Random Forest and XGBoost for classifying movies.
- **Approach 2**: Use word embedding along with bidirectional LSTM to train and evaluate a Deep Learning model.
- **Approach 3**: Use pretrained Word2Vec along with bidirectional LSTM to capture the sequential nature of text data for better performance.

### Outcome:
The project successfully develops a model that achieves an accuracy of 54% in movie classification using Approach 3 with pretrained Word2Vec and bidirectional LSTM, demonstrating the effectiveness of different machine learning techniques in classification.

![App Screenshot](https://paritkansal121.odoo.com/web/image/332-420a8530/dataset-cover2.webp)

