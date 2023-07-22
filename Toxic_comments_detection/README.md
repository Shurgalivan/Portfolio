# Sentiment Analysis for "WikiShop" Project

## Stack Used:

- Python
- LightGBM (LGBMClassifier)
- Hugging Face Transformers (DistilBERT)
- Scikit-learn (CountVectorizer)
- Pandas 
- NumPy 


## Objectives:

The "Sentiment Analysis for WikiShop" project aims to develop a sentiment classification system for the online store "WikiShop." The system allows users to edit and enhance product descriptions, and the comments are classified as positive or negative based on their sentiment. This project explores different models, such as LGBMClassifier and DistilBERT, and various preprocessing techniques, including CountVectorizer, to achieve accurate sentiment classification.

## Findings

Key Findings:

- LGBMClassifier Outperforms DistilBERT:
The LGBMClassifier model, a gradient boosting framework, exhibited superior performance on the preprocessed text data using CountVectorizer. Its ability to handle high-dimensional and sparse feature spaces efficiently made it ideal for sentiment classification.
- Limited Data Affects DistilBERT Performance:
Training DistilBERT on a reduced dataset (5000 rows) likely impacted its ability to learn complex patterns effectively. As a result, it showed unsatisfactory results compared to LGBMClassifier.
 
By implementing this sentiment analysis system, "WikiShop" can enhance its user experience by fostering a positive and constructive environment for content creation and engagement.

For detailed analysis and code implementation, please refer to the [Jupyter Notebook](https://github.com/Shurgalivan/Portfolio/blob/main/Video%20Games%20Research/video_games_market.ipynb) provided in this repository.
