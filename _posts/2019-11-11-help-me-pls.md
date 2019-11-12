---
layout: post
title: HELP ME
subtitle: pls
tags: [code, arduino, vibe board]
---

For this assignment, I wrote a program that buzzes out my name in Morse Code when a switch is turned off and buzzes out SOS in Morse Code when the switch is on.
Unfortunately my vibe board has some loose connection and only vibrated sometimes, so I had to test my code with an LED light instead.


Here's what my setup looked like (since I can't take pictures of sound).
![Help setup](https://21mdr1.github.io/img/jammin_setup.jpg)


##### A tip for next time:
Switches are digital input and thus only work with digitalRead and digitalWrite. Don't use analogRead and analogWrite.


