This is an end-to-end sentiment analysis of tweets regarding Donald Trump.
The code extracts & loads tweets regarding Donald Trump to MongoDB Database. For every 1000 tweets, it selects the text column
containing all the tweets, transforms it into a Pandas dataframe, cleans & lemmatizes the tweets before running sentiment analysis 
& wordcloud.
1) Ensure that MongoDB has been downloaded and set-up is complete
2) Create new collection 'tweets' inside database
3) Ensure that twitter dev account has been set-up
4) Download ipynb file & replace consumer_key,consumer_secret,access_key,access_secret with your own credentials
5) Change 'twitterdb' in 'mongodb://localhost/twitterdb' to your database name
6) Run code & observe results
7) Kindly interrupt the code to stop execution

Fun-fact: During the period of creation, many are asking for the impeachment of Donald Trump. You can observe from the wordcloud
that the words 'impeachment', 'ukraine' are fairly-common.

P.S: This is my first attempt at an ETL project with MongoDB. Special thanks to the original code by Daniel Foley. 
Feel free to optimize the code as you wish.
