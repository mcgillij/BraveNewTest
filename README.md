# BraveNewTest
Test for Brave New World

## index.html
This file contains the work done for the resize / 3d cube and the mobile redirect

The resizing of the video is being done with stylesheets / div wrapper.

3D Cube was created using three.js / CSS3DRenderer / TrackballControls to get the 3d cube.

All the video muting / autoplay / pause disabling and time setting done with the vimeo js api.

## mobile.html
Contains the code for the mobile accelerometer tilt/bouncy 
using very basic js calls to move the title of the video around that was fetched via the vimeo js api.
Bounces around the title and an animated gif of the first few seconds of the video.

## login.html
Contains the code for the facebook iRate friendship rating app.

As I never used facebook in the past, this was interesting, as I have privacy concerns with the implications of using it at all. But I made an account and signed up for the developer api, read through the docs and created this very basic friend rating application.

You can use the test user: wjaourt_wongsen_1477231539@tfbnw.net, password:Test12
To access the application that reads his other friends that are loaded up as test users.

I used localforage.js for the persistent storage on the client end. 

Test environment setup on AWS accessible here:

Resize / 3d Cube / Mobile site can be accessed http://52.23.254.116:8000/index.html
Facebook iRate test application: http://52.23.254.116:8000/login.html (don't forget the login details above)

