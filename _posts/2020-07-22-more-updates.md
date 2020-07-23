---
layout: post
title:  Getting Ready for Photos
date:   2020-07-22 20:52:00 -0700
categories: photography update
description: "More features optimize the photo blog experience"
image:
---

Most of the fun of starting a new development project is getting everything setup. Right now, I’m focusing on setting up features around photo gallery management and viewing.

In the last few commits, I added Lozad.js. However, I was having trouble integrating [Photoswipe](https://photoswipe.com). After some research, I came across [this post](https://blog.bitsrc.io/lazy-loading-images-using-the-intersection-observer-api-5a913ee226d), which included using `IntersectionObserver` with lazy loading. After spiking on this for about an hour, I got it working and was happy with the results.

So I removed Lozad, added the script with `IntersectionObserver`, implemented image lazy loading, and Photoswipe. So, with all this implemented, I suppose I’ll get to creating real content at some point in time. But first, I need a design!...
