**************************************************
Login Cookie
**************************************************
It logins to the twitter through list of cookies passed in ``cookies``

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: twitter.login_cookie(cookies="cookies")

   
   :param str cookies: list of cookies of twitter
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict