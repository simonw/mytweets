mytweets
========

A simple script to back up all of your tweets in to a local JSON file.

Dependencies:

- httplib2 from http://code.google.com/p/httplib2/
- simplejson (unless Python 2.6) from http://pypi.python.org/pypi/simplejson/

Usage:

1. Create a file called config.py in the same directory as the script:

USERNAME = 'your-twitter-username'
PASSWORD = 'your-twitter-password'

2. Run the command like so:

python fetch.py

3. Your tweets will be saved to my_tweets.json

You can run the command again any time to save new tweets created since you 
last ran the script.
