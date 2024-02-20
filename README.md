# WebSraping_Amazon_Product_Review
This project scrapes Amazon product reviews using web scraping techniques and analyzes the sentiment expressed in the reviews. It extracts reviews of a specific product from the Amazon website, cleans the text data, performs sentiment analysis, and visualizes the sentiment distribution.
## Features
- Web scraping of Amazon product reviews using BeautifulSoup and requests libraries.
- Data cleaning to preprocess the text data for analysis.
- Sentiment analysis using the TextBlob library to classify reviews as positive, negative, or neutral.
- Visualization of sentiment distribution using matplotlib.

## Usage
1. Run the `amazon_reviews_scraper.py` script to scrape Amazon product reviews and store them in a CSV file.
2. Run the `analyze_sentiment.py` script to perform sentiment analysis on the scraped reviews and visualize the sentiment distribution.

## Requirements
- Python
- BeautifulSoup
- requests
- pandas
- nltk
- TextBlob
- matplotlib
