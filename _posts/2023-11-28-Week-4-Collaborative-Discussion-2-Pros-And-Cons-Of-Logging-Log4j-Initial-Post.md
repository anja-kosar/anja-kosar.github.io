---
layout: post
title: Network Security - Week 4 - Collaborative Discussion 2 - Pros and Cons of Logging - Log4j 
subtitle: Log4j Initial Post
categories: Week 2

---

## Collaborative Discussion 2 - Pros and Cons of Logging - Log4j - Initial Post
In this week students were required to research various literature on pros and cons of logging, particularly the impact of log4j.

POST:
Monitoring and logging is an important aspect of every day security, as it provides raw data that administrators and security teams use to identify potential threats. These mechanisms are basic security pillars that form the foundation of a robustly administered security framework. (Kiprin, B. 2021) Monitoring and logging is also beneficial to early detection of threats, incident response, threat intelligence and even compliance requirements, by implementing a security monitoring and logging program. For example, implementing the PCI DSS and GDPR standard which mandates that organizations that process credit card transactions maintain logs of all system activity. (Hiremat, O. N.D) However, if security logging and monitoring mechanisms are not properly implemented or maintained, they can be rendered ineffective, leaving organizations vulnerable to attacks. 
Although logging is an important aspect of security, it can also have it disadvantages too. This was discovered in December 2021, now known as Log4Shell in servers supporting the game Minecraft where bad actors have made millions of exploit attempts of the Apache Log4j 2 Java library. (Berger, A. 2023) Because this is a versatile, industrial-grade Java logging framework, it is used by 8% of the Maven ecosystem and listed as one of the top 100 critical open source software projects. 
The discovered vulnerability, published as CVE-2021-44228, enables a remote attacker to take control of a device online, as long as that device is running certain versions of Log4j 2. What made this vulnerability even more dangerous, is the fact that many companies and organizations, even governments, use the Log4j library in numerous applications, whether in web servers, web applications, network devices and other hardware and software. Some well known and identified companies are Amazon Web Services and VMware. 
Since the vulnerability has been discovered, Apache has issued software update patches in hopes to mitigate the vulnerability. Unfortunately, immediate patching is not viable in all scenarios. For example, products obtained from third-party vendors might contain vulnerable versions of the popular logging library that users cannot modify without updating the whole product, making them dependent on those vendors to release updates. (Constantin, L. 2021)

In some cases, improper implementation and configuration of security monitoring and logging systems may cause risks. In other cases, obtaining those same security monitoring and logging systems with vulnerabilities or weaknesses from vendors may also cause risks, regardless of what configuration you may implement. Taking this into consideration, it is important to for any organization to properly do research on existing current threats before they implement any security solution to their infrastructure. 


References:
Log4J, 2023 Log4j – Apache Log4j 2 – Logging Services. [online] Available at: https://logging.apache.org/log4j/2.x/. [Accessed 28 November 2023]

Berger, A. (2023). What is Log4Shell? The Log4j vulnerability explained (and what to do about it). [online] Dynatrace news. Available at: https://www.dynatrace.com/news/blog/what-is-log4shell/?utm_source=google&utm_medium=cpc&utm_term=log4j%20vulnerability%20explained&utm_campaign=uk-application-security&utm_content=none&gclid=CjwKCAjwiuuRBhBvEiwAFXKaNJd3hLzYlujXuVbTIP63_IioBFvzAYOePxfft2D6ded7EXfaTu4j4BoCrHAQAvD_BwE&gclsrc=aw.ds [Accessed 28 November 2023].

Hiremath, O. (N.D). Risk of Security and Monitoring Logging Failures. [online] Available at: https://www.softwaresecured.com/post/risk-of-security-and-monitoring-logging-failures. [Accessed 28 November 2023]. 

Constantin, L. (2021). 4 ways to properly mitigate the Log4j vulnerabilities (and 4 to skip). [online] Available at: https://www.csoonline.com/article/571789/how-to-properly-mitigate-the-log4j-vulnerabilities.html. [Accessed 28 November 2023].



Reflection:
This post was the most challenging out of all of the collaborative discussions, due to the fact that it is a completely new unexplored territory. I was not familiar with logging or the log4j breach. However, having done generous research on the topic, I became familiarized with various breach types, which initially I was not aware of being possible or existed.
