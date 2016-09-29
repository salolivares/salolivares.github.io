---
layout: default
title: Portfolio
---

### Java
During the summer of 2016, I had the amazing opportunity to intern at [ViaSat Inc.](https://www.viasat.com/){:target="_blank"}. I collaborated with another UCSB student to design, develop and test software made to automate the company software release pipeline in a continuous integration/development environment. The original process would involve an engineer taking approximately four hours to release a new software build. With the tools we built, that process was reduced to mere minutes. The engineer would run our command line tool or GUI tool, fill out a small number of fields, and the tool would take care of the rest. The command line tools were made so it can easily be integrated into continuous integration/development software (such as Jenkins, Travis CI, etc.), so releasing software would not require any action from the engineer. The GUI was built JavaFX following a model-view-controller software pattern.

[OpenCV HSV Color Converter](https://github.com/salolivares/hsvColorConverter){:target="_blank"} is what I consider to be my first real full scale side project. I came up with the idea for this tool when using OpenCV and trying to find what color I needed to track on my web cam feed. It was very tedious screen-capping my webcam, loading into Photoshop to find the color code, then converting to the OpenHSV format. The core feature of this tool is to convert RGB/HEX color codes to the OpenCV HSV color codes. Normal HSV ranges are the following: H = 0 - 360, S = 0 - 100 and V = 0 - 100 --- while OpenCV HSV ranges are: H: 0 - 180, S: 0 - 255, V: 0 - 255. The user simply inputs a color code they have, or uses the color picker on any image they've opened, and the converter will give them back an OpenCV complaint HSV color code. I learned how to use the Maven build tool, and wrote several unit tests with JUnit.

### Python
[SpooderBot](https://discordapp.com/oauth2/authorize?client_id=184537503284330496&scope=bot&permissions=133692435){:target="_blank"} is an asynchronous, multipurpose chat bot for the VoIP service [Discord](https://discordapp.com/){:target="_blank"}. It's built with Python 3.5 and implements several APIs to provide Discord members with music playing functionality (YouTube, Spotify) and image searches (GIPHY, Imgur). The bot also offers several administrative capabilities (point system, kicking/banning users, defining roles, etc) and debugging tools. Currently, SpooderBot is hosted on a inexpensive server running Ubuntu 16.04, used by two gaming communities with 50+ members, and its incredibly robust as it handles 20+ commands simultaneously with ease. 

### Sites
The following are some of the sites I've built over the years as an amateur web developer.

- [S.O. Plumbing Inc.](http://soplumbinginc.com/): Built with HTML, CSS, JS.
- [CodersSB](http://coderssb.com/): Built with Twig, HTML, CSS, JS. Managed with Grav CMS.
- [This Site](): First built using HTML, CSS, JS. Transitioned to self hosted Ghost blog. Now hosted on Github pages using Jekyll.