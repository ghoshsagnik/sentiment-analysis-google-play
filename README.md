# Sentiment Analysis for Google Play Reviews

## Problem Statement
Manually analyzing Google Play Store reviews is inefficient. This project automates sentiment analysis to help users, developers, and marketers extract insights on app performance and user satisfaction.

## Project Overview
This application consists of two components:

### 1. Backend (Python + Flask)
- **Technologies**: Flask, transformers, google-play-scraper, pyngrok
- **Features**:
  - Extracts reviews from Google Play Store using the app URL.
  - Performs sentiment analysis using Sentiment-RoBERTa.
  - Provides a decision based on sentiment percentages:
    - **Positive ≥ 70%**: Recommended.
    - **50% - 70%**: Good, but depends on user preference.
    - **40% - 50%**: Mixed feedback.
    - **Positive < 40%**: Likely has issues.
- **Process**:
  - Extract app ID → Fetch reviews → Preprocess → Analyze sentiment → Return insights.

### 2. Frontend (HTML + JavaScript)
- **Features**:
  - Input field for Google Play Store URL.
  - Buttons to fetch reviews and perform sentiment analysis.
  - Dynamically displays reviews, sentiment percentages, and recommendations.
  - Uses Fetch API to communicate with Flask backend.

## Strengths
- Seamless backend-frontend integration.
- High-accuracy Sentiment-RoBERTa model.
- Real-time insights for developers and marketers.
- Clear decision-making framework.

## Weaknesses
- **Google Play Store dependency**: API changes may impact data retrieval.
- **Binary sentiment classification**: No neutral/mixed sentiment detection.
- **Performance limitations**: Large datasets may slow down processing.
- **Limited to English reviews**.
- **Ngrok dependency**: Free version has dynamic URLs.

## Applications
- **App Developers**: Monitor user feedback for updates.
- **App Reviewers**: Analyze app performance for content.
- **Marketing Teams**: Assess public reception for strategy.

## Conclusion
This project leverages ML, web scraping, and web development to automate review sentiment analysis. Future improvements may include scalability enhancements and multilingual support.

## Important Note
Kindly read the Instructions to run.md before doing any coding.
