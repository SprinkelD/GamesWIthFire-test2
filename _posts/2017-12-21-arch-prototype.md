---
ID: 1
post_title: ""
author: gameswithfire
post_excerpt: ""
layout: post
permalink: >
  http://localhost/2017/12/21/arch-prototype/
published: true
post_date: 2017-12-21 15:49:09
---
We've completed the second prototype of the archway sensor and lights system. For sensors, we've gone with 8 InfraRed sensors located above the participant. This gives us a nice understanding of what the user is doing and provides a form of multitouch input. Each Sepal will contain three of these in the archways. In the image below you can see the LED bars that will light the sides and top of the Sepal.

<img class="alignleft size-full wp-image-490" src="http://games-with-fire.com/wp-content/uploads/2017/12/ArchwayPrototype2.jpg" alt="" width="1200" height="900" />
<p style="font-weight: bold; line-height: 2px; text-align: center;">Prototype with Lighting</p>
The system itself is composed of 3 microprocessors: one that reads the analog IR sensors, one that publishes the sensor data and calculates a fast fourier transform and one that controls the lights. We've gone with a very distributed IoT(Internet of Things) architecture this go round, where each feature is a small single function subsystem. This should allow for a very module composition of things and hopefully, make it easier to allow more programmers to be involved.

<img class="alignleft size-full wp-image-491" src="http://games-with-fire.com/wp-content/uploads/2017/12/ArchwayPrototype1-1.jpg" alt="" width="1200" height="652" />
<p style="font-weight: bold; line-height: 2px; text-align: center;">Prototype Closeup</p>
Here is a video explaining the setup and showing some of the initial test animations.

<a href="https://youtu.be/b5WdR7Psenc" target="_blank" rel="noopener">Explanation Video</a>

This is a change for testing purposes.