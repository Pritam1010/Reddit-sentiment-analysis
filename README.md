# 🔍 Reddit Sentiment Analysis App

This is a Python-based sentiment analysis app that uses NLP to analyze Reddit posts and comments in real time.

Built with **Streamlit**, **PRAW**, and **NLTK (VADER)**, the app provides insights into public sentiment based on recent Reddit discussions.

---

## 🚀 Features

- 📥 Fetches Reddit posts and top comments
- 🧠 Sentiment Analysis using VADER (Positive, Negative, Neutral)
- 🖥️ Interactive output via terminal or Streamlit UI
- 🔌 Easy to run and modify for your own use

---

## 🧰 Tech Stack

| Purpose            | Tool / Library       |
|--------------------|----------------------|
| Web App            | Streamlit            |
| NLP Engine         | NLTK (VADER)         |
| Reddit Integration | PRAW (Reddit API)    |
| Environment Config | python-dotenv        |

---

## 📦 Installation

### 1. Clone this repository

```bash
git clone https://github.com/your-username/reddit-sentiment-analysis.git
cd reddit-sentiment-analysis

pip install -r requirements.txt
python -m nltk.downloader vader_lexicon

streamlit run app.py
