**Project Overview:**
This project focused on building and evaluating machine learning models to perform sentiment
analysis on text data. The goal was to classify text, movie reviews, in this case as positive 
or negative by applying natural language processing techniques and supervised learning models.

This project demonstrates the NLP pipeline, from text preprocessing to model evaluation and 
interpretation, with a strong emphasis on clear visualization and explainability.

**Problem Statement:**
Understanding sentiment in text data is crucial for applications such as:
Customer feedback analysis, social media monitoring, and product brand sentiment tracking.

This project aims to predict sentiment accurately using classical machine learning approaches
and compare their performance.
**
Dataset:**
Source: Movie review dataset
Target variable: Sentiment (Positive/Negative)
Input: Raw text reviews

**Methodology:**
1. Text Preprocessing
   - Lowercasing
   - Removing punctuation and stopwords
   - Tokenisation
   - TF-IDF vectorisation
2. Models Implemented
   - Logistic Regression
   - Naive Bayes
   - Random Forest
3. Model Evaluation
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrices
   - ROC-AUC Curves

**Key Results:**
- Logistic Regression and Naive Bayes performed strongly on text data
- ROC-AUC analysis provided insight into classification trade-offs
- Visual diagnostics were used to compare model behavior and errors

**Visualizations:**
- Confusion matrices
- Model comparison bar charts
- ROC-AUC curves
These were used to communicate model performance and insights

**Project Walkthrough:**
A walkthrough of this project is available here: https://youtu.be/8LJB9mfMAlg

**Tools and Libraries:**
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

Future Improvements
- Experiment with word embeddings (Word2Vec, GloVE)
- Apply deep learning models (LSTM, Transformers)
- Extend to multi-class sentiment classification
- Add explainability using SHAP values
