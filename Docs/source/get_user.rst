**************************************************
Get User
**************************************************
It fetches the data of profile passed in ``profile_url``.

Here is the code:-

.. py:function:: twitter.get_user(profile_url="profile_url")

   
   :param str profile_url: Profile url whose information need to be fetched
   :return: {'Joined': 'Joined', 'Info': 'Info', 'DOB': 'DOB', 'Following': 'Following', 'Website': 'Website', 'Followers': 'Followers', 'Location': 'Location', 'Twitter_Id': 'Twitter_Id', 'Name': 'Name', 'TweetsCount': 'TweetsCount'}
   :rtype: dict