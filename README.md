# halloween-video-kiosk

This webpage was created to run on a rasberryPi as a full screen web kiosk to play AtmosFX videos in a full screen environment. The rasberryPi on boot launches Google Chromes kiosk mode. For details visit [my blog post ](https://www.nicholasstees.com/fun/2017/10/13/halloween-video-kiosk)

### Features
- Videos automatically start playing
- Videos are randomized at the start to give a variety in performances
- Select videos can be triggered by keyboard keys (used for jump scares)
- Videos will fill to viewport container and work with any resolution.

## Getting started
Mainly you just have to clone this project, add videos to the /video folder, and change the javascripts videoSources array to match your video files.

## Keyboard shortcuts for videos
To create keyboard shortcuts to play certain videos, modify the script to watch for those keycodes. I left keycodes to log to the console on every keypress, so just pull up the Browsers console (F12) and watch for those codes as you press keys, and modify the script accordingly. 

#### Happy Halloween and Enjoy!
