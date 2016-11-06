# BraveNewTest
Test for Brave New World

## facebook.html
This new version of the Facebook friendship rating application, no longer lets the users rate their friends, but instead calculates a friendship rating for them. Due to needing special permissions from facebook to be able to view anything even remotely interesting in their GraphAPI, the rating is derived from the mutual friends between yourself the user, and your friends. Those with more friends in common will score higher. I wanted to incorporate music choice into the equasion but my app needs to be reviewed first before they allow it to query that information from the GraphAPI. The site has been toggled to live on facebook, you can access the link here: https://s3.amazonaws.com/mcgillij-test/facebook.html

For users to be visible in then application they also need to have signed into the application and accepted the application permissions. The friends list is limited to other users who have signed into the application as per Facebooks terms of service rules.

As of version 2.0 GraphAPI we can no longer query the friendslist directly, thus we can only pull the friends that have also signed into the application.

You can see a screenshot of the application in action here: https://github.com/mcgillij/BraveNewTest/blob/master/irate.png 
Or the source-code here: https://github.com/mcgillij/BraveNewTest/blob/master/facebook.html

## index.html
This file contains the work done for the resize / 3d cube and the mobile redirect

The resizing of the video is being done with stylesheets / div wrapper.

3D Cube was created using three.js / CSS3DRenderer / TrackballControls to get the 3d cube.

All the video muting / autoplay / pause disabling and time setting done with the vimeo js api.

Left click spins the cube, right click pans and middle click zooms.

I left some code in here commented out that you can switch if you want to render a cube or a rectangle, I thought the rectangle looked cooler, so I just left it as the default for now.

## mobile.html
Contains the code for the mobile accelerometer tilt/bouncy 
using very basic js calls to move the title of the video around that was fetched via the vimeo js api.
Bounces around the title and an animated gif of the first few seconds of the video.

## login.html -- old
Contains the code for the facebook iRate friendship rating app.

As I never used facebook in the past, this was interesting, as I have privacy concerns with the implications of using it at all. But I made an account and signed up for the developer api, read through the docs and created this very basic friend rating application.

You can use the test user: wjaourt_wongsen_1477231539@tfbnw.net, password:Test12
As this isn't a "LIVE" application on facebook it's just in test mode.
To access the application that reads his other friends that are loaded up as test users.

I used localforage.js for the persistent storage on the client end. 

## Test environment setup on AWS accessible here:

Resize / 3d Cube / Mobile site can be accessed https://s3.amazonaws.com/mcgillij-test/index.html
New Facebook iRate application: https://s3.amazonaws.com/mcgillij-test/facebook.html (should be usable with regular facebook accounts).
Old Facebook iRate test application: http://jm-site.s3-website-us-east-1.amazonaws.com/login.html (requires test user login details above)

