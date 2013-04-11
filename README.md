Spotube
=======

Convert Spotify playlists into YouTube ones.
Based on Jukebox (PySpotify).

Dependencies
=======

  - Python 2.7
  - LibSpotify
  - PySpotify 
  - GData (Python API Google)

  - Spotify Premium Account
  - YouTube Developer Key (it's free)


Installation
=======

  - LibSpotify
    - Download https://developer.spotify.com/technologies/libspotify/
    - Extract and run
      # make install prefix=/usr/local

  - PySpotify
    - Download http://pyspotify.mopidy.com 
    - Extract and run
      # python setup.py install

  - GData
    - Download http://code.google.com/p/gdata-python-client/downloads/list
    - Extract and run
      # python setup.py install

  - Spotify Premium Account
    - You will need to request an application key at the developer website http://developer.spotify.com/ before being able to run it.
    - Place spotify_appkey.key in the same folder that spotube.py

  - YouTube Developer Key
    - Get one at https://code.google.com/apis/youtube/dashboard/

Configuration
=======

  - Complete spotube.cfg with your Spotify and YouTube credentials.

Run
=======

  - Run
    $ python spotube.py

License
=======

  - MIT License
