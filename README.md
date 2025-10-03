# PySpark Real-Time News Sentiment Analysis

A comprehensive real-time news sentiment analysis system built with Apache Spark that scrapes Indian news sources, performs sentiment analysis using multiple NLP libraries, and provides interactive dashboards for insights visualization.

##  Project Overview

This project implements a complete data pipeline for real-time news sentiment analysis focusing on Indian news sources. It combines web scraping, natural language processing, distributed computing with PySpark, and data visualization to provide actionable insights from news sentiment trends.

### Key Features

- **Real-time News Scraping**: Ethical RSS feed scraping from 8+ major Indian news sources
- **Dual Sentiment Analysis**: Combines TextBlob and VADER sentiment analyzers for robust results
- **PySpark Integration**: Leverages distributed computing for scalable data processing
- **Interactive Dashboard**: Real-time visualization with matplotlib, seaborn, and plotly
- **Relevance scoring**: Custom algorithm to prioritize important news articles
- **Comprehensive Analytics**: Source-wise sentiment distribution, hourly trends, and statistical insights

##  Technologies Used

- **Apache Spark (PySpark)**: Distributed data processing and analytics
- **Python Libraries**: TextBlob, NLTK (VADER), BeautifulSoup4, Feedparser
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Web Scraping**: Requests, Beautiful Soup, RSS parsing
- **Data Processing**: Pandas, NumPy

##  Data Sources

The system scrapes news from the following Indian news sources:
- Times of India
- The Hindu
- Indian Express
- NDTV
- Economic Times
- News18
- Zee News
- Hindustan Times

##  Getting Started
### Prerequisites

Python 3.7+
Java 8+ (for Spark)

### Installation

1. Clone the repository:
https://github.com/T4SKM4ST3R69/spark-streaming-sentiment-dashboard.git


2. Install required packages:
pip install pyspark findspark textblob nltk beautifulsoup4 requests
pip install matplotlib seaborn plotly pandas wordcloud transformers torch
pip install newspaper3k feedparser lxml fake-useragen

3. Download NLTK data:
import nltk
nltk.download('punkt')
nltk.download('vader_lexicon')
nltk.download('stopwords')


### Quick Start

1. **Initialize Spark Session**:
   Run the notebook cells to set up PySpark environment

2. **Configure News Sources**:
   Modify the `NEWS_SOURCES` dictionary to add/remove news sources

3. **Start Real-time Analysis**:
   Execute the main processing function:

4. **View Dashboard**:
The system will automatically generate and update visualizations every cycle

## Key Metrics & Analytics

The system provides comprehensive analytics including:

- **Sentiment Distribution**: Overall positive/negative/neutral sentiment breakdown
- **Source Analysis**: Sentiment trends by news source
- **Temporal Patterns**: Hourly sentiment trends
- **Relevance Scoring**: Custom algorithm prioritizing important news
- **Statistical Insights**: Average sentiment scores, standard deviation, extremes

## Configuration

### Scraping Parameters
- **Scraping Interval**: 10 seconds (configurable)
- **Articles per Source**: 5 per cycle (adjustable)
- **Data Retention**: Last 500 articles kept in memory
- **Crawl Delay**: Respects robots.txt (2-5 seconds)

### Sentiment Analysis
- **TextBlob**: Provides polarity (-1 to 1) and subjectivity (0 to 1)
- **VADER**: Compound sentiment score (-1 to 1)
- **Combined Score**: Average of both analyzers for final classification

## Sample Results

The system generates various visualizations:
- Sentiment distribution pie charts
- Source vs sentiment heatmaps
- Hourly trend analysis
- Relevance vs sentiment scatter plots
- Source performance comparisons

## Project Structure

├── Pyspark.ipynb  
├── README.md 
└── requirements.txt 
