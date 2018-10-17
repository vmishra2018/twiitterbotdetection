### CSCI S-109a - Introduction To Data Science - Final Project
### Contributors: [Karan Bhandarkar](mailto:karanbhandarkar@gmail.com), [Vivek Mishra](mailto:iblpvivek@icloud.com)
<HR>
  
### [Welcome](README.md)&emsp;|&emsp;[Introduction and EDA](intro-and-eda.md)&emsp;|&ensp;[**_Literature Review_**](lit-review.md)&emsp;|&emsp;[Models](models.md)&emsp;|&emsp;[Summary](summary.md)
<HR>


## Content:
1. [References](#references)
1. [Related Work](#related-work)

<HR>
  
### References

1. Stefan Wojcik, “Bots in the Twittersphere”: http://www.pewinternet.org/2018/04/09/bots-in- the-twittersphere/ 

2. Chris Baraniuk, “How Twitter Bots Help Fuel Political Feuds”: https://www.scientificamerican.com/article/how-twitter-bots-help-fuel-political-feuds/ 

3. Chengcheng Shao et al., “The spread of low credibility content by social bots”: https://arxiv.org/pdf/1707.07592.pdf

4. The tweepy Python library: http://www.tweepy.org

5. Twitter’s developer resources to learn about the API: https://developer.twitter.com 

6. Asbjan Ottesen Steinskog et al., ”Twitter Topic Modeling by Tweet Aggregation": http://www.aclweb.org/anthology/W17-0210 
Time Magazine: http://business.time.com/2013/04/24/how-does-one-fake-tweet-cause-a-stock-market-crash/

7. The Telegraph: https://www.telegraph.co.uk/business/2018/03/31/twitter-bots-manipulating-stock-markets-fake-news-spreads-finance/

8. Twelve ways to spot a bot: https://medium.com/dfrlab/botspot-twelve-ways-to-spot-a-bot-aedc7d9c110c

[Back to top](#content)

### Related Work

#### [Twitter Bot Detection](https://github.com/RohanBhirangi/Twitter-Bot-Detection)

Observations from this project:<BR>
1. Decision Tree classifier provides the highest accuracy<BR>
2. High precision (>97%) values for all the classifiers<BR>
3. High precision denotes low false-positives (the probability of a user being identified as bot when it is a non-bot is low)<BR>
4. Thus, the models efficiently identify a non-bot account<BR>
5. But we get low recall score for the classifiers<BR>
6. Which means there are a lot of false-negatives in our prediction<BR>
7. These are twitter accounts which are bots but are identified as non-bots<BR>

#### [Detecting Twitter Bots using Machine Learning](https://github.com/jubins/MachineLearning-Detecting-Twitter-Bots)

Twitter bot is a program used to produce automated posts, follow Twitter users or serve as spam to entice clicks on the Twitter microblogging service. In this project, they use Machine Learning techniques to predict weather an account on Twitter is a Bot or a real user. They have performed significant amount of feature engineering, along with feature extraction - selected features out of 20 helped us to identify whether an account is bot or non bot. They implemented various algorithm but finally implemented their own which gave AUC>95%.

[Back to top](#content)
