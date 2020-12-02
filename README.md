# getDeletedTwitchVodsWithoutSeconds

Requirements:

* hashlib. install if you don't have it
* datetime. install if you don't have it
* urllib
* Python 3+

Once you have all requirements installed, run the script and enter the info it needs (streamer name, vod ID, start timestamp of stream) and it will return a url. Feed this url into VLC's network stream and you can now view deleted vods.

* streamer name: the exact streamer's name
* vod ID: The broadcast id can be found in the last part of the URL on twitchtracker. For example https://twitchtracker.com/berry0314/streams/40382317630, the broadcast id is 40382317630.
* start timestamp: formatted like this (YYYY-MM-DD HH:MM) in UTC time. You can Also find this information on twitchtracker.
