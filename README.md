**YouTube Comments Scraping and Sentiment Analysis**

01. I scraped comments from a YouTube video, uploaded by the channel named 'Veritasium', titled "This is why we can't have nice things". The goal of this project was to store the data collected in an organised manner, and perform EDA.

02. I divided the entire scope of the project into 5 parts. Part 1: Scraping comments from the YouTube Video, Part 2: Part 2: Sentiment Analysis of the comments, Part 3: Performing EDA on Positive comments, Part 4: Performing EDA on Negative comments, and Part 5: Analyzing the Emojis in the comments.

03. I used Chrome Driver and Selenium libraries to get to the YouTube page and scrape the comments. I stored the raw data in a DataFrame using Pandas library and performed EDA on it. I made wordclouds using the TextBlob library to understand how often the words in both positive and negative comments were repeated, and whether the kind of language that was used was child-friendly or not. Lastly, I plotted the count of each distinctive emoji using the Plotly library.
