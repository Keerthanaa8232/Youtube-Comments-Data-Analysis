# 🎥 YOUTUBE-COMMENTS-DATA-ANALYSIS

### 🧾 Overview

This project analyzes YouTube comments to extract meaningful insights about viewer sentiments, frequently used words, and emoji patterns.
The dataset contains thousands of user comments from YouTube videos, and the analysis aims to understand user engagement and sentiment distribution.
Through techniques like sentiment analysis, text preprocessing, word cloud visualization, and emoji sentiment detection, this project provides insights into how audiences react to content on YouTube.
Using VADER (from NLTK) and TextBlob, the project evaluates emotional tone in comments — whether positive, neutral, or negative — and supports findings with visual insights like word clouds and emoji sentiment plots.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🧰 Tools & Technologies Used

Python
Libraries:
- Pandas, NumPy – Data processing
- Matplotlib, Seaborn, WordCloud – Visualization
- TextBlob, NLTK (VADER) – Sentiment Analysis
- emoji – Emoji extraction and sentiment mapping
- re – Text cleaning and preprocessing

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 📊 Project Workflow
 1. Data Collection
    Used a pre-downloaded YouTube comments dataset (UScomments.csv).
 2. Data Cleaning & Preprocessing
    Removed duplicates and null values , Converted timestamps and formatted text, Removed links, tags, and unnecessary symbols.
 3. Sentiment Analysis
    Used TextBlob to classify comments as Positive, Negative, or Neutral, Calculated polarity and subjectivity scores for each comment.
 4. Word Cloud Analysis
    Generated a WordCloud of most frequently used words in YouTube comments, Visualized words contributing most to positive/negative sentiments.
 5. Emoji Analysis
    Extracted emojis and counted their frequencies, Visualized emoji sentiment trends (e.g., 😂, 😍, 😢, 😡).

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 📈 Key Insights

- Most YouTube comments were positive, reflecting high audience engagement and appreciation.
- Common words included “awesome,” “love,” “great,” “cool,” indicating strong positive feedback.
- The most used emojis were 😂, ❤️, and 🔥, suggesting humor and enthusiasm dominate the comment tone.
- Negative sentiments were mostly tied to technical issues or controversial topics.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 📂 Directory Structure
YouTube-Data-Analysis/
│
├── 📘 README.md                     # Project documentation
├── 📓 Youtube_data_analysis.ipynb   # Main analysis notebook
├── 📁 data/
│   └── UScomments.csv               # YouTube comments dataset
├── 📁 visuals/
│   ├── sentiment_distribution.png
│   ├── wordcloud.png
│   └── emoji_analysis.png
└── 📄 requirements.txt     

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 📚 Learning Outcomes

- Learned text preprocessing and cleaning techniques
- Performed sentiment and emoji-based text analysis
- Created visual storytelling from unstructured data
- Strengthened understanding of real-world text analytics

    
