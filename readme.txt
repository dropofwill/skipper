Plan for Skipper:

* Drag-and-drop a users playlists, save the list.
* Shuffle+play a selected playlist
* Skip song right before it is over
	- current_timer = first by starting a timer on start up
	- duration =  meanwhile querying for the duration of the song - ~5s
	- until current_timer > duration play next track
	 
