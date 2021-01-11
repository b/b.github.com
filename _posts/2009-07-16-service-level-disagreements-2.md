---
layout: post
title: "Service Level Disagreements, Part 2"
---

# {{ page.title }}

[Yesterday](http://blog.b3k.us/2009/07/15/service-level-disagreements.html), I explained the dangers of the common misunderstanding of service level agreements as insurance policies. While I mentioned a strategy of using multiple vendors rather than relying on the SLA offered by a single vendor, some more specific details will be useful in understanding and internalizing this approach.  
  
Over the past ten years I have participated in or lead negotiations for internet and CDN bandwidth at [Internap](http://www.internap.com), [Amazon](http://amazon.com), and [Microsoft](http://microsoft.com). At first I invested significant time and effort in defining SLAs, methodology, metrics, and penalties, as is common practice.  What eventually became apparent were two things:  
  
* Defining meaningful SLAs for public internet services, as opposed to private telco links, is not generally possible.
* SLA failure penalties are insufficient compensation for business impact.  
  
From this experience and these realizations I changed my approach significantly.  The two facets of the new strategy were, and are:  
  
* Only enter into contracts with as small a traffic commitment as feasible and with no penalties for termination, regardless of cause.  
* Engage multiple vendors for all bandwidth services.  
  
Availability, which is always the responsibility of the customer, is now actually under the customer's control, rather than being delegated to a vendor via an SLA.  Should a vendor fail to deliver the desired service level, even for a short period of time, traffic can be shifted to other vendors until quality improves.  Should a vendor prove too unreliable to use at all, their services can be terminated and other vendors brought in to replace them.
  
To make best use of this strategy it is important to have proper software support in place.  For example, a single CDN vendor should be used for content on each page served, and the vendor used varied dynamically across requests; mixing multiple CDN vendors on a single page can actually reduce availability.  Similar traffic engineering can be done for requests to your own web servers using DNS-based global load balancing, though with coarser granularity.  Similar principles will apply to "the cloud" as the interfaces and functionality in the space are commoditized.  
  
As Heinlein said, [TANSTAAFL](http://en.wikipedia.org/wiki/There_ain't_no_such_thing_as_a_free_lunch), and high-availability distributed systems are not exceptions.  __You are responsible for your availability__.  Understand clearly the business value to you of a vendor SLA and be prepared to change your strategy, and put in the technical and contract work required, if it will not meet your business needs.
