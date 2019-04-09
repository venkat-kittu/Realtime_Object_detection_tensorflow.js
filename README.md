# Realtime_Object_detection_tensorflow.js
Real time object detection using tensorflow.js in the browser through web cam

Most of the code taken from below blogpost

https://medium.com/@erdemisbilen/building-realtime-object-detection-webapp-with-tensorflow-js-and-angular-a4ff5062bdf1

This is a clientside object detection using web cam

# Usage <br />

**1)Online model :**<br />
Directly open index.html in browser, when you connected to internet and it will work after few seconds.<br />

**2)Offline model:**<br />
You need to start the server first using below command.This will run a simple python server.<br />


python2 :<br />
  python server.py


python3 : <br />
  python3 server.py

Next just open the index_local.html in the browser then it will load model from models folder and it will try to detect
