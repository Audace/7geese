#7geese
======

Hubot script for integrating with the 7geese platform.

##Configuration
=============

* `GEESE_CONSUMER_KEY`: The oauth_consumer_key given to users by 7geese

##Usage
=====

* Once you have your bot up and running, there are three main uses of the script
    * `Hubot 7geese total`: Returns the total recognitions given in your network as well as a link to the board
    * `Hubot 7geese newest`: Returns the newest recognitions and link to that specific category of recognitions
    * 60 second interval: Checks to see if any new recognition has been made, if so it prints it in the #general room

* After 7geese is finished developing a newer version of their API, plans for more integration with calls about individual users and check-ins will be executed
