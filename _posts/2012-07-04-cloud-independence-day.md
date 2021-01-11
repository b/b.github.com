---
layout: post
title: "Google Compute Engine - Cloud Independence Day"
---

# tl;dr

You're in a rush, so I'll summarize the rest for you:

The [Google Cloud Platform](http://cloud.google.com/products/compute-engine.html) is the biggest deal in IT since Amazon launched EC2 and will cause the cloud market to explode.
  
## Google is Real

The Google Cloud Platform, now synonymous with Google Compute Engine, is the biggest deal in IT since Amazon launched EC2 and will completely alter the cloud market in at least two fundamental ways:
  
* We now have a utility market
* We now have true competition
  
The first will cause an explosion in adoption, especially by enterprise customers.  You want to build a 99.99%+ availability system on top of something that has 99.9% availability?  Well, you better have more than one, and now you do.  Here comes the hockey stick!  The second will result in all the usual competition benefits of more aggressive innovation and better prices for customers.
  
During the initial, private beta for EC2, the same point GCE is now, much of the focus for trial customers was what we would now call Big Data, like batch oil exploration simulations.  Beyond that, AWS was exactly two services: S3 and EC2.  It turns out you can get a hell of a lot done with just compute and object storage.
  
Now take a look at what Google already has for services:
  
* Cloud Engine is a lot like EC2 & EBS
* Cloud Storage is a lot like S3
* Cloud SQL is a lot like RDS
* Analytics can be used like CloudWatch (and I know of people putting billions of their own data points in Analytics)
* BigQuery has no AWS equivalent, but maybe you could build it with EMR?
* PageSpeed has no AWS equivalent
  
Just from that list, we can see Google is coming out of the gate years ahead of where AWS started.  And with 600k+ cores, GCE is about 50x bigger.  That is more servers than all but a handful of companies have, and still a tiny fraction of Google's infrastructure.  They also had the benefit 5 of years watching and learning from Amazon, in addition to their prodigious technical capabilities and vast infrastructure.  Beyond these existing services, they have quite a bit of their own infrastructure just begging to be turned into additional products:
  
* A massive CDN that supports YouTube, a video streaming site you might know -> CloudFront
* A sophisticated DNS/traffic management infrastructure (point your resolver at 8.8.8.8 and you are on it) -> Route 53
* A software load-balancing system supporting everything of theirs you touch -> ELB
    
How long until these are available to the public and Google has an IaaS offering that rivals AWS in both functionality and scale?  Well, you already know what I think.  It is happening, and fast.
  
## And so...

A lot of the chatter I've seen on Twitter and blogs appears to be written by people with don't know or dismiss the enormous advantages Google has in this space and forget what AWS looked like at the start.  
  
You might be tempted to think this isn't Google's core business.  People said the same thing when Amazon launched AWS.  Google makes money on ads, but they are an infrastructure company, just as Amazon makes money selling books, but they are an infrastructure company.  These are infrastructure companies productizing their infrastructure and expertise for consumption by everyone.  This is big, planetary scale infrastructure.  This is cloud legitimized and super-sized.
  
In the words of the prophet: [Shit just got real](http://somethingjustgotreal.com).
