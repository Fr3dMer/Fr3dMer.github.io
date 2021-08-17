--- 
short_name: Freddie
name: Alarm
image_link: /assets/images/main_alarm.png
title: Sunrise simulator alarm clock
blurb: A GUI which sends commands to a IKEA Trådfri gateway over CoAP to control a Trådfri lightbulb.
layout: projects
---

After struggling to get up in the dark of winter I decided to buy a Wake-Up Light Alarm Clock to simulate a sunrise, however seeing their high prices set out to make one myself.

I used a IKEA Trådfri lightbulb paired with a Trådfri gateway as a controllable wireless lightsource. Using a Rasberry Pi 3b I send commands to the gateway via CoAP(Constrained Application Protocol) using the library [libcoap](https://github.com/obgm/libcoap "link to libcoap library"). I wrote a multithreaded GUI using the python plug-in PyQt5 to act as a front end for displaying the time and to allow the user to set the simulated sunrise time.

