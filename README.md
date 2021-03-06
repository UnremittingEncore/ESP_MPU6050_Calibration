# ESP32_MPU_6050 Noise Reduction using Kalman Filters
  
Project built upon by using this link https://RandomNerdTutorials.com/esp32-mpu-6050-web-server/

Kalman Filter Link https://github.com/jarzebski/Arduino-KalmanFilter

## Project Overview
- We use Server-Sent Events to update all the readings.
- The 3D object is created using a JavaScript library called [three.js](https://threejs.org).

## Update Network Credentials (in the Arduino sketch)
```
// Replace with your network credentials
const char* ssid = "REPLACE_WITH_YOUR_SSID";
const char* password = "REPLACE_WITH_YOUR_PASSWORD";
```

## Useful Links
- https://www.avrfreaks.net/forum/tut-hard-gyros-and-accelerometers-basics?name=PNphpBB2&file=viewtopic&t=89294
- http://www.geekmomprojects.com/gyroscopes-and-accelerometers-on-a-chip/
- https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-333-aircraft-stability-and-control-fall-2004/lecture-notes/lecture_15.pdf
- https://stackoverflow.com/questions/23009549/roll-pitch-yaw-calculation/23010193
- https://os.mbed.com/questions/83017/Calculating-Yaw-using-accelerometer-and-/
 
 
