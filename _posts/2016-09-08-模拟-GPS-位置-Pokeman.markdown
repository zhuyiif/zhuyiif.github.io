---
layout: post
title:  "怎么在iOS上模拟GPX位置"
date:   2016-09-08 11:39:12 -0700
categories: iOS
---

前几个Pokeman Go太流行了，对我我这种懒人是不喜欢到处跑来跑去的，所以想到开发一个简单的应用模拟位置，
然后就可以在公司一直打怪升级了

# [Source Code](https://github.com/zhuyiif/location-simulation)  

# gps-simulation
Simulate locations using GPX files.  
This will only work if you run the app through Xcode, as it relies on the debug session.

## Usage

### Simulate Locations

* Select scheme ```gps-simulator``` -> Edit Scheme

* Select ```Allow Location Simulation```

* Choose a gpx file from the ```Default Location``` dropdown

* Run the project on your device

iOS is now cycling through the location points in the GPX file!

### Add GPX Files

* Add your GPX file to the project under the ```gpx-files``` directory

* Select scheme ```gps-simulator``` -> Edit Scheme
 
* Click on the ```Default Location``` dropdown and select your GPX file
* 

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
