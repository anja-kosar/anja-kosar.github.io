---
layout: post
title: Network Security - Week 4 - Scanning Activity
subtitle: Kali Linux 
categories: Week 4

---

## Network Security - Week 4 - Scanning Activity
In this week, students were provided with a scanning activity which related to our chosen websites. For the purpose of the activity, I used a combination of Kali Linux tools, as well as some open-source tool kits. The information gathered is as follows:

-	What Operating System does the website utilize?
This website is currently running on Apache OS.

-	What Web Server software is it running?
This website is running on Apache HTTP Server, version unknown, however PHP version 7.4.33 which is now considered as ‘outdated’ with current version in use being 8.2. According to cvedetails.com and tenable.com, version 7.4.33 is no longer considered safe with multiple vulnerabilities identifies surrounding this version. 

-	Is it running a CMS (Wordpress, Drupal, etc)?
This website is currently using Magento CMS.

-	What protection does it have (CDN, Proxy, Firewall)?
According to the WhatWaf tool in Kali Linux, this website uses ‘CloudFront Firewall (Amazon)’.

-	Where is it hosted?
This website is hosted by A2Hosting.

-	Does it have any open ports?
According to Nmap on Kali Linux, below open ports were identified:

PORT (TCP)	STATE	SERVICE
21	Open	  Ftp
53	Open	  Domain
80	Open	  Http
110	Open	  Pop3
143	Open	  iMap
443	Open	  Https
587	Open	  Submission
993	Open	  iMaps
995	Open	  Pop3s
3306	Open	Mysql
5060	Open	Sip
8080	Open	Http-Proxy

-	Does the site have any known vulnerabilities?
Vulnerabilities found for server-side software. As mentioned above the PHP outdate as well as below CVE’s:
CVE 2015-9251 jquery
CVE 2019-11358 jquey
CVE 2020-11023 jquery
CVE 2020-11022 jquery
CVE 2022-34253 magento
CVE 2022-42344 magento
CVE 2022-34254 magento
CVE 2022-34256 magento
CVE 2022-24086 magento

Cookie vulnerability:
Cookie Name: PHPSESSID which is a subdomain cookie. Vulnerable websites under the main domain may access these cookies and use the victim session on the main site. 

No cookie consent and preference policy met.

The X-Content-Type-Options header is not set. This could allow the user agent to render the content of the site in a different fashion to the MIME type

No password policy advised to clients.


Reflection:
This activity as much as it was the most challenging, was the most fun and beneficial as well. This activity expanded on my use of Kali Linux tool and was the first time I used them for website vulnerability assessments. I did not have as many challenged as I thought I would have within Kali Linux itself, perhaps because I do have some background knowlegde of Kali due to work environments. Evene though I have never used the tools in this capacity, it was a smooth sail. The challenge aspect of it arised when I obtained the scanning results, I was not familiar with what they meant, causing a lot of research and explorations of CVE databases to learn mitigations. By doing so, I obtained a further broaded concept of website development, from  a different perspective other than just typing out HTML.

