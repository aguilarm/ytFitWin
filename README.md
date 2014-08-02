YouTube FitWindow (ytFitWin)
========

I'm not a huge fan of fullscreen or the theatre mode YouTube has by default, so I made this extension that will resize videos to fit your window but still show the search bar.  It also auto resizes to fit when you resize your window, so you can always see the whole video no matter what size you want the window to be.

##Installation and Use

Right now this is not on the chrome store, so the easiest way to install is to put the src folder on your hdd somewhere, go to your chrome extensions (found under tools or as a tab grouped with history and settings), check Developer mode on the top right, click Load unpacked extension, and then choose the src folder.

To use, go to a youtube video (right now the extension only works on videos on youtube.com) and click the red rectangle to expand your video, seen below.
<br><br>
<img src="media/buttonLocation.png">

## ToDo


- Add settings page so user can turn on/off searchbar or make FitWin the default size
- Force 1080 or 720p
- Known Bug: If the user runs resizePlayer so it's large, then clicks a related video without running resizePlayer again  (minimizing video), the player to reloads large without running the onload script and everything except the related video section loads correctly.  Related videos load under the video, I'm pretty sure this is because YouTube uses a lot of ajax/xhr to load new videos so I need to try a few more things to fix it.