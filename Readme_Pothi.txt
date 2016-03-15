Steps to run :
Use Python 3
1. Install NLTK and the Corpus(Stopwords)
2. Install memcached
3. Install the python module for memcached (python3-memcached)
4. Install Tweepy
5. Start the server for memcached
6. Run 'python twitter_stream_download_cache.py -keyword' from your terminal

Comments:
I am not sure if I've implemented cache the way you wanted it.
I could change it if you like
Using nltk and some preprocessing, I have been able to identify @something, #something, links, emoticons and have ignored common words like 'the', 'and', 'to', etc. using the stopwords corpus of nltk.
