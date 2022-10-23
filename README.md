# config
i3wm config and additional tools

This repository is dedicated to <a href="https://i3wm.org/"><b>i3</b></a> window manager and additional tools i use or i've used, which helps make desktop environment look better then default.


> I don't have much experience with [tiling window managers](https://en.wikipedia.org/wiki/Tiling_window_manager) so i am still getting used to.
 
## [I3status](https://i3wm.org/docs/i3status.html)

I3wm has a default status bar(i3status). After installation status bar looks like this:


![i3status](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftau.gr%2Fimg%2F2020-02-23%2Fi3status1.png&f=1&nofb=1&ipt=75bae021250047f974490caaa8ffaba9418e9c2fd9eaa121d9f72f4e892c8178&ipo=images)


Status bar consits of separated by pipe sections, which shows different data(etc. cpu, battery status, wlan).
I3status has few [possibilities](https://i3wm.org/docs/i3status.html) for customization. 

In terms of customization i3status is quite boring so i quickly removed to [i3blocks](https://github.com/vivien/i3blocks).

## [I3blocks](https://github.com/vivien/i3blocks)

I3blocks became next status bar i've used. He gives you more apportunity for customization.

Default i3blocks bar looks like i3status. There are the same sections with data. Unlike i3status here you can create your own script, which will show useful information.

>[Here](https://github.com/vivien/i3blocks-contrib) you can find scripts, which was already wrote. Nobody forbids you to write your own script using Bash, Perl, Python or other language.


After all configuration my status bar:

![image](http://www.nalijm.org/i3blocks.jpg)

File *i3blocks.conf* contains discription and links to the scripts, which are executed when i3blocks starts.

## [I3lock](https://github.com/i3/i3lock)

Since i3 was installed i've been using default i3lock. I've found several solutions how to make/change default lockscreen. 

First: [betterlockscreen](https://github.com/betterlockscreen/betterlockscreen). But for some reasons it doesn't work.(distor: debian 11). I'm trying for find out something.

Second: [i3lock-color](https://github.com/Raymo111/i3lock-color) i use now. It is much better then default(white lock screen).
