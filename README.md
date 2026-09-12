# 🎬 Movie Review Classification

## 📌 Overview

Movie Review Classification is a **Natural Language Processing (NLP)** project that predicts whether a movie review expresses a **Positive** or **Negative** sentiment.

The project demonstrates how textual data can be processed and converted into numerical representations that can be used by machine learning classification models.

---

## 🎯 Objective

The main objective of this project is to:

* Analyze movie review text.
* Preprocess and clean textual data.
* Convert text into numerical features.
* Train a machine learning classification model.
* Predict whether a review is **Positive** or **Negative**.

---

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Gensim
* Colab

---

## 🔄 Project Workflow

```text
Movie Reviews
      ↓
Data Cleaning
      ↓
Text Preprocessing
      ↓
Tokenization
      ↓
Stopword Removal
      ↓
Stemming / Lemmatization
      ↓
Feature Extraction
(Bag of Words / TF-IDF)
      ↓
Train-Test Split
      ↓
Machine Learning Model
      ↓
Prediction
      ↓
Positive / Negative
```

---

## 📝 NLP Preprocessing

The review text is processed before training the model.

The main preprocessing steps include:

1. **Lowercasing**
   Converts all text into lowercase.

2. **Tokenization**
   Splits a sentence into individual words.

3. **Stopword Removal**
   Removes commonly occurring words that may not provide useful information.

4. **Stemming / Lemmatization**
   Converts words into their root or base form.

5. **Text Vectorization**
   Converts text into numerical features using techniques such as:

   * Bag of Words (BoW)
   * TF-IDF

---

## 🤖 Machine Learning

After preprocessing, the reviews are converted into numerical vectors.

These vectors are used to train a classification model such as:

* Multinomial Naive Bayes
* Logistic Regression
* Random Forest

The trained model learns patterns associated with positive and negative reviews and uses them to classify new reviews.

---

## 📊 Evaluation

The model can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Example:

```text
              Precision    Recall    F1-Score

Negative         ...         ...        ...
Positive         ...         ...        ...

Accuracy                    ...
```

---

## 💡 Example

### Input

```text
"The movie was amazing and the acting was excellent."
```

### Output

```text
Positive
```

### Input

```text
"The movie was boring and the story was disappointing."
```

### Output

```text
Negative
```

---

## 📁 Project Structure

```text
Movie-Review-Classification/
│
├── Movie_Review_Classification.ipynb
├── README.md
├── dataset/
│   └── movie_reviews.csv
│
└── requirements.txt
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-repository-link>
```

### 2. Navigate to the project directory

```bash
cd Movie-Review-Classification
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Run the notebook cells sequentially to preprocess the data, train the model, and perform predictions.

---

## 🔮 Future Improvements

* Deploy the model using Streamlit.
* Add a web interface for entering reviews.
* Compare multiple NLP vectorization techniques.
* Compare different classification algorithms.
* Improve performance using hyperparameter tuning.
* Extend the system to classify multiple sentiment categories.

---

## 👩‍💻 Author

**Brindasree Chenna**

This project was developed as part of learning **Natural Language Processing and Machine Learning**.
