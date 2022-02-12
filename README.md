# Music
Simple script to listen music on terminal

# Deps
Required:
* mpv

Optional (only necessary if playing musics that you don't have downloaded):
* youtube-dl(or any fork)
* sed 
* curl 
* search(already included)

# How to install
* Clone this repo
* Run install.sh

# Usage
* music <command>
* play file:<path to file>				| Play local music file
* play folder:<full path to folder> 		| Put all songs in a folder on a temp playlist
* play playlist:<full path to txt file>	| Use plain text file as playlist
* play url:<url>							| Play specific url
* play search:<song to search>			| Search for specific song online
* next 									| Skip current song
* prev 									| Return to previous song
* seek  <time> 							| Seek for the specified time
* advance									| Advance music 5 seconds
* return 									| Return music 5 seconds
* pause									| Pause music
* loop									| Loop music (will stay active until reboot or you disable it)
* stop									| Stop current song						
## Parameters:
* --shuffle									| Works with 'playlist:' and 'folder:' start playlist in a random order
* --first									| Works with 'search:' play the first song returned from search

