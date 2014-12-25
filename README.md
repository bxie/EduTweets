EduTweets
=========

Visualizes Frequency of Education Related Tweets (#onlineeducation)

=========

TO RUN:

1. Go apps.twitter.com and create an App
2. Add necessary information (Consumer and Oauth Keys) to first cell in EduTweets.ipynb
3. Run Each Cell in Order (The last cell will output the visualization)
 
NOTES:
- To change the query, see the specifications in the 4th cell (variable "q" in particular). Any hashtags in "q" must be added to q_hashtags list
- Cell 4 actually makes the call to the Twitter API. This will take time. This may also be rate limited (dev.twitter.com/rest/public/rate-limiting)

