IMDB Sentiment Analysis with DistilBERT

This project performs sentiment analysis on the IMDB movie reviews dataset using Hugging Face Transformers and PyTorch. The model classifies movie reviews as either positive or negative.

Features
Data cleaning and preprocessing (removes HTML tags, special characters, and converts text to lowercase)
Tokenization using DistilBERT tokenizer
Training a DistilBERT-based classifier
Saving and loading model & tokenizer
Evaluation with metrics: Accuracy, Precision, Recall, F1 Score
Confusion matrix visualization
Prediction on new text samples
Requirements
Python 3.10+
Jupyter Notebook / JupyterLab
PyTorch
Transformers (pip install transformers)
Scikit-learn (pip install scikit-learn)
Matplotlib (pip install matplotlib)
Seaborn (pip install seaborn) (optional for better confusion matrix plots)
Pandas (pip install pandas)
