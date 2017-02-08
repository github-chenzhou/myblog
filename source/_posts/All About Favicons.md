---
title: All About Favicons (And Touch Icons)
date: 2016-4-20
tags:
 - javascript
 - 前端资源
 - 标准参考
 - 转载
categories:
 - 前端基础
 - 前端资源
---

All About Favicons (And Touch Icons)

[All About Favicons (And Touch Icons)](https://bitsofco.de/all-about-favicons-and-touch-icons/)
[转载地址](https://bitsofco.de/all-about-favicons-and-touch-icons/)

This week I decided to look into the proper ways to use site favicons (and by extension, mobile "touch icons") across browsers. Although there are already quite a few articles on this topic, I decided to write this post as a way for me to bring together everything I have researched and present it in an easy to understand format for myself and, hopefully, you.

The Basics

The favicon (favourite icon) is an image used by browsers to represent a web page. It is typically 16x16 pixels, but varying and larger sizes are now more frequently required due to browsers using them in a growing number of ways -

The address bar
The links bar
Bookmarks
Tabs
Desktop icon
If we do not specify where to find the favicon, all major browsers (as early as IE5) will by default search for a file named "favicon.ico" in the website's root directory. This means that we technically do not need to declare anything else to have a working favicon.

However, using the ico format can be limiting. It doesn't support transparency, and isn't the most optimized for the web. Nowadays, we are able to use a wider range of formats including png, gif, jpeg, and, in limited circumstances, svg.