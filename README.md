# LIRI-CLI

L.I.R.I. stands for Language Interpretation and Recognition Interface. It is a command line node app that takes in parameters and gives back data from various APIs.


The app features 4 different features using the node liri.js [command-here] syntax. Below are the command types...

concerthis [artist-here] returns any upconing concerts using the BandsInTown API.

![concertthis](http://i63.tinypic.com/2d0i8w8.png "concertthis")

spotifythis [song-title-here] returns the artist, album, and preview URL for a specific song using the Spotify API.


![spotifythis](http://i67.tinypic.com/5x205s.png "spotifythis")

moviethis [movie-title-here] returns the year, rating, plot summary, reviews of a specific movie using the IMDb API.


![moviethis](http://i64.tinypic.com/ei8n77.png "moviethis")

dowhatitsays returns the result of a "random" result by reading the random.txt file and performing the command written in that file. This command can be changed to any one of the 3 types listed above.

![dowhatitsays](http://i67.tinypic.com/15fkwn5.png "dowhatitsays")


#Instructions
Unfortunately, since this is a command line application, it must be cloned down to your machine to be demoed. After cloning down the repo to your computer, cd into the LIRI-CLI folder and run npm install to download all the node dependencies mentioned above.

To run the app, simply use the node liri.js [command-here] format discussed above.
