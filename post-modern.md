# Post-Modern

--
# Phone as a Gamepad
![Apple](img/apple-logo.png) ![Android](img/android-logo.png)
## There's an app for that...
<aside class="notes">
  yay itunes, yay google play
</aside>

--
# It's called a Browser
![Firefox](img/firefox-logo.png) ![Chrome](img/chrome-logo.png)

[demo](http://azprogrammer.com/frozen/vanagon)
--

## You have to use your hands?
![Firefox](img/babys_toy.jpg)
## That's like a baby's toy.
--

# Camera Face Tracking
![Unicorn Donuts](img/unicorn_donuts.png)
<aside class="notes">
  Donut Horns made by B-Reel for Google hangouts
</aside>
--

# Voice Recognition
<img src="img/HAL9000.png" style="">

--

# Web Speech API
```javascript
new webkitSpeechRecognition();
```
[Demo](https://googledrive.com/host/0By0fqh2gf1M7MjhtOUhISjZHUFE/)

--
# 3D Tracking
  
* Leap Motion
* MS Kinect
--
# Leap Motion
![Leap Motion](img/leap.jpg)
# WebSockets !
<aside class="notes">
  bindings for Java, CSharp, python...
</aside>
--
## leap.js
```javascript
  var controller = new Leap.Controller({enableGestures:true});
  controller.on('frame', function(frame) {
    game.pointables = frame.pointables;
  });
  controller.connect();
```
[Demo](http://localhost:8081/)

--
## But I want to wear a controller...
![Picard](img/picard.jpg) ![Stark](img/stark.jpg)

--
# Project Glass
![Glass](img/glass.jpg)

--
# Mirror API
![Mirror](img/googleglassapi.png)

--
# Face
![Face](img/face.png)
[https://github.com/monteslu/Face](https://github.com/monteslu/Face)
--
## Face API
![Mirror](img/faceapi.png)

[demo](http://hackphx.com:11097/three/examples/face.html)
--
# Connect ALL the things.

# Websockets are your glue.
--

# Thank You

[@MONTESLU](http://twitter.com/monteslu)
