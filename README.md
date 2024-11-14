# Twitter Sentiment Analyst with NLP



The aim of this project is to perform sentiment analysis on Turkish tweets obtained from Twitter. Two datasets are utilized for this purpose:

<b> tweets_labeled.csv: </b> This dataset contains labeled tweets with sentiment analysis already performed. Model training will be conducted using this dataset.<br>
<b> tweets_21.csv:</b> This dataset consists of tweets without sentiment analysis. Using the trained model, sentiment predictions will be made on this dataset, and the predicted results will be saved in a new label column.

Several essential steps have been completed in this project:<br>
<b>Feature Engineering:</b> New columns and features have been added to the tweets_labeled.csv dataset.<br>
<b>Data Preprocessing:</b> Tweets have been converted to lowercase, and numbers, punctuation, and stop words have been removed. Dependent variables were transformed using label encoding.<br>
<b>TF-IDF Model:</b> The TF-IDF model has been applied for sentiment analysis.

As a result of model training, an accuracy rate of 65% was achieved. The model was also tested with external tweets, showing a reasonable level of accuracy in these tests as well.
