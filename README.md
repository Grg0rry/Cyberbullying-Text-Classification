# Text Classification on Tweets for Cyberbullying

## Background
A text mining project for Social Media Analytics (IST2134) on scrapping tweets and classifying them whether they are cyberbullying or not.

## Methodology
1. Tweets extracted through the `Twitter search API` using Tweepy
2. Labelize tweets collected
    - 1 for hate tweets (usage of sexist or racial slur, or criticizes or negatively stereotypes a sex or a minority)
    - 0 for non-hateful tweets
3. Data cleaning
    - remove twitter handles (@user), 
    - hyperlinks, 
    - special characters, 
    - numbers,
    - punctuations, and
    - stop word
4. Tokentization and Lemmatization to root word
5. Modelling techniques
    - Logistic Regression,
    - Multinomial Naive Bayes, and 
    - Support Vector Classifier
