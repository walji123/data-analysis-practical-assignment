# Social Media Engagement Analysis

## Overview

This project analyzes engagement patterns across social media platforms using a dataset of posts containing likes, comments, shares, post type, platform, and sentiment.

The goal is to understand what factors influence engagement and identify patterns across different platforms and content types.

---

## Key Question

What factors drive social media engagement across platforms and content types?

---

## Dataset Description

The dataset contains 100 social media posts with the following features:

- `post_id`: Unique identifier for each post  
- `platform`: Social media platform (Facebook, Instagram, Twitter)  
- `post_type`: Type of content (image, video, poll, carousel, text)  
- `post_time`: Timestamp of post  
- `likes`: Number of likes  
- `comments`: Number of comments  
- `shares`: Number of shares  
- `post_day`: Day of the week posted  
- `sentiment_score`: Sentiment label (positive, neutral, negative)

---

## Methods Used

The analysis was conducted using Python and includes:

- Data loading and inspection
- Data cleaning and formatting
- Exploratory Data Analysis (EDA)
- Group-based aggregation
- Descriptive statistics
- Feature engineering (engagement metric)
- Data visualization using Matplotlib

---

## Engagement Metric

A custom engagement metric was created to measure total user interaction:

\[
Engagement = Likes + Comments + Shares
\]

---

## Key Insights

- Facebook video posts dominate the highest-liked content, suggesting strong performance for video content on Facebook.
- Instagram shows the highest average shares, indicating stronger content distribution behavior.
- Poll posts achieve the highest average engagement, suggesting interactive content drives stronger user participation.

---

## Visualizations

The project includes:
- Average likes by platform (bar chart)
- Distribution of likes (histogram)

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib

---

## Project Structure
