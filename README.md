# python-pexels
A unofficial python library to support all of Pexels API features.

* Supports all of the **endpoints**, which are available in API v1.0

* Return data are **python objects**.

* User **friendly** library.

* Easy to **use**.
  
📚 **Documentation** for this library can be found below. It contains **detailed instructions** on how to use API.

📚 **Documentation for the official API can be found** [here](https://www.pexels.com/api/documentation/?language=javascript).
## Installation

You can install the library via **pip**

    pip install python-pexels

Or using **source code**, which is not recommended.

    git clone https://github.com/jk6521/py-pexels-api.git

    cd py-pexels-api

    python setup.py install

more installation guide found [here](https://python-pexels.readthedocs.io/en/latest/installation.html)

## Usage & Example
You need **API token** to access Pexels API, you can get it [here](https://www.pexels.com/api/new/)

Once library is installed using pip, create a new python file named `main.py`

```py
    #main.py
    from Pexels import Client

    client = Client(token="abcd1223")

    #search photos
    photos = client.search_photo(query="Joker")

    #you can access return data like
    print(photos.total_results)

    >>> 230
```
more examples can be found [here](https://python-pexels.readthedocs.io/en/latest/examples.html)

## Useful Links

📚 [Docs](https://python-pexels.readthedocs.io/en/latest/index.html)
🌐 [PyPi](https://pypi.org/project/python-pexels/)
💬 [Telegram](https://t.me/blackbulls_support)