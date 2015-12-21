---
layout: page
title: "Getting started"
category: tutorials
date: 2015-12-18 23:19:00
---

### Install Arduino

- Install [Arduino.](https://www.arduino.cc/en/Main/Software)
 - Version of Arduino must be supported by Teensyduino. Compatible versions are shown on the [Teensyduino page.](http://pjrc.com/teensy/td_download.html)

### Install Teensyduino

- Install Teensyduino from [pjrc.com.](http://pjrc.com/teensy/td_download.html)

### Download your first program

- Plug in Teensy via USB.
- Open Files >> Examples >> Teensy >> Tutorial1 >> Blink
- Modify the *ledPin* definition to the correct pin number as described by the comment next to the line of code.

~~~
// Teensy 2.0 has the LED on pin 11
// Teensy++ 2.0 has the LED on pin 6
// Teensy 3.0 has the LED on pin 13
const int ledPin = 11;
~~~

- Click Upload.

If successful, you will see the onboard Teensy LED flashing slowly.