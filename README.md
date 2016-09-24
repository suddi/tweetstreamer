# tweetstreamer

A Tweepy streamer to collect tweets from Twitter's Streaming API based on criteria

## Install

````
pip install tweetstreamer
````

## Usage

````
from tweetstreamer import auth, listen

connection = auth(<CONSUMER_KEY>, <CONSUMER_SECRET>, <ACCESS_KEY>, <ACCESS_SECRET>)
listen(connection, <TRACK>)
````
