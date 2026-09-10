# 🍽️ Restaurant Reviews Sentiment Analysis

This project performs **sentiment analysis on restaurant reviews** using Natural Language Processing (NLP) and machine learning techniques.

The project preprocesses customer reviews and classifies them into **Positive** or **Negative** sentiment.

## 📌 Project Overview

The goal of this project is to analyze restaurant reviews and determine whether a customer's experience is positive or negative.

The project includes implementations using three different machine learning algorithms:

* Logistic Regression
* Random Forest
* Support Vector Machine (SVM)

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Natural Language Toolkit (NLTK)
* Scikit-learn
* Matplotlib
* Seaborn

## 🔄 Project Workflow

1. Load the restaurant review dataset.
2. Clean and preprocess the review text.
3. Convert text to lowercase.
4. Remove non-alphabetic characters.
5. Remove English stopwords.
6. Apply Porter Stemming.
7. Convert text into numerical features using `CountVectorizer`.
8. Split the dataset into training and testing sets.
9. Train machine learning classification models.
10. Predict sentiment on the test data.
11. Evaluate model performance using accuracy, precision, recall, and a classification report.
12. Visualize the confusion matrix and sentiment data.

## 🤖 Machine Learning Models

### Logistic Regression

The Logistic Regression implementation uses `CountVectorizer` to convert the processed reviews into numerical features and trains a Logistic Regression classifier for sentiment prediction.

### Random Forest

A Random Forest classifier is used as another approach for classifying restaurant reviews into positive and negative sentiments.

### Support Vector Machine

The project also includes an SVM-based classifier for sentiment classification.

## 📊 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* Classification Report
* Confusion Matrix

## 📁 Project Structure

```text
Sentiment_Analysis_Restaurant_Reviews/
│
├── restaurant_reviews_logistic_regression.py
├── restaurant_reviews_randomforest.py
├── restaurant_reviews_svm_classifier.py
└── README.md
```

## ▶️ Running the Project

Clone the repository:

```bash
git clone https://github.com/RajuSreenu/Sentiment_Analysis_Restaurant_Reviews.git
```

Navigate to the project directory:

```bash
cd Sentiment_Analysis_Restaurant_Reviews
```

Install the required libraries:

```bash
pip install numpy pandas nltk scikit-learn matplotlib seaborn
```

Run any of the implementations:

```bash
python restaurant_reviews_logistic_regression.py
```

or

```bash
python restaurant_reviews_randomforest.py
```

or

```bash
python restaurant_reviews_svm_classifier.py
```

## 📈 Results

The project calculates accuracy, precision, recall, and generates a confusion matrix to evaluate the performance of the sentiment classification models.

## 🎯 Key Learning Outcomes

* Natural Language Processing
* Text preprocessing
* Feature extraction
* Sentiment classification
* Machine learning model training
* Model evaluation
* Data visualization
* Comparing different classification algorithms

## 👨‍💻 Author

**Raju Sreenu**

GitHub: https://github.com/RajuSreenu
