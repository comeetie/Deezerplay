# Deezerplay

1. Playlist data
	- files : playlist2.txt, playlist1.txt
	- source : ["Word2vec applied to Recommendation: Hyperparameters Matter" by H. Caselles-Dupré, F. Lesaint and J. Royo-Letelier.](https://github.com/deezer/w2v_reco_hyperparameters_matter)
	- content : one playlist per line track\_deezerid, artist\_deezerid

2. Artist data
	- file : Artists.csv
	- source : [deezer api artist](https://developers.deezer.com/api/artist) 
	- file artist\_details\_spot.csv
	- source [spotify api artist](https://developer.spotify.com/documentation/web-api/reference/artists/get-artist/) + deezerid

2. Track data
	- file : Tracks.csv
 	- source : [deezer api artist](https://developers.deezer.com/api/track)
 	- file track\_details\_spot.csv
	- source [spotify api audio features](https://developer.spotify.com/documentation/web-api/reference/tracks/get-several-audio-features/) + deezerid
