---
layout: post
title:  "p5js-schooltimetable"
date:   2017-04-08 11:40:42 +0100
categories: p5js
comments: true
---
![Imgur](http://i.imgur.com/itEzXbv.png)<br>

One of my biggest projects on P5js so far has been a project to help me keep track of what the current lesson is at school.<br> Without a bell system in the school and a technician that doesn't have a lesson timetable it can be difficult keeping track of what lesson it is.

I decided that a p5 project could help me out with this.<br>
I have learnt a great deal doing this project about:
  - working with javascript date function
  - Calculating remaining time
  - Using my own JSON file as data input
<!--more-->
Once I had a rough working version. I then decided that really I need to have this as a desktop application. Which then lead me to explore ways of packaging a javascript app.

I first discovered node.js, this allowed me to create a basic webserver to run the app, then AppJS to make a Windows executable. I eventually settled on Electron which is kind of a sucessor to AppJS, as AppJS is now depreciated.

The next stage in the project has been releasing the software to various member of the team. Getting valuable feedback which has resorted in bug fixes and already 2 new features that I hadn't thought about.

The application is still evolving and I recommend to anyone starting out in programming is to think about a tool that would make you day to day life easier that you currently don't have. Try making it, dont worry if you don't have a full picture of what you need to do, that is part of the journey and learning code. Then share it with others, its great getting peoples feedback, good or bad.
