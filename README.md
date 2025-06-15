# Movie Reviews - Sentiment Classification

This notebook explores sentiment classification using the **NLTK Movie Reviews Corpus**, aiming to categorise reviews as positive or negative. The project involves data preprocessing, feature engineering, model training with Logistic Regression, and evaluation of standard classification metrics.

This project was developed as part of my data science learning journey.

**Dataset: nltk.corpus.movie_reviews**
---

## Project Goals

- Understand and preprocess raw text data.
- Extract meaningful features manually and automatically.
- Train and evaluate a logistic regression classifier.
- Visualize sentiment distribution in the dataset.

---

## Techniques Used

- Tokenization, lemmatization, and stopword removal
- Feature extraction using bag-of-words and custom patterns
- Logistic Regression for classification
- Evaluation using accuracy, precision, recall, and F1-score

---

## Libraries Used

- `nltk`
- `scikit-learn`
- `matplotlib`
- `contractions`
- `emoji`
- `textstat`

---

## Sample Output

- **Accuracy Score (on Dev Set)**: ~ 0.84
- **Classification Report (Dev Set)**:
- 
               precision    recall  f1-score   support

         neg       0.82      0.87      0.84       199
         pos       0.86      0.81      0.83       201
    accuracy       -         -         0.84       400
   macro avg       0.84      0.84      0.84       400
weighted avg       0.84      0.84      0.84       400


