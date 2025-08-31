# Prodigy-Task4
Analyzed and visualized sentiment patterns in Twitter data to understand public opinion and attitudes toward brands and topics. Each tweet is classified as Positive, Negative, or Neutral using a Logistic Regression classifier.
📌 Project Overview

This project focuses on analyzing and visualizing sentiment patterns in social media text data.
The goal is to understand public opinion and attitudes toward topics or brands using NLP techniques.

I used the Twitter Training Dataset provided by Prodigy InfoTech for the internship task.

📂 Dataset

Source: Twitter Training Dataset

The dataset contains tweets labeled with sentiment categories like Positive, Negative, Neutral, and Irrelevant.

⚙️ Steps Performed

Data Cleaning

Removed missing values and irrelevant entries.

Standardized text (lowercasing, removing special characters, etc.).

Exploratory Data Analysis (EDA)

Visualized sentiment distribution.

Checked for common words in positive vs. negative tweets.

Sentiment Analysis

Implemented sentiment classification using VADER Sentiment Analyzer.

Compared sentiment scores with labeled data.

Visualization

Plotted bar charts and word clouds for each sentiment class.

Generated insights into sentiment patterns.

📊 Tools & Libraries Used

Python

Pandas & NumPy → Data Cleaning

Matplotlib & Seaborn → Visualization

NLTK (VADER) / TextBlob → Sentiment Analysis

WordCloud → Text Visualization

🔍 Key Insights

Most tweets were labeled as Positive or Negative, with fewer Neutral ones.

Certain keywords and hashtags were strongly associated with sentiment categories.

VADER performed well in aligning with labeled sentiments.
