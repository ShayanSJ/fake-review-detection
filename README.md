# Fake Review Detection Using Machine Learning

<img width="1280" height="714" alt="image" src="https://github.com/user-attachments/assets/b809a7d0-ddf2-4c28-9bb6-711a1ed13735" />



## Overview
This project detects fake (deceptive) reviews using classical machine learning techniques.
It was developed and executed in **Google Colab**, and is suitable for local execution as well.

Two models are trained and evaluated:
- Logistic Regression (TF-IDF features)
- Multinomial Naive Bayes (TF-IDF features)

The project includes preprocessing, model training, evaluation, and basic error analysis.

## Dataset
The dataset consists of labeled text reviews:
- **label**: `1` = fake review, `0` = genuine review
- **text**: review content

> Note: Ensure the dataset file is available locally or uploaded to Colab before running the notebook.

## Project Structure
```
fake-review-detection/
│
├── fake_review_detection.ipynb   # Main notebook
├── README.md                     # Project documentation
├── requirements.txt              # Python dependencies
└── .gitignore                    # (Recommended)
```

## Installation (Local)
```bash
pip install -r requirements.txt
```

## Running the Notebook
- Open `fake_review_detection.ipynb` in Jupyter Notebook or Google Colab
- Run cells sequentially from top to bottom

## Models & Techniques
- Text preprocessing (regex cleaning, stopword removal, lemmatization)
- TF-IDF vectorization
- Logistic Regression with hyperparameter tuning
- Multinomial Naive Bayes
- Model comparison using precision, recall, F1-score

## Results
Logistic Regression achieved better overall performance compared to Naive Bayes on this dataset.

## Optional UI
The notebook includes optional code for:
- Streamlit
- Gradio

These are **not required** for model training and can be ignored or removed if deploying only the ML pipeline.

## Future Improvements
- Deep learning models (LSTM, BERT)
- Larger and more diverse datasets
- Deployment as a web API

## Author
Your Name
