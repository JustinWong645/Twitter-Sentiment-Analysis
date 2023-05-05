# Twitter-Sentiment-Analysis

## About 
This is my contribution for [Stock Prediction Mini-Project](https://github.com/CodeLutetium/SC1015-Stock-Predictor/blob/main/stock_prediction.ipynb) for SC1015 (Introduction to Data Science and Artificial Intelligence) which uses 2 datasets, the **Yahoo Finance AAPL Stock Price** data, and **Twitter Tweets** containing 'AAPL' or general stock market ticker symbols from **2015 to 2019**. I am primarily interested in how people sentiment affect stock prices.

##Model used
Sentiment Analysis
    - To Obtain Sentiment
        - **Valence Aware Dictionary and Sentiment Reasoner**
    - To Classify Rise or Fall
        - Linear Discriminant Analysis
        - **Random Forest Classifier**
        - Logistic Regression
        
##Conclusion
Random Forest Classifier proved to be the most reliable model with 56% accuracy. Linear Discriminant Analysis and Logistic Regression proved to have lower accuracy or biasness to a certain class.

##What can I learn from this project
- Data extraction from a large dataset.
- Data cleaning techniques using python's pandas library.
- Sentiment Analysis using VADER.
- Selection of which sentiment variable is best to use.
- A highly speculative crowd online proved it hard to use people's sentiments to come up with highly accurate prediction.
- Sentiment analysis is best used with other indicators to help investors come up with an informed decision.

##Possible Improvements
I can use different avenue to collect sentiment data, such as news articles and other popular social media websites or applications.
