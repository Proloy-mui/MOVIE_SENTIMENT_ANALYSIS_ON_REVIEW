# MOVIE_SENTIMENT_ANALYSIS_ON_REVIEW
Sentiment analysis model for movie reviews using ML techniques like logistic regression and SVM. It classifies reviews as positive or negative, with preprocessing, training, and evaluation steps. Helps studios and platforms understand audience sentiment.
##  Overview

The main objective is to use sentiment analysis techniques to understand how audiences feel about movies. This is done by training models like **Logistic Regression** and **Support Vector Machines (SVM)** on review data from sources such as **IMDb** and **Rotten Tomatoes**.

##  Features

- Text data preprocessing (cleaning, normalization)
- Model training using logistic regression & SVM
- Evaluation using accuracy and F1-score
- Predictive system for review sentiment

##  Dataset

- Collected from IMDb or Rotten Tomatoes  
- Includes both positive and negative reviews

##  Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK / SpaCy (for preprocessing)
- Jupyter Notebook

##  Model Evaluation

Models are evaluated using:
- **Accuracy**
- **F1-Score**
- **Confusion Matrix**

##  Deployment (Optional)

The trained model can be deployed via a simple Flask or Streamlit interface to demonstrate real-time sentiment classification.

##  Use Cases

- Help studios understand public response
- Support review platforms with automatic tagging
- Provide feedback loops for movie makers

##  How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook movie_sentiment_analysis.ipynb
   ```

##  Requirements

Create a `requirements.txt` with:
```
scikit-learn
pandas
numpy
nltk
jupyter
```

##  License

MIT License
