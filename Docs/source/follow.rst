**************************************************
Follow
**************************************************
It follow the profile passed in ``profile_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: twitter.follow(profile_url="profile_url")

   
   :param str profile_url: Profile url need to be followed
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict