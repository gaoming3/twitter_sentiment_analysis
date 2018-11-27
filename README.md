# Twitter_Sentiment_Analysis
https://www.kaggle.com/crowdflower/twitter-airline-sentiment<br />
Analyze how travelers in February 2015 expressed their feelings on Twitter

This is a sentiment analysis that predict the motion of each tweet and the negative reasons behind each tweet.

Sentiment Analysis is a branch of NLP that allows us to determine algorithmically where a statement or document is "positive" or "negative"<br />
This is a guide for sentiment analsysis includes: how to use build and test your model.<br />
In this twitter sentiment analsysis, there are 5 different sections: 

### 1.Cleaning data
Remove html tags, attributes, URLS, stopwords.<br />
Html characters replaced with an ASCII equivalent

### 2.Exploratory analysis<br />
What can data tell you?

### 3.Model preparation and implementation<br />
The idea of this step was to train a model using "A" data set and use it on "B" data set and check with results that given from "B"<br />
Also train a multiple class logistic regression model and check its accuracy

A logistic regression was used to train data from generic tweets(Trainning 70% data and testing 30% data) <br />
TF-IDF methods was used and explained in the notebook

### 4.Discussion <br />
My thoughs from step 1 - step 4.

### 5.Bonus section<br />
Compared model performance between:<br />
LinearSVC, Logistic Regression, Multinomial NB and Random Forest Classifier.

This code can be used on any NLP analysis. <br />
Hope you enjoy!

### If you have any questions,feel free to shoot me a email :) 

Mingkun Gao<br />
mingkun.gao@mail.utoronto.ca<br />
Toronto, Ontario

Licensed under the [MIT License](LICENSE)
