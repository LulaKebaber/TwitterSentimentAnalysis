# Airline Review Sentiment Analysis (ARSA)

## 📌 Project Overview
This project focuses on **multi-class single-label sentiment analysis** of Twitter airline reviews.  
The task is to classify tweets into **positive**, **neutral**, or **negative** categories, enabling deeper understanding of customer feedback in the aviation industry.

The work was implemented in the Jupyter Notebook [`ARSA_FINAL.ipynb`](./ARSA_FINAL.ipynb).

---

## ✨ Features
- Preprocessing of raw text data (cleaning, tokenization, normalization).
- Exploratory Data Analysis (EDA) with visualizations.
- Training and evaluation of sentiment classification models.
- Comparison of multiple approaches for performance benchmarking.
- Evaluation using metrics such as **accuracy, precision, recall, F1-score, and confusion matrix**.

---

## 📂 Dataset
- **Source**: [Twitter US Airline Sentiment Dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)  
- **Description**: Contains tweets labeled as `positive`, `neutral`, or `negative`.

| Column | Description |
|--------|-------------|
| `text` | Raw tweet text |
| `airline_sentiment` | Sentiment label (`positive`, `neutral`, `negative`) |
| Other metadata | Airline name, tweet info (not always used) |

---

## ⚙️ Installation
Clone the repository and install the dependencies:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
