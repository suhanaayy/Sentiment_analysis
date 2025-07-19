# 🐦 Sentiment Analysis of Tweets

This project analyzes tweet sentiments and classifies them as **positive/neutral** or **negative (racist/sexist)** using natural language processing (NLP) and machine learning techniques.

---

## ⚙️ Setup Instructions

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/sentiment-analysis-tweets.git
cd sentiment-analysis-tweets
```

### Step 2: Create and Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### Step 3: Install Dependencies

```bash
pip install -r Requirements.txt
```

---

## 🧪 Methodology

### 1. Data Loading

- Loads training and testing tweet datasets.

### 2. Preprocessing

- Removes null values  
- Cleans tweets (punctuation, stopwords, symbols)  
- Tokenizes and stems words  
- Extracts hashtags  
- Adds tweet length as a feature  

### 3. EDA

- Visualizes class distribution  
- Plots most common words  
- Generates word clouds for sentiment  
- Analyzes hashtags for trends  

### 4. Feature Engineering

- `CountVectorizer` (Bag-of-Words)  
- `Word2Vec` embeddings from Gensim  

### 5. Model Building

Trains and evaluates:
- Logistic Regression  
- Decision Tree  
- Random Forest  

### 6. Evaluation

- Uses Accuracy, F1-score, and Confusion Matrix

---

## 📊 Results

| Model               | Accuracy  |
|--------------------|-----------|
| Random Forest       | 95.14%    |
| Logistic Regression | 94.05%    |
| Decision Tree       | 93.25%    |

✅ **Random Forest** outperformed other models in both accuracy and F1-score.

---

## 🔮 Future Scope

- Real-time tweet streaming and sentiment classification  
- Interactive dashboards to visualize trends  
- Support for multilingual sentiment analysis

---

## 💾 Requirements

```text
numpy==1.23.5  
pandas==1.5.3  
matplotlib==3.7.1  
seaborn==0.12.2  
scikit-learn==1.2.2  
nltk==3.8.1  
wordcloud==1.8.2  
gensim==4.3.1  
tqdm==4.64.1
```

---

## 📚 References

- https://scikit-learn.org/stable/  
- https://radimrehurek.com/gensim/models/word2vec.html  
- https://www.nltk.org/

---

## 🙌 Acknowledgement

This project was built to demonstrate NLP and ML-based sentiment classification of tweets. It provides a foundation for automating harmful content detection and public opinion analysis.
