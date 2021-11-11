# covid_sentiments_analysis

#Dataset used for testing: 
https://www.kaggle.com/gpreda/covid19-tweets
#Dataset used for training1: 
http://help.sentiment140.com/for-students ( a list of 1.6 million tweets along with a score as to whether they're negative or positive. )
#Dataset used for training2:
https://www.kaggle.com/surajkum1198/twitterdata (This dataset contains cleaned tweets from india on topics like coronavirus ,covid 19 and lockdown etc. The tweets have been collected betwen dates 23th march 2020 and 15th july 2020 .then the text have been labeled into four sentiment categories fear ,sad,anger and joy.)
#NRC Word-Emotion Association Lexicon: 
http://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm

#Covid_tweets_polarity_using_ML
in this notebook, we tried to visualize the test data and train data to get information about both of them. Then we proceeded to training an SVM model on the train data after extracting the relevant information (polarity and user location) from it. We used a vectorizer that would extract at most 4000 features (memory allocation limit). We visualized the negativiy and positivity according to cities.

