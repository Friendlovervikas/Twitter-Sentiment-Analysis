# Twitter Sentiment Analysis

## About This Project

The **Twitter Sentiment Analysis** project analyzes the sentiment of tweets based on a user-provided search query (such as hashtags, keywords, or topics). The project uses **Python**, **Tweepy**, and **TextBlob** (or **VADER**) to fetch real-time tweets from Twitter and perform sentiment analysis to classify them as **positive**, **negative**, or **neutral**.

This project can be useful for understanding public opinion about specific topics, brands, or events. It provides insights into how people feel about a subject based on the tweets they post. You can use this tool for market research, brand monitoring, or social media analytics.

### Key Features:
- **Real-Time Tweet Extraction**: Fetch real-time tweets from Twitter using a search query.
- **Sentiment Analysis**: Classify each tweet's sentiment (positive, negative, or neutral) using **TextBlob** or **VADER**.
- **CSV Export**: Export the sentiment results (tweet text and sentiment classification) into a CSV file for easy analysis.
- **Command-Line Interface (CLI)**: Simple command-line interface to interact with the program and input search queries.

### Technologies Used:
- **Python**: The primary language for this project.
- **Tweepy**: A Python library for accessing the **Twitter API** and fetching tweets.
- **TextBlob** or **VADER**: Libraries for performing sentiment analysis.
- **pandas**: For data manipulation and exporting sentiment analysis results into CSV files.
- **.env**: Used to securely store Twitter API credentials.

---

### How It Works:

1. **Search Query Input**:  
   The user provides a keyword or hashtag they want to analyze.
   
2. **Fetch Tweets**:  
   The **Tweepy** library is used to access Twitter's API and fetch tweets related to the search query in real-time.

3. **Sentiment Classification**:  
   Each fetched tweet is processed using **TextBlob** or **VADER** to determine whether the sentiment of the tweet is **positive**, **negative**, or **neutral**.

4. **Export Results**:  
   The analysis results are saved to a CSV file containing the tweet text, sentiment score, and sentiment classification.

5. **Command-Line Interface**:  
   Users can interact with the program through the command line, providing a search query to fetch and analyze tweets.

---

### Getting Started

To get the project up and running on your local machine, follow the setup instructions below.

---

### Setup

#### **Prerequisites**

Ensure you have the following installed on your machine:
- **Python 3.x**: You need **Python 3** to run the script.
- **Twitter Developer Account**: You need to create a Twitter Developer account and obtain your API credentials (API Key, API Secret Key, Access Token, and Access Token Secret).

#### **Installation Steps**

1. **Clone the Repository**  
   Start by cloning the repository to your local machine:
   ```bash
   git clone https://github.com/friendlovervikas/twitter-sentiment-analysis.git
