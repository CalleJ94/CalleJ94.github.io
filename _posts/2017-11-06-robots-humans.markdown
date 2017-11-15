---
layout: post
title:  "robots.txt and humans.txt!"
date:   2017-11-06 05:13:34 +0100
categories: jekyll update
comments: true
beskrivning: Här går jag igenom lite om vad en robort.txt är för något och hur jag har gjort på min sida och går även igenom min humans.txt
---

* **What is robots.txt and how have you configure it for your site?**  
robots.txt is used to give web robots instructions, in my robots.txt so have I put in:  
  *User-agent:* *  
  *Disallow:* /  
  *User-agent: Googlebot*  
  *Allow:* /  
  This means that all robots is disallow exept for Googlebot, so if Yahoos robot Slurp want to go in to my site, it will first go to robots.txt and see that it don't have access to the site. 

* **What is humans.txt and how have you configure it for your site?**  
  The humans.txt is used to let people know who is behind the website, in my txt file have I put in my name and were im from.
  