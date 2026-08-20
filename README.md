# ChatGPT Review Analysis

## Project Overview

This project analyzes customer reviews of ChatGPT using Python and Natural Language Processing (NLP) techniques.

The objective is to understand user sentiment, identify frequently mentioned topics, and extract meaningful insights from customer feedback.

## Objectives

- Understand the overall sentiment of ChatGPT users
- Analyze customer ratings
- Calculate sentiment polarity and subjectivity
- Categorize reviews into positive, negative, and neutral sentiment
- Identify frequently mentioned keywords
- Analyze sentiment trends over time
- Generate actionable business recommendations

## Dataset

The dataset contains customer reviews of ChatGPT with the following fields:

- Review ID
- Review
- Ratings
- Review Date

The dataset initially contained 196,727 records.

## Data Cleaning

The following preprocessing steps were performed:

- Standardized column names
- Converted review dates to datetime format
- Converted ratings to numeric format
- Handled missing reviews
- Checked for duplicate records
- Removed 2,511 completely duplicated rows
- Created a review length feature

After removing exact duplicate rows, the dataset contained 194,216 records.

## Exploratory Data Analysis

The analysis includes:

- Rating distribution
- Review length distribution
- Sentiment distribution
- Text analysis
- Sentiment trends over time

## Sentiment Analysis

TextBlob was used to calculate:

### Polarity

Polarity measures whether a review expresses positive or negative sentiment.

The score ranges from -1 to +1.

### Subjectivity

Subjectivity measures whether a review is more opinion-based or objective.

The score ranges from 0 to 1.

Reviews were categorized as:

- Positive
- Neutral
- Negative

## Text Analysis

Positive reviews were analyzed to identify frequently occurring words.

Some frequently occurring positive terms included:

- good
- best
- nice
- great
- helpful
- amazing
- love
- useful
- ChatGPT

## Sentiment Over Time

Monthly average polarity was calculated to understand how the sentiment expressed in reviews changed over time.

The analysis showed an overall positive trend in average sentiment during the period analyzed.

## Key Insights

- Users frequently expressed positive opinions about ChatGPT.
- Words such as "good", "great", "helpful", and "useful" appeared frequently in positive reviews.
- Sentiment remained positive throughout the period shown in the monthly analysis.
- Text analysis provides additional information beyond numerical ratings.

## Business Recommendations

1. Continue improving features associated with positive user experiences.
2. Analyze recurring negative feedback to identify product pain points.
3. Monitor customer sentiment alongside numerical ratings.
4. Track sentiment trends over time.
5. Use customer feedback to prioritize future product improvements.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TextBlob
- Regular Expressions
- WordCloud
- Jupyter Notebook / Google Colab

## Conclusion

This project demonstrates how Python and NLP can be used to transform unstructured customer reviews into meaningful insights.

By combining ratings, sentiment analysis, subjectivity, keyword analysis, and time-based analysis, the project provides a better understanding of customer experiences with ChatGPT.
