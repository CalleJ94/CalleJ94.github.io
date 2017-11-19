---
layout: post
title:  "robots.txt and humans.txt!"
date:   2017-11-06 05:13:34 +0100
categories: jekyll update
comments: true
beskrivning: Här går jag igenom lite om vad en robort.txt är för något och hur jag har gjort på min sida och går även igenom min humans.txt
---

* **What is robots.txt and how have you configure it for your site?**  
Robots.txt används för att ge web robotar instruktioner, i min robots.txt så la jag in:  
  *User-agent:* *  
  *Disallow:* /  
  *User-agent: Googlebot*  
  *Allow:* /  
  Detta gör att alla web robotorn inte har tillträde förutom Googlebot, så om Yahoos robot Slurp skulle vilja gå in på sidan så får den inte det. 

* **What is humans.txt and how have you configure it for your site?**  
  Humans.txt används för att tala om vem som har skapat webbsidan, är ungefär samma sak som eftertexterna på en film, i min humans så la jag till mitt namn och vart jag är ifrån.
  