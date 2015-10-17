---
layout: page
title: Mr Run
image:
  feature: greenbacon.png
---
## Description
Mr Run is a simple Android App with networking functions.

It has a user accounts system, which allows users to sign up and pick a character. When they login in the future, they will load their chosen character. Once their character loads on the screen, it will walk to anywhere 

## The Process ##

### Technologies ###
+ PHP and MySQL for the user database
+ Java for the Android App and Server

One of my main goals for working on this project was to explore the animation functionalities of Android Studio. Android Studio has many animation functions and classes. I had to expriment with a few of them in order to find one that could animate the walking motion and the movement to the new position.

After I got the animation working, I move on the implementing the server. I wrote and tested both TCP and UDP servers, hosted on an Amazon EC2 instance. In the end, I decided on the TCP server. The server operates with simple protocols. Whenever a new user joins or when a user moves, the app sends a message to the server. The server then relays this message to all connected users to update them on the new position. 

[![gitimage](/images/gitpic.jpeg)](https://github.com/themetalbacon/Mr-Run "Link to GitHub page")
