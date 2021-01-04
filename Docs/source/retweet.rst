**************************************************
Retweet
**************************************************
It retweets on tweet passed in ``tweet_url`` with tweet passed in ``tweet``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: twitter.retweet(tweet="tweet",tweet_url="tweet_url")

   
   :param str tweet: Tweet or text to post
   :param str tweet_url: Tweet link where need to retweet
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict