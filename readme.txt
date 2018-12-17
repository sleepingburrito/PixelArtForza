Forza pixel art macro maker. Upload an image and copy and paste the code generated into a “.ahk” (you will need https://www.autohotkey.com/ installed for the “.ahk” to work). Start the macro then switch back to the game, make sure the game is in the create new vinyl menu at the start (where your adding the first shape to the first layer). From there let it do its magic.

Info:
-It only supports 100% alpha (so when the alpha channel reads 0 in RGBA). Other alpha levels could be supported in the future.

-Get 60fps. I tried to tune the timing on key presses to work for 60fps but I cant guarantee for less fps.

-Its slow, it could take a few hours depending on the complexity of the image. I use it when I’m at work or sleeping. Please someone take my script and make a faster script that’s better than this one, there are a lot of tricks that I did not do.

-It uses 1 block per pixel, so a 3k pixel limit per vinyl group. 100% alpha pixels do not count so you can have as many as you want. The pixel count is given after the generation at the top of the file, so you can get an idea if you went over or how long it will take to make.

-Max resolution is depending on max pixel count. If you use all the pixels in a square shape it comes out to about 54x54 for the 3k layer limit. But you could do a larger image for example if you used alpha pixels. Keep in mind that where you can place shapes is based on screen limit. The macro draws from the center to the right/down. I made sure 54x54 works for 1080p display but it will dependent on your resolution. 

-To stop the macro, you will need to minimize the game and close it in the system tray. There is also no way to continue from where you left off.


This app is a static webpage with the code embedded. You may download it and run it offline. There are settings in the code that I did not expose (like key press timing and starting location). Please play with them if you wish. 

Credit:
https://stackoverflow.com/a/4459419
https://stackoverflow.com/a/8023734
author: SleepingBurrito
