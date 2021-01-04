**************************************************
Get User
**************************************************
It fetches the data of profile passed in ``profile_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: twitter.get_user(profile_url="profile_url")

   
   :param str profile_url: Profile url whose information need to be fetched
   :return: {"body": {'Location': 'Location', 'Twitter_Id': 'Twitter_Id', 'Info': 'Info', 'DOB': 'DOB', 'Joined': 'Joined', 'Followers': 'Followers', 'Name': 'Name', 'TweetsCount': 'TweetsCount', 'Website': 'Website', 'Following': 'Following'}, "success_score": "100", "errors": []}
   :rtype: dict