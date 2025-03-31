---
title: "Day 21 - technical issues"
date: 2020-04-05
categories: 
  - "42"
tags: 
  - "quarantine"
---

This week is topping the charts re: technical issues. First was figuring out how to transfer everything from my old laptop to my new one. I really wanted to get this done ASAP, as I'm giving my old laptop to a friend for her son to use for school. Then, it was uploading images for my blog post on Friday night, and last night, it was Disney+.

I did finally get the laptop situation worked out. My airport / time capsule hadn't been turned on in about 4 or 5 years, so once I got that reset and running it was just a matter of waiting (and waiting and waiting) first for the backup, and then for the restore onto the new machine.

Disney+ on the other hand, those are technical issues on their side, so not much I can do about it. I get Disney+ for free, so maybe I shouldn't complain, but it's annoying when it tells me I have an internet issue when Netflix and Hulu work just fine. And then when it stopped complaining about my internet, it played the movie, but with no sound. Ugh. I almost gave up and then it decided to work.

Today, I am back to the blog issue. The support tech who helped me Friday night couldn't figure it out, so he escalated my ticket for me. The suggested solution -- take a screenshot of my photos and post that instead. Um... no.

So, I've been poking around and seeing if I could figure it out on my own. First step -- debug mode. This clearly indicates an issue --

> **Fatal error**: Maximum execution time of 30 seconds exceeded in **/public\_html/wp-includes/class-wp-image-editor-imagick.php** on line **355**.

I tried turning off all the plugins, changed the theme, nothing helped. I finally found an article on the WP forums -- "This usually means your host is taking too long to process the derivative images (thumbnails, etc.) when you upload your files." I emailed the tech guy back, asked him to look into that and also to see if we can update PHP (I have a shared hosting solution, so I can't just go update that myself). We'll see what he says! If they can't figure this out, I may have to consider switching hosting providers. Anyone using something they like? I had GoDaddy for awhile, but I really really don't want to go back there, so any other suggestions?
