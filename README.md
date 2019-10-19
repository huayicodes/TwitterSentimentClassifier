# Twitter Sentiment Classifier

### Project Overview
**Motivation:** Social media has become an indispensable platform for many businesses to directly interact with consumers and to market products. Using AI to automatically identify whether a tweet is a positive or negative response allows businesses to quickly grasp customer reactions without going through every tweet. 

**Deliverables:** In this project, I developed a Logistic Regression model to classify the sentiment (positive or negative) of tweets, to an accuracy of 77%. This trained model is useful for gauging overall consumer reactions to a new product, or for quickly locating negative responses, which usually require special attention from customer service.

### Project Details 
**The Data**: This big dataset contains 1600k tweets with labeled polarity.
- polarity labels: 0 = negative, 4 = positive <br>
- http://help.sentiment140.com/for-students <br>

**The Model**: Using a small subset (5%) of the total data, I compared a Naive Bayes model with a Logistic Regression model. The two models have similar performance, but Logistic Regression won by a tad. With this Logistic Regression model, I can classify the polarity of a tweet with 77% accuracy. This is a great performance considering that human analysts only agree around 80-85% of the time. 

**Next Steps**: 
* It's unknown how generalizable this model is when applied to specific businesses or products. It will be interesting to test it on a more specific dataset. 
* An unexplored approach is to look at phrases (bigram) instead of just single words (unigram). This could help in cases such as differentiating between "good" and "not good". 
* The third possibility is to analyze punctuations. Exclamation mark, for instance, indicates strong emotions. 
* And a neural network is always another option. 
