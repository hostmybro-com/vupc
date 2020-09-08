# 



<img src="file:///Users/michaelpintos/Downloads/Webp.net-resizeimage%20(1)%20(1).png" title="" alt="Webp.net-resizeimage (1) (1).png" data-align="center">

# **VUPC**

> WebRTC screensharing Electron app for Mac OS - Linux - Windows

## Table of contents

* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)
  
  ## General info
  
  VUPC is an open source screen sharing + remote collaboration application for Mac OS, Linux, Windows. You can share your desktop with someone else while letting them share your mouse and keyboard remotely. Right now it is not as good as commercial alternatives, mostly because this initial prototype was written in 3
  
  days. [The big difference is that you can send PRs to make VUPC better!]([machester4/vupc · GitHub](https://github.com/machester4/vupc)
  
  ## Screenshots
  
  ![Example screenshot](/Users/michaelpintos/Desktop/Captura%20de%20Pantalla%202020-09-08%20a%20la(s)%2009.48.43.png)
  
  ## Technologies
* Electron - version 9.0
* VueJS - version 2.6
* NodeJS - version 13.9
  
  ## Setup
  
  You can download the binaries already compiled, or you can compile a local version yourself.
  
  ## Building the app
  
   **Requirements**
  - MacOS - XCode
  - Windows - 
  - Linux - 
  
  
  
  Clone repository :
  `git clone git@github.com:machester4/vupc.git`
  
  
  
  Install server dependencies :
  
  `cd server && yarn`
  
  
  
  Install app dependencies :
  
  `cd app && yarn`
  
  
  
  run server :
  
  `cd server && yarn run start:debug`
  
  
  
  run app :
  
  `cd app && yarn run electron:serve`
  
  
  
  ## Features
  
  List of features ready and TODOs for future development
* Share screen
* Mouse click event in host
  To-do list:
* Keyboard events in host
* Your ideas :)
  
  ## Status
  
  VUPC is currently **ALPHA STATUS** and is intended for developers/early adopters. Check out the Issues to get involved. VUPC is a volunteer run project, your contributions and improvements are welcome!
  
  ## Inspiration
  
  This project is inspired by [ScreenCat]([GitHub - maxogden/screencat: :cat2: webrtc screensharing electron app for mac os (Alpha)](https://github.com/maxogden/screencat)) which was discontinued a long time ago.
  
  ## Contact
  
  Created by [@machester4]([machester4 (Michael Pintos) · GitHub](https://github.com/machester4)) - feel free to contact me!

### MIT License

