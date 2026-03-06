#Interactive-QuizApplication

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SAIDHARANEE

*INTERN ID*: CTIS4535

*DOMAIN*: DATA ANALUTICS

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

---

# NLP Sentiment Analysis on Restaurant Reviews

## Project Overview
This project performs **Sentiment Analysis on restaurant review data** using **Natural Language Processing (NLP)** techniques. The goal is to classify customer reviews as **positive or negative** based on the text content.

The project demonstrates the complete NLP pipeline including **data preprocessing, text vectorization, machine learning model training, and evaluation** using Python.

## Objective
- Perform sentiment analysis on textual data
- Apply Natural Language Processing (NLP) techniques
- Convert text data into numerical features
- Train a machine learning model to classify sentiments
- Evaluate model performance using standard metrics

## 📂Dataset
The dataset contains restaurant reviews and their corresponding sentiment labels.

| Column | Description |
|------|-------------|
| Review | Customer review text |
| Liked | Sentiment label (1 = Positive, 0 = Negative) |

Dataset File:
```
Restaurant_Reviews.csv
```

## 🛠️Technologies Used

### Programming Language
- Python

### Development Environment
- Jupyter Notebook

### Python Libraries
- pandas
- numpy
- matplotlib
- scikit-learn
- nltk
  
## 🔄Project Workflow

### 1. Data Preprocessing
- Removing punctuation and special characters
- Converting text to lowercase
- Removing stopwords
- Applying stemming

### 2. Feature Extraction
Text data is converted into numerical form using the **Bag of Words technique**.

### 3. Model Training
- Splitting the dataset into training and testing sets
- Training a machine learning classifier to predict sentiment

### 4. Model Evaluation
The model performance is evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

## ▶️How to Run the Project

### 1. Clone the Repository
```
git clone https://github.com/yourusername/sentiment-analysis-nlp.git
```

### 2. Install Required Libraries
```
pip install -r requirements.txt
```

### 3. Run the Notebook
Open Jupyter Notebook and run:

```
sentiment_analysis.ipynb
```

---

## 📈Results
The trained model successfully predicts whether a restaurant review expresses **positive or negative sentiment** using NLP techniques.
