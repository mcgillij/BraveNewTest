# BraveNewTest
Test for Brave New World

## index.html
This file contains the work done for the resize / 3d cube and the mobile redirect

The resizing of the video is being done with stylesheets / div wrapper.

3D Cube was created using three.js / CSS3DRenderer / TrackballControls to get the 3d cube.

All the video muting / autoplay / pause disabling and time setting done with the vimeo js api.

I left some code in here commented out that you can switch if you want to render a cube or a rectangle, I thought the rectangle looked cooler, so I just left it as the default for now.

## mobile.html
Contains the code for the mobile accelerometer tilt/bouncy 
using very basic js calls to move the title of the video around that was fetched via the vimeo js api.
Bounces around the title and an animated gif of the first few seconds of the video.

## login.html
Contains the code for the facebook iRate friendship rating app.

As I never used facebook in the past, this was interesting, as I have privacy concerns with the implications of using it at all. But I made an account and signed up for the developer api, read through the docs and created this very basic friend rating application.

You can use the test user: wjaourt_wongsen_1477231539@tfbnw.net, password:Test12
As this isn't a "LIVE" application on facebook it's just in test mode.
To access the application that reads his other friends that are loaded up as test users.

I used localforage.js for the persistent storage on the client end. 

Test environment setup on AWS accessible here:

Resize / 3d Cube / Mobile site can be accessed http://jm-site.s3-website-us-east-1.amazonaws.com/index.html
Facebook iRate test application: http://jm-site.s3-website-us-east-1.amazonaws.com/login.html (don't forget the login details above)

