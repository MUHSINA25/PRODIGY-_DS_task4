# PRODIGY-_DS_task4
# Sentiment Analysis Internship Report

## Project Title: Sentiment Analysis on Social Media Data

## Overview
This project focuses on analyzing and visualizing sentiment patterns in social media data to gain insights into public opinion and attitudes towards specific topics or brands. By leveraging Natural Language Processing (NLP) techniques and machine learning models, we explore how users engage with gaming and technology-related content across various platforms.

---

## Problem Statement
Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands. The goal is to uncover emotional trends, explore topic-specific sentiment distribution, and classify sentiments using machine learning algorithms.

---

## Dataset
The dataset contains the following attributes:
- **ID**: Unique identifier for each entry.
- **Topic**: The main subject of the post (e.g., gaming topics).
- **Sentiment**: The sentiment label (Positive, Negative, Neutral, Irrelevant).
- **Text**: The raw social media post content.

### Preprocessing Steps
1. Removed missing values in the `Text` and `Sentiment` columns.
2. Applied text cleaning to remove noise, including special characters, URLs, and extra whitespace.
3. Tokenized and normalized the text.
4. Created a `cleaned_text` column containing processed textual data.

---

## Sentiment Distribution Insights
- **Negative Sentiment**: Highest frequency with ~22,000 mentions.
- **Positive Sentiment**: Close second at ~20,000 mentions.
- **Neutral Sentiment**: Falls in the mid-range with ~18,000 mentions.
- **Irrelevant Content**: Lowest frequency at ~13,000 mentions.

This distribution highlights that users predominantly express strong emotional opinions over neutral or irrelevant content.

---

## Visualizations
1. **Sentiment Distribution Graph**:
   - Reveals the breakdown of sentiments across the dataset.
2. **Word Clouds**:
   - Positive Sentiment: Terms indicating enjoyment and appreciation.
   - Negative Sentiment: Words reflecting frustration or criticism.
   - Neutral Sentiment: Industry-related descriptive terms.

---

## Sentiment Analysis Model
### Logistic Regression Results
- **Accuracy**: 69%
- **Precision and Recall**:
  - **Negative Sentiment**: Precision = 0.73, Recall = 0.77
  - **Positive Sentiment**: Precision = 0.65, Recall = 0.76
- **Weighted Average F1-Score**: 0.69

The model demonstrates moderate performance, with the highest accuracy in identifying negative sentiments.

### Key Observations
- The dataset is balanced, with a consistent distribution of sentiment categories.
- Negative sentiment classification achieves the highest precision and recall scores.

---

## Conclusion
The analysis provided valuable insights into sentiment trends, emotional responses, and public attitudes in gaming and technology-related discussions. The sentiment classification model achieved satisfactory accuracy, showcasing its potential for understanding social media sentiment patterns.

---

## Tools and Technologies
- **Python**: For data preprocessing, NLP, and modeling.
- **Libraries**: Pandas, NLTK, Scikit-learn, Matplotlib, Seaborn.
- **Visualization Tools**: Word clouds and sentiment graphs for data insights.


