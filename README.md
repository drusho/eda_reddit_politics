[<img src="https://img.shields.io/badge/Email-%23EA4335.svg?&sflat&logo=gmail&logoColor=white" height="20" width="60" />](mailto:rraxxpl0jagb@opayq.com) &emsp;[<img src="https://img.shields.io/badge/Twitter-%231DA1F2.svg?&sflat&logo=Twitter&logoColor=white" alt="Twitter profile link button" height="20" width="70" />](https://twitter.com/drusho) &emsp; [<img src="https://img.shields.io/badge/Linkedin-%230A66C2.svg?&sflat&logo=linkedin&logoColor=white" alt="Linkedin profile link button" height="20" width="70" />](https://linkedin.com/in/davidrusho) &emsp; [<img src="https://img.shields.io/badge/Tableau-%23ff4d4d.svg?&sflat&logo=tableau&logoColor=white" alt="Tableau profile link button" height="20" width="70" >](https://public.tableau.com/app/profile/drusho) &emsp; [<img src="https://img.shields.io/badge/Github Blog-%23181717.svg?&style=flat&logo=github&logoColor=white" alt="Github profile link button" height="20" width="90" alt="Github Blog Button"/>](https://drusho.github.io/blog) 

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
