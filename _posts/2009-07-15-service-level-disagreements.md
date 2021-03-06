---
layout: post
title: "Service Level Disagreements"
---

# {{ page.title }}

Vijay posted a (better late than never) [rebuttal](http://vijaygill.wordpress.com/2009/07/15/cloud/) to a [post from November last year](http://www.hpcinthecloud.com/hpccloud/2008-11-03/10_reasons_why_telcos_will_dominate_enterprise_cloud_computing.html) by Joe Weinman of AT&T.  I agree with all the points Vijay makes, and want to focus in on a particular area of Joe's article:  
  
> (4) SLAs with financial penalties -- Not only won't enterprises accept "Well, after all, it's still in beta" as an excuse for service outages, they demand meaningful SLAs (service level agreements) with clear metrics for evaluating achievement of those SLAs, backed up by monitoring and management systems, and financial penalties such as credits or refunds if service levels aren't met. A "free" or low-cost service with questionable delivery quality is about as attractive to a CIO as an offer of free neurosurgery from someone who just skimmed a blog on how to do it in three easy steps.
  
Ah, the mighty service level agreement!  The tooth and claw by which the wily customer brings the vendor to heel.  Get the SLA right and you, the customer, can sit back and relax, safe in the knowledge that should there be an outage, you are covered.  Your business is protected from harm by the warm, experienced embrace of a big, stable telco.  Pinch me, I must be dreaming.  
  
Vijay refers to SLAs as "an actuarial game".  The situation is rather worse than that.  The trouble is that many intelligent people mistake an SLA for an insurance policy.  It most definitely is not.
  
An insurance policy is purchased for a price, often based on actuarial tables, that reflects the risk of the policy being paid out and the size of the pay out.  The value of the policy is that it is a hedge: in the event of a claim, the holder is compensated for (approximately) the full value lost.  The insurance industry is predicated on most policy holders paying far more over the life of their policies than they are paid out, and on there not being catastrophic events that cause simultaneous claims by a large number of policy holders.  
  
A service level agreement does not work this way.  An SLA is not a hedge against the business impact of an outage: it is a refund policy.  The maximum value of an SLA 'claim' is your monthly bill.  The cost to your business of an SLA failure is likely to be far higher, but you will not be compensated for that loss.  A six hour service outage might cost your small business 10,000 dollars.  receiving a 500 dollar service credit is cold comfort.  
  
SLA failures become more common as you move up the stack from the rigid, extremely well-characterized, layer 1 telco sweet spot.  Outages that impact large sections of your customer base simultaneously are inevitable in large-scale, shared software infrastructure.  If SLAs were insurance policies, vendors would quickly be out of business.
  
Given this, the question remains: how do you achieve confidence in the availability of the services on which your business relies?  The answer is to use multiple vendors for the same services.  This is already common practice in other areas: internet connection multihoming, multiple CDN vendors, multiple ad networks, etc.  The cloud does not change this.  If you want high availability, you're going to have to work for it.
