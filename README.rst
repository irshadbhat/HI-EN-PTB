Code-Mixed Hindi-English Paninian dependency treebank
=====================================================

----

Requirements
^^^^^^^^^^^^

Install `Tweepy`_

.. _`Tweepy`: https://github.com/tweepy/tweepy

Get your Twitter app keys from https://apps.twitter.com/ and put the keys in the ``crawl_tweets.py`` script.


Crawl Tweets
^^^^^^^^^^^^

::

    python crawl_tweets.py -i tweet_ids_train.txt -a train-annot.json -o tweets_train.conll
    python crawl_tweets.py -i tweet_ids_dev.txt -a dev-annot.json -o tweets_dev.conll
    python crawl_tweets.py -i tweet_ids_test.txt -a test-annot.json -o tweets_test.conll


Data Statistics
^^^^^^^^^^^^^^^

::

    ||  Sentences ||   Tokens  ||   Hi  ||  En   || Ne  || Univ  || Acro  ||
    ||  1,448     ||   20,203  || 8,363 || 8,270 || 698 || 2,730 || 142   ||


Contact
^^^^^^^

::

    Irshad Ahmad Bhat
    MS-CSE IIITH, Hyderabad
    bhatirshad127@gmail.com
    irshad.bhat@research.iiit.ac.in
