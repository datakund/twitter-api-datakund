**************************************************
Post
**************************************************
It tweets on twitter with text passed in ``tweet``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: twitter.post(tweet="tweet")

   
   :param str tweet: Tweet which need to be posted
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict