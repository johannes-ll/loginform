# Music streaming website
This project was developed a year ago for my final project in a web development class I had. When submitted, everything was working correctly, but now some functions have depreciated so I have decided to update it.
## If you are interested, please check out my *original extensive documentation [here](https://github.com/johannes-ll/project-list/blob/main/Dokumentation%20slutprojekt%20-%20Musikstreamingtj%C3%A4nst.pdf)*
## Changes
### Changed DB
I originally used mysql for my database. I changed this to mongodb as the original implementation was janky and I feel that mongodb is more important to show knowledge about. To do this I needed to remake some auth.js code, update server.js slightly and change playlist.js to fit with mongodb. I am happy with these changes.
### Removed depreciated yt-dl
A year ago when I created this project the standard was to use yt-dl. Now that package is depreciated, so I decided to use youtube-audio-stream instead. I used this package over others since I only need to stream audio and this was the simplest to set up, the only needed dependecy is ffmpeg.
### Styling
The login page didnt have its own css so I made something basic to make the page usable. I should also route everything to auth.html if the user isnt logged in.
### Showcase video
The original video showcasing the website dissapeared with my google school account, so I need to create a new one.
