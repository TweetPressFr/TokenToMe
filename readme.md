# TokenToMe #

Get access token from Twitter

## Requirements ##

consumer key and consumer secret : <a href="https://apps.twitter.com/app/new">Get yours !</a>


## Description ##

Class that allows you to grab an access token from Twitter in WordPress

`$init =  new TokenToMe('CONSUMER_KEY', 'CONSUMER_SECRET', 'statuses/user_timeline', array('count' => 20), 'tweetpressfr');`

The fourth param should give you the ability to add additional param according to the Twitter's API documentation.

## Changelog ##

# 1.1
* Fix some bugs in case class is not set properly
* add method to Twitter's object according to any request

# 1.0
* First commit
