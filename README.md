# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Web APIs & Classification

### Problem Statement 

The Goal of this project is to teach engineer basic understanding on how to do Natual Language Processing problem using API. 
Since there was no data given, I choose to collect data from Reddit using it's API. 

Two subreddit I picked was r/iphone and r/GooglePixel 

1. Iphone url : https://www.reddit.com/r/iphone.json
2. GooglePixel : https://www.reddit.com/r/GooglePixel.json

#### Approch - Collect , Clean, Model

##### Collect :

I collected about 1200 posts for each subbredit and from those posts, i picked the title of the post. 
Since the data was in json file, i change it to pandas dataframe and then to csv. 

##### Clean:

Out of 1200, 300 was dublicate jobs. So, i deleted the dublicates and got rid of the null post. 

#### Model and results:

I used Logistic Regression and Naive Bayes Multinomial models. 

Logistic Regression Accuracy : Training - 98.6 % and Testing 86.5%
Naive Bayes Multinomal Accuracy : Training - 95.6 % and Testing 88.45%

Naive Bayes Multinomal was less overfitting then logistic regression 
