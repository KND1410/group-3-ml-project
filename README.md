# 💬 Review Sentiment Analysis 

## 📌 Project Overview
This project implements a complete Natural Language Processing (NLP) pipeline to classify the sentiment of movie reviews as either Positive or Negative. Rather than relying solely on basic counting algorithms, this project explores and compares traditional One-Hot_encoding, Bag-of-Words and TF-IDF models against dense contextual neural word embeddings (Word2Vec) to address complex linguistic challenges such as sarcasm, negated context, and domain-specific vocabulary.

##  Dataset & Task

* **Dataset:** IMDb Movie Reviews Dataset (lakshmi25npathi on Kaggle) — 50,000 highly polarized movie reviews, featuring raw text string data and binary sentiment labels (positive/negative).
* **Task:** Classify the sentiment of each movie review into one of two categories — Positive or Negative — by converting raw text into mathematical representations to analyze semantic context, tone, and vocabulary.
* **Type:** Binary classification (2 classes). Baseline = one-hot-encoding, bag-of-words and TF-IDF Vectorization with Multinomial Naive Bayes / Logistic Regression; improved version utilizes custom 193-dimensional Word2Vec embeddings coupled with hyperparameter-tuned Logistic Regression.
* **Source:** https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

## 👥 Team Members
* **Nguyễn Minh Hoàng**: Project manager, Error analysis
* **Nguyễn Đăng Khôi**: Data
* **Nguyễn Xuân Dương**: Baseline model
* **Vũ Trần Nam Khánh**: Improvement

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Machine Learning:** Scikit-Learn (`LogisticRegression`, `MultinomialNB`)
* **NLP & Embeddings:** Gensim (`Word2Vec`)
* **Data Manipulation & Math:** Pandas, NumPy
* **Visualization:** Matplotlib (Confusion Matrices)

## ⚙️ How to Run
1. Requirement
    - Git
    - Python 3.13 or lower
2. Clone this repository.
```bash
git clone https://github.com/KND1410/group-3-ml-project.git
cd group-3-ml-project
```
3. Install library
```bash
pip install pandas numpy scikit-learn gensim matplotlib
```
4. Run the Jupyter Notebook cell-by-cell to view the training process, Grid Search outputs, and the final Error Analysis confusion matrices.

## 🤖 LLM Component

We used **Google Gemini** ( `gemini-2.5-flash` ) for one controlled step: *[Feature Engineering Helper / Error Analysis Assistant]*.

To run the LLM step yourself:

1. Get a free API key from [Google AI Studio](https://aistudio.google.com/)
2. Create a `.env` file:
```env
GEMINI_API=your_key_here
```
3. Install the client:
```bash
pip install google-genai
```
The exact prompt we used is documented in `LLM.ipynb` .

## 📊 Results & Model Comparison

| Model Architecture | Training Score | Testing Score | Train/Test Gap |
| :--- | :--- | :--- | :--- |
| **One-hot-encoding + Naive Bayes** | 84.52% | 84.33% | 0.19% |
| **One-hot-encoding + Logistic Regression** | 89.32% | 86.99% | 2.33% |
| **Bag-of-words + Naive Bayes** | 83.79% | 83.41% | 0.38% |
| **Bag-of-words + Logistic Regression** | 89.32% | 86.63% | 2.69% |
| **TF-IDF + Naive Bayes** | 84.77% | 84.29% | 0.48% |
| **TF-IDF + Logistic Regression** | 89.32% | 87.11% | 2.21% |
| **Word2Vec + Logistic Regression** | **91.28%** | **89.03%** | **Optimal Champion** |

## The AI assistant helped to do:
* Feature Engineering Helper
* Error Analysis Assistant

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
