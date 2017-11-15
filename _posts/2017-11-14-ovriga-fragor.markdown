---
layout: post
title:  "Övriga frågor"
date:   2017-11-14 18:05:00 +0100
categories: jekyll update
comments: true
image: http://www.robotstxt.org/static/robotstxtwrap.png
---

# Övriga frågor till examinationen

* __Vad är robots.txt och hur har du konfigurerat den till din sajt?__

  Robots.txt ger instruktioner till web-bottar om vilka delar av sajten de har tillåtelse att besöka i olika syften.
  Då min statiska sida inte ämnar till att någon annan än jag eller kursansvariga så har jag inte gett någon robot tillåtelse till nån del av sajten.
* __Vad är humans.txt och hur har du konfigurerat den till din sajt?__

  Humans.txt ämnar till att berätta kort om människorna bakom hemsidan. Den är bara till för att ge en mänskligare touch till den och jag har angett mitt namn, min twitter, vart jag kommer ifrån, vilken IDE jag har använt bl. a.
* __Hur implementerade du kommentarer till dina blogposts?__

  Jag använde Disqus för att genom deras server kunna visa kommentarer på mina posts. Jag kan själv styra i YAML om jag ska ha kommentarer på specifika posts genom att ange "comments: true/false"
* __Vad är Open Graph och hur använde du den?__

  Open Graph är ett protokoll skapat av Facebook för att kunna ge en förhandsvisning av en länk när man delar den på bl a sociala medier och chattplattformar. Jag använder den genom att ta "title" från posten automatiskt och "image" genom en image-tag i YAML där jag anger en specifik bildlänk för varje post.