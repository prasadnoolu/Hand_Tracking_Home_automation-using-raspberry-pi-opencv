# Hand_Tracking_Home_automation-using-raspberry-pi-opencv
This project makes use of Rpi and opencv to turn on and off electrical appliances by showing respective hand (finger count) gesture infront of the raspberry pi webcamera

Dependencies
OpenCV (google it to install in your Pi)
WiringPi (Installation: http://wiringpi.com/download-and-install/)

video link:
https://drive.google.com/file/d/1CVgpH9-SdRxy7wluBJeg9Q_hHrNCYun_/view?usp=sharing

Compiling  the code by typing this command in your Raspberry pi terminal
g++ Hand.cpp -o Handy `pkg-config --libs opencv` -std=c++11 -lwiringPi

Running the code:
./Handy

Have Problem, put an email @ varaprasad239@gmail.com
