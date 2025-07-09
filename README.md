## Stock Sentiment Analysis 
A real-time NLP application that scrapes Twitter for stock-related tweets (e.g., $AAPL, $TSLA), applies transformer-based models to classify sentiment, and generates actionable insights to assist investors and analysts in understanding public market sentiment.

#### Key Features
- Real-Time Scraping: Gathers live tweets mentioning stock symbols (e.g., $AAPL, $TSLA) via snscrape.
- Transformer-Based Sentiment Classification: Uses pre-trained models to classify tweets as Positive, Negative, or Neutral.
- Data Visualization: Displays frequency plots and sentiment distributions using matplotlib and seaborn.
- Market Sentiment Aggregation: Computes net sentiment scores for each stock to give high-level insights.
- Efficient Execution: Shows progress bars with tqdm and handles data efficiently using pandas.

 #### Tech Stack
- Languages: Python
- Libraries: transformers, snscrape, pandas, matplotlib, seaborn, tqdm
- Tools: Jupyter Notebook, Git, VS Code

#### How It Works
1. Input: Define the stock ticker and number of tweets to scrape.
2. Scraping: Tweets are pulled using snscrape with specific search queries.
3. Preprocessing: Tweets are cleaned, tokenized, and prepared for model inference.
4. Sentiment Inference: Transformer model (e.g., BERT) classifies each tweet's sentiment.
5. Aggregation & Visualization: Results are grouped, scored, and plotted to show sentiment trends.

#### Output
- Sentiment breakdown per stock (bar chart)
- Time-series plot of sentiment fluctuations
- Overall sentiment score: Bullish / Bearish / Neutral

####  Possible Extensions
- Deployment with Flask or Streamlit for real-time user interaction.
- Expansion to multi-lingual sentiment or topic modeling for broader market insights.

#### Conclusion
This project demonstrates how real-time financial sentiment can be extracted from social media using transformer-based NLP techniques. By translating public opinion into measurable signals, it empowers developers, investors, and analysts to make more informed, data-driven decisions.
