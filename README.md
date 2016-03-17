Pitchfork Scraping
==================
Pitchfork is a popular music website that publishes reviews, news, and exclusive content daily. It's a pretty good source if you're able to ignore the occasional snarkiness. 

I tend to use Pitchfork to see what's been released and find some new tunes. I always use Spotify to listen to any songs that seem interesting.

I'm tired of having to manually search for artist and song names to add to a playlist on Spotify, so I'm going to make things a little easier. I really like Pitchfork's "Best Of" lists and found that they follow a similar format of displaying titles in their HTML. 

This script will scrape artist and song titles from all the pages of the online feature provided, add a new playlist to the Spotify user provided, and populate that playlist with as many tracks as it can find.

Usage
-----
    $ python pitchforkScraping/ YOUR_SPOTIFY_URI_NUMBER http://pitchfork.com/LINK/TO/BEST/OF/FEATURE

Dependencies
------------------
###Beautiful Soup 4.x
    $ pip install beautifulsoup4

###Spotipy 2.0
    $ pip install spotipy

See [Spotipy's documentation](http://spotipy.readthedocs.org/en/latest/) for help setting up local Spotify API environment.


"Best Of" Example URLs
----------------------------
### [200 Best Songs of the 1980's](http://pitchfork.com/features/lists-and-guides/9466-the-top-200-tracks-of-2010-2014/)

### [200 Best Songs of the 1980's](http://pitchfork.com/features/lists-and-guides/9700-the-200-best-songs-of-the-1980s/)

### [100 Best Tracks of 2015](http://pitchfork.com/features/lists-and-guides/9765-the-100-best-tracks-of-2015/)

####More can be found [here](http://pitchfork.com/features/lists-and-guides/).
