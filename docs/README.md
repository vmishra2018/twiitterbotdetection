## CSCI S-109a - Introduction To Data Science - Final Project
#### Contributors: [Karan Bhandarkar](mailto:karanbhandarkar@gmail.com), [Vivek Mishra](mailto:iblpvivek@icloud.com)
<HR>
  
### [**_Welcome_**](README.md)&emsp;|&emsp;[Introduction and EDA](intro-and-eda.md)&emsp;|&ensp;[Literature Review](lit-review.md)&emsp;|&emsp;[Models](models.md)&emsp;|&emsp;[Summary](summary.md)
<HR>

### Content:
1. [Motivation](#motivation)
2. [Problem Statement](#problem-statement)

<HR>

### Motivation 

Manipulative robots are spreading fake news online that could be exacerbating volatility in financial markets.

A [major study](https://editorialexpress.com/cgi-bin/conference/download.cgi?db_name=RESConf2018&paper_id=874)  of tens of millions of tweets over two years found that the sheer volume sent by “bots” helped to drive shares in FTSE 100 companies up or down for short periods, effectively moving markets. Tweets sent by humans typically had a positive impact on stock prices while those sent by robots were more often negative, according to research presented to the Royal Economic Society by economists Oleksandr Talavera, Rui Fan and Vu Tran.

Robot messages typically had an effect for up to half an hour, pulling down prices and increasing volatility.

In 2013, the Twitter feed of the Associated Press told us that [Barack Obama had been injured in an explosion at the White House](https://www.theguardian.com/business/2013/apr/23/ap-tweet-hack-wall-street-freefall). The tweet was fake — the product of a hack — but given the events in Boston earlier in the week, the news spread like wildfire, garnering more that 4,000 retweets.

The AP quickly addressed the situation, suspending its Twitter account, and alerting readers through associated accounts that the tweet describing an explosion at the White House was the result of a hack.  No harm, no foul, right?

Well, not exactly. [According to the Financial Times](https://www.ft.com/content/33685e56-ac3d-11e2-a063-00144feabdc0#axzz2RLrglMyc), that one tweet sent shock waves through the stock market — causing the S&P 500 to decline 0.9% — enough to wipe out $130 billion in stock value in a matter of seconds. The market quickly recovered that value, but the breakneck pace at which the stock market tumbled reminded many people of the infamous 2010 “flash crash,” or 2012's crisis at Knight Capital Management, in which a computer glitch cost the firm $440 million and nearly sent it into bankruptcy.

Both of these events were [caused by the proliferation of high-frequency trading](http://www.dailymail.co.uk/sciencetech/article-3090221/The-tweet-cost-139-BILLION-Researchers-analyse-impact-hacked-message-claiming-President-Obama-injured-White-House-explosion.html), or the practice of Wall Street firms using high-powered computers to execute thousands or millions of trades per second, making minuscule profits — that add up in a big way — on each trade.

[High frequency and algorithmic trading are taking over markets](https://medium.com/@ruzbehb/high-frequency-and-algo-trading-are-taking-over-markets-what-it-means-for-you-7017dec1308e). Traders have started using algortihms to comb through the internet at lightning fast speeds. Social sentiment has become a big part of these algorithms and hence, a major cause for concern for market volatility. It has become vital to validate the authenticity of the social sentiment and this, is the motivation behind our project.

[Back to top](#content)

<HR>
  
### Problem Statement:

In this project, the goal is to detect Twitter bots using tweets data from the Twitter developer API by utilizing machine learning techniques. This will be done to determine whether a financial tweet is of significance or not. How do we do this?
1. The first step is to create our own dataset. We will mine the data for the project using the Twitter API and utilize feature engineering and pre-processing techniques to prepare the data for analysis.
1. The next step is to plot the data in various ways to try and get an understanding of trends in our data. We will use this for selecting significant features and engineering new ones, where required.
1. After this, we start modelling the data. Different models could capture different feature relations better. We will try and capture this by using ensemble techniques.
1. Conclude with a comparison of the models. Include an error analysis and an evaluation of the predictive quality of the models. 

[Back to top](#content)
