---
layout: post
title: Network Security - Week 3 - Scanning Activity
subtitle: Scanning Activity
categories: Week 3

---

## Week 3 Scanning Activity

Throughout this Network Security (NS) module, from week 1, my fellow students and I were provided with a list of websites to choose from, which would be utilized throughout this module for various assignments. My website of choice was www.allthegear.org.uk, an e-commerce platform, specializing in sales of outdoor clothing and gear. The first assignment, due in week 3 of the module, was “Vulnerability Assessment - Baseline and Analysis Plan”. For more information on this assignment, you can refer to the post on the front page. 

The scanning activity can be considered as the second phase of the assignment. The results for this scanning activity will be utilized in one of the final assignments due at the end of the module, week 6. For this scanning activity, I was given a list of tools to use, such as Traceroute, dig and NsLookup, with further instructions, mainly:

1. How many hops from your machine to your assigned website?
2. Which step causes the biggest delay in the route? What is the average duration of that delay?
3. What are the main nameservers for the website?
4. Who is the registered contact?
5. What is the MX record for the website?
6. Where is the website hosted?

I used my Windows command prompt (cmd) to traceroute to the target website. The command I used was “tracert allthegear.org.uk”. The traceroute command ended in a total of 17 hops. The biggest delay was step 6 and 7, which resulted in “request timed out”. 
The main nameservers for the website are:

ns1.a2hosting.com
ns2.a2hosting.com
ns3.a2hosting.com
ns4.a2hosting.com

The registrar contact for the website is ENOM LLC, URL: https://www.enom.com 

The MX Record for the website is mail.allthegear.org.uk 

The website is hosted by A2 Hosting, Inc. located in Amsterdam, Netherlands. 


Throughout this scanning activity, I did not come across many challenges, other than taking some time to familiarize myself with using traceroute, as I had not used it before through the command shell. As part of my work investigations, I often use open source (OSINT) tools, which are open for use to anyone on the internet. These tools have many helpful tools that can find any information out about any domain. As the module progresses, I will do a further reflection as further scanning activities will be slightly different to this one, which will include Linux.



