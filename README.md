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
### Prerequisites

