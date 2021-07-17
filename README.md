# Data Analysis of Reddit's /r/politics
##### _Using Praw to Access API Data from Reddit_

<br> 

<img src="https://raw.githubusercontent.com/drusho/eda_reddit_politics/main/assets/reddit_politics.jpg" width="500">

<br>
<br>

## Project Links
---

1. [Blog Post: "Data Analysis of Reddit's /r/Politics"](https://drusho.github.io/api/nlp/pandas/plotly/texthero/praw/reddit/2021/07/05/reddit-politics-eda.html)
2. [Google Colab Notebook](https://colab.research.google.com/drive/1agUoLToktaw5SvuUzPnNigftivS_qLmt?usp=sharing)

<br>
<br>

## Project Goals
---

The purpose of this project was to practice using APIs to scrape data from a website. The website Reddit was chosen because it is one of the visited websites on the internet.  Data from the subreddit /r/politics was scrapped using the python library _Praw_.  This subreddit was chosen due to it's active userbase.  Analysis included determining top posts for this subreddit and understanding what factors contributed to their ranking beyond most upvotes and comments.  

Additional goals for the project included:

    Finding the top posts by score/upvotes
    Determining if a high score correlates with a high number of comments
    Discover the popular words used in all post titles
    Semantics analysis of posts and determine if they are negative, positive, or neutral?


<br>
<br>

## Summary of Results
---
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

<br>
<br> 

## Social Links

[<img src="https://img.shields.io/badge/Github_Blog-%23ffa64d.svg?&style=for-the-badge&logo=&logoColor=" />](https://drusho.github.io) [<img src="https://img.shields.io/badge/github-%23181717.svg?&style=for-the-badge&logo=github&logoColor=white" />](https://github.com/drusho)  [<img src ="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">](https://twitter.com/drusho)  [<img src="https://img.shields.io/badge/tableau-%23ff4d4d.svg?&style=for-the-badge&logo=tableau&logoColor=white">](https://public.tableau.com/app/profile/drusho) [<img src="https://img.shields.io/badge/linkedin-%230A66C2.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://linkedin.com/in/davidrusho)
