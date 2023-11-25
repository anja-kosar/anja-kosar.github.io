---
layout: post
title: Network Security - Week 3 - Scanning Activity
subtitle: Scanning Activity
categories: Week 3

---

## Week 3 Scanning Activity

Throughout this Network Security (NS) module, from week 1, my fellow students and I were provided with a list of websites to choose from, which would be utilized throughout this module for various assignments. My website of choice was www.allthegear.org.uk, an e-commerce platform, specializing in sales of outdoor clothing and gear. The first assignment, due in week 3 of the module, was “Vulnerability Assessment - Baseline and Analysis Plan”. For more information on this assignment, you can refer to the post on the front page. 

The scanning activity can be considered as the second phase of the assignment. The results for this scanning activity will be utilized in one of the final assignments due at the end of the module, week 6. For this scanning activity, I was given a list of tools to use, such as Traceroute, dig and NsLookup, with further instructions, mainly:

•	How many hops from your machine to your assigned website?
•	Which step causes the biggest delay in the route? What is the average duration of that delay?
•	What are the main nameservers for the website?
•	Who is the registered contact?
•	What is the MX record for the website?
•	Where is the website hosted?

I used my Windows command prompt (cmd) to traceroute to the target website. The command I used was “tracert allthegear.org.uk”. The traceroute command ended in a total of 17 hops. The biggest delay was step 6 and 7, which resulted in “request timed out”. 
The main nameservers for the website are:

ns1.a2hosting.com
ns2.a2hosting.com
ns3.a2hosting.com
ns4.a2hosting.com

The registrar contact for the website is ENOM LLC, URL: https://www.enom.com 

The MX Record for the website is mail.allthegear.org.uk 

The website is hosted by A2 Hosting, Inc. located in Amsterdam, Netherlands. 



