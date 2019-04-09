# Realtime_Object_detection_tensorflow.js
Real time object detection using tensorflow.js in the browser through web cam

Most of the code taken from below blogpost

https://medium.com/@erdemisbilen/building-realtime-object-detection-webapp-with-tensorflow-js-and-angular-a4ff5062bdf1

This is a clientside object detection using web cam

##Usage##
1)Online model :
Directly open index.html in browser, when you connected to internet and it will work after few seconds.

2)Offline model:
You need to start the server first using below command
python server.py

Next just open the index_local.html in the browser then it will load model from models folder and it will try to detect
