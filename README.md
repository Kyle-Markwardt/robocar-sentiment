# Robocar Sentiment

This project analyzes sentiment of NYT Articles on "Autonomous Driving" since 2016 and their impact on the stock prices of companies developing self-driving cars.

v1 used datasets from NYT API and Yahoo Finance.  Ultimately, the datasets in v1 were too small and all atttempted models failed to find a relationship between headline sentiment and sotck price movement, with any time lag.

It used a pre-trained model (sentence-transformers/all-MiniLM-L6-v2) to determine sentiment.

![Daily NYT driverless car headline sentimnet](URL or path to image)

