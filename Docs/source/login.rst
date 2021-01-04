**************************************************
Login
**************************************************
It logins to twitter through credentials passed in ``username`` and ``password``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: twitter.login(username="username",password="password")

   
   :param str username: Twitter Username
   :param str password: Twitter Password
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict