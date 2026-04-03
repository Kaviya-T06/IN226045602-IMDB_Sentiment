# IMDB Sentiment Analysis with DistilBERT

This project performs **sentiment analysis** on the IMDB movie reviews dataset using **Hugging Face Transformers** and **PyTorch**.  
The model classifies movie reviews as either **positive** or **negative**.

---

## Features

- Data cleaning and preprocessing
  - Removes HTML tags
  - Removes special characters and numbers
  - Converts text to lowercase
- Tokenization using **DistilBERT tokenizer**
- Training a **DistilBERT-based classifier**
- Model saving and loading
- Evaluation metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- Confusion matrix visualization
- Prediction on new text samples

---

## Requirements

| Library | Install Command |
|---------|----------------|
| Python 3.10+ | [Official Python site](https://www.python.org/) |
| Jupyter Notebook / Lab | `pip install notebook jupyterlab` |
| PyTorch | `pip install torch` |
| Transformers | `pip install transformers` |
| Scikit-learn | `pip install scikit-learn` |
| Matplotlib | `pip install matplotlib` |
| Seaborn (optional) | `pip install seaborn` |
| Pandas | `pip install pandas` |

