# ChatGPT Review Analysis – Sentiment Analysis Using Python

## Project Overview

This project focuses on analyzing customer reviews of ChatGPT using Python, Natural Language Processing (NLP), and data visualization techniques.

The objective is to understand customer satisfaction, identify positive and negative feedback patterns, analyze customer sentiment, and extract frequently mentioned keywords from user reviews.

The project uses sentiment analysis and text mining to transform unstructured customer reviews into meaningful insights.

## Objectives

- Analyze customer reviews and understand user satisfaction.
- Perform Exploratory Data Analysis (EDA) to identify review patterns.
- Calculate sentiment polarity and subjectivity.
- Classify reviews into Positive, Negative, and Neutral categories.
- Examine the relationship between customer ratings and sentiment.
- Extract frequently occurring keywords from positive and negative reviews.
- Visualize customer feedback using charts and word clouds.

## Tools & Technologies

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Google Colab | Development environment |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| TextBlob | Sentiment analysis |
| NLTK | Natural Language Processing |
| Scikit-learn | Keyword extraction |
| WordCloud | Word cloud visualization |

## Project Workflow

The project follows eight major steps:

### 1. Importing Libraries
Imported the required Python libraries for data manipulation, visualization, NLP, and sentiment analysis.

### 2. Loading the Dataset
Loaded the ChatGPT customer reviews dataset using Pandas.

### 3. Data Cleaning and Preprocessing
- Standardized column names.
- Identified and handled missing review values.
- Checked and removed duplicate records.
- Converted ratings into numeric format.
- Converted review dates into datetime format.

### 4. Exploratory Data Analysis (EDA)
Performed exploratory analysis to understand:
- Distribution of customer ratings.
- Average customer rating.
- Monthly review trends.
- Review length distribution.
- Average ratings over time.

### 5. Text Preprocessing and Sentiment Analysis
- Converted review text into lowercase.
- Removed URLs, special characters, and unnecessary spaces.
- Calculated sentiment polarity using TextBlob.
- Calculated subjectivity scores.
- Classified reviews into Positive, Negative, and Neutral categories.

### 6. Rating vs Sentiment Analysis
Analyzed the relationship between customer ratings and sentiment scores using:
- Average sentiment polarity by rating.
- Cross-tabulation of ratings and sentiment categories.
- Correlation analysis.
- Heatmap visualization.

### 7. Positive and Negative Review Analysis
Separated reviews based on customer ratings to examine positive and negative customer feedback.

### 8. Keyword Extraction and Text Analysis
- Extracted frequently occurring keywords from positive reviews.
- Extracted frequently occurring keywords from negative reviews.
- Generated separate word clouds to visualize frequently discussed topics.

## Key Concepts

**Sentiment Polarity:** Measures the emotional orientation of text, ranging from -1 (negative) to +1 (positive).

**Subjectivity:** Measures whether the text expresses personal opinions or factual information, ranging from 0 (objective) to 1 (subjective).

**Exploratory Data Analysis (EDA):** Helps identify patterns, trends, and relationships within the dataset.

**Keyword Extraction:** Identifies frequently occurring words to understand commonly discussed topics.

## Visualizations

The project includes the following visualizations:

- Customer Rating Distribution
- Monthly Customer Review Trends
- Review Length Distribution
- Average Customer Rating Over Time
- Customer Sentiment Distribution
- Sentiment Polarity Distribution
- Review Subjectivity Distribution
- Average Sentiment Polarity by Rating
- Ratings vs Sentiment Categories
- Correlation Heatmap
- Positive Review Word Cloud
- Negative Review Word Cloud

## Project Files

```text
ChatGPT-Review-Analysis/
│
├── ChatGPT_Analysis.ipynb
├── chatgpt_reviews (1).csv
├── ChatGPT_Review_Analysis_Final.csv
└── README.md
```

## How to Run the Project

1. Clone or download this GitHub repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload `ChatGPT_Analysis.ipynb`.
4. Upload the original customer reviews CSV dataset when prompted.
5. Run the notebook cells sequentially.
6. Explore the generated visualizations and sentiment analysis results.

## Limitations

- TextBlob may not accurately identify sarcasm or context-dependent expressions.
- Keyword frequency does not always indicate whether a feature is praised or criticized.
- Automated sentiment
