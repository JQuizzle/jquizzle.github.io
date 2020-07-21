---
layout: post
title:  "Making Progress"
date:   2020-07-20 06:48:00 -0700
categories: update
description: "Expanding the capabilities of this blog"
image:
---
Quick update. 

Added lazy loading via [Lozad.js](https://www.npmjs.com/package/lozad) integration. This will be useful for when I add images and eventually image galleries to this site. Speaking of images, I’ve decided to go with [BunnyCDN](http://bunnycdn.com) to host these files. I signed up for their free trial to play around. So far, I like what I'm seeing.

Why a CDN? Well, I wasn’t sure why either until I did some research. Right now, I need a place to store image files and deliver them to the requesting user. There's no need for server-side processing, databases, or anything else a person needs a server for.

However, if there is a future need for a server, I’ll probably go with an on-demand GCE instance. But that’s a post for another time.