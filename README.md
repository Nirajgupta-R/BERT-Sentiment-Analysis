# BERT Sentiment Analysis

A Deep Learning based Sentiment Analysis web application using **BERT (Bidirectional Encoder Representations from Transformers)** and **Flask**.

The application classifies a given text/review as **Positive** or **Negative** and also provides the model's confidence score.

## 🚀 Features

- BERT-based sentiment classification
- Positive / Negative prediction
- Confidence score
- Flask backend
- HTML/CSS frontend
- GPU support during model training
- Easy-to-use web interface

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- BERT
- Flask
- HTML
- CSS
- Numpy
- Pandas
- Scikit-learn

## 📊 Dataset

The project uses a labeled sentiment dataset containing reviews classified into:

- `0` → Negative
- `1` → Positive

The dataset is divided into:

- Training Set
- Validation Set
- Test Set

## 🧠 Model

The project uses:

**BERT Base Uncased**

The pre-trained BERT model is fine-tuned for binary sentiment classification.

```text
Input Review
     ↓
BERT Tokenizer
     ↓
BERT Model
     ↓
Classification Layer
     ↓
Positive / Negative
     ↓
Confidence Score
