Frequently Asked Questions
==========================

You can find most of the common FAQ's here, some are from `Pexels help <https://help.pexels.com/>`_.

What is Pexels?
---------------

Pexels is a free stock photo and video website and app that helps designers, bloggers,
and everyone who is looking for visuals to find great photos and videos that
can be downloaded and used for free. If you see a photo or video you like, simply download it for free (no strings attached!).

What steps can I take to avoid hitting the rate limit?
------------------------------------------------------

All API keys come with a default limit of 20,000 requests per month. This is sufficient for most use cases but here are a few tips to making the most of your requests. 

- Make requests that return more results at once. All the methods that return multiple objects
  can be configured with `page` and `per_page` parameters for pagination.
  The maximum value of `per_page` is 80. You should request for as much data as necessary for your use case.

- Implement your own cache of responses from the Pexels API. URLs to our content returned from the
  API should not change over the short term, so serving them from your own cache would allow you
  to use Pexels content without having to use up your quota. 24 hours is a good amount of time to cache responses for.

- If you are making searches based on your users’ input, normalize the searches.
  A search for `cat` will return the same response as a search for `cat`.
  Use this in conjunction with the caching described above.

Do I have to pay for higher limits?
-----------------------------------

Nope! The API is free of charge. If you’re likely to hit the default request limits and you're able to provide and 
show acceptable attribution to Pexels and our contributors, limits can be lifted free of charge.

Got more questions, where to ask?
---------------------------------

I have made a telegram group where you can ask your queries.
`Telegram Channel <https://t.me/blackbulls_support>`_