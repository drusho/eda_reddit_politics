# Exploratory Data Analysis of Reddit's r/politics


## Project Goals


This notebook will focus on 'Hot' subreddit tab posts due to their focus on upvotes and recent comments.  Data from /r/politics will be scrapped using python library _Praw_.  Analysis will include determining top posts for this subreddit and understanding what factors contributed to their ranking beyond most upvotes and comments.  Such as the correlation between comments and points, word frequency and semantic analysis of post titles

<br>
<br>

## Summary of Results

### __Correlation of Post Score and Number of Comments__

<img src="https://raw.githubusercontent.com/drusho/eda_reddit_politics/main/reports/figures/Correlation%20of%20Dataframe%20(Heatmap).png" width="500"/>

A heatmap that was ran through Seaborn showed there was a very positive correlation between the number of comments and the score of a posts (0.89).

<br>
<br>

#### __Word Frequency of Post Titles__

<img src="https://raw.githubusercontent.com/drusho/eda_reddit_politics/main/reports/figures/Word%20Frequency%20of%20Post%20Titles%20(Wordcloud).png" width="500"/>

Word frequency showed that _Biden_ and _Trump_ were the most popular key words, followed by _GOP_.

<br>
<br>

#### __Sentiment Analysis__
<img src="https://raw.githubusercontent.com/drusho/eda_reddit_politics/main/reports/figures/Sentiment%20of%20Post%20Titles%20(Histogram%20Plot).png" width="500">

The majority of posts in /r/politics were found be _neutral_, followed by _negative_.





