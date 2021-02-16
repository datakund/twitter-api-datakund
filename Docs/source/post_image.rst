**************************************************
Post Image
**************************************************
It posts image on twitter with text passed in ``tweet`` and image path in ``image_path``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: twitter.post_image(image_path="C:/Users/image.png",tweet="Hi...")

   
   :param str image_path: Image file path which needs to be posted on twitter
   :param str tweet: Tweet or description
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
