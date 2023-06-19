# Skybox transparency from generated depth map
small examples of using depth map and 360 skyboxes with three.js

The generated depth map was used to create the CockpitTransp.png file.  
I imported the 360 image and the greyscale depthmap into an image editor.   
There I used a curve and threshold filter to create a transparency mask of the windows - making them transparent - and saved the output as CockpitTransp.png with transparency.  
The three.js part is basically just one big sphere for the background and a second smaller sphere for the cockpit. Adding orbit control and that's about it.  
  
First time loading might take a bit - CockpitTransp.png is 14MB

