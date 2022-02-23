# ITCS_5156_Project
In this project, I use the BERTweet model to analyze a set of COVID-19 related tweets and predict using a decision tree classifier whether or not the tweet was tweeted
by a verified user or not. I extract the embeddings from the BERTweet model and use those as X values and the column 'user_verified' from the COVID-19 dataset as y values 
which will be predicted. Then, an accuracy score is used after the datasets are fit to the model to see whether to measure the classifier's performance.
