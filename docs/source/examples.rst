Usage and Example
=================

You need API token to access Pexels API, you can get it `here <https://www.pexels.com/api/new/>`_

Once library is installed using pip, create a new python file named main.py

main.py

.. code-block:: python

    from Pexels import Client

    client = Client(token="abcd1223")

    #search photos
    photos = client.search_photo(query="Joker")

    #you can access return data like
    print(photos.total_results)

    >>> 230