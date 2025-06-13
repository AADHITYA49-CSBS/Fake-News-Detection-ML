


Fake News Detection Using Machine Learning

📌 Project Overview
This project applies Natural Language Processing (NLP) techniques to classify fake vs. real news articles using TF-IDF vectorization and Logistic Regression. The goal is to enhance misinformation detection by leveraging machine learning.

📌 Dataset
Due to file size limitations, dataset files are hosted on Google Drive:
https://docs.google.com/spreadsheets/d/1IiCQC5DJMLprSSZbdkP0SWStN24B2GNSDfS5-tn7efk/edit?usp=drive_link
https://docs.google.com/spreadsheets/d/1GPuq3M7gARaiiTydlGbFykRE7O_PN-UVITxhpyTyNjA/edit?usp=drive_link

📌 Ensure both files are placed in your project directory before execution.

📌 Technologies & Libraries Used
Data Processing - Pandas, Numpy
Text Processing - NLTK, Regex
Machine Learning - Scikit-learn, TF-IDF Vectorizer
Visualization - Matplotlib, Seaborn
Development Environment - Google Colab

📌 Model Training & Evaluation

Metric	    Fake News (Label 0) 	Real News (Label 1)
Accuracy	    98.87%	                   -
Precision	    99%	                      99%
Recall	      99%	                      99%
F1-Score	    99%	                      99%

📌 TF-IDF ensures accurate feature extraction, improving classification efficiency.

📌 Future Enhancements

Feature	                            Improvement Area
Deep Learning	              Implement LSTMs or Transformers for enhanced accuracy
Dataset Expansion	          Include real-time news sources for better generalization
Error Analysis	            Investigate misclassified articles for fine-tuning








