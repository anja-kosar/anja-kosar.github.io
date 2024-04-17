---
layout: post
title: Security Risk Management – Week 7 – Collaborative Learning Discussion 2 – Initial Post
subtitle: Collaborative Learning Discussion 2 – Initial Post
categories: Week 7

--- 

## Collaborative Learning Discussion 2 – Initial Post

This week, students were introduced to various methods used as part of Quantitative risk modeling, some of which use probabilistic approaches such as Monte Carlo simulations and Bayes theorem-based methods, as well as multi-criteria decision analysis techniques such as TOPSIS, AHP and ANP.

As part of the Collaborative Learning Discussion 2, students were advised to read Spring et al (2021) and answer the following questions:
# What characteristics of CVSS do the authors criticize? Do you agree with the critique? 
# The authors also discuss a number of alternatives to CVSS. Select one of these alternatives and post an argument for why it should replace CVSS.

## Post

The Common Vulnerability Scoring System (CVSS) is a method used to supply a qualitative measure of severity. The method consists of three metric groups: Base, Temporal, and Environmental. The Base metrics produce a score ranging from 0 to 10, which can then be modified by scoring the Temporal and Environmental metrics. (NIST 2019). 

According to its creators, the Common Vulnerability Scoring System (CVSS) “provides a way to capture the principal characteristics of a vulnerability … reflecting its severity … to help organizations properly assess and prioritize their vulnerability management processes, however it scores severity not security risk, leaving potential gaps in security. A significant problem is that the CVSS formula, which is used to calculate scores, is not adequately justified. This is because, in technical terms, the formula states that "faster + fastest = 6," and the specification has the task of proving this. This means that context, implications, and operational issues with scoring are not taken into consideration by the algorithm. (Spring et al 2021)

Having read the above article, although CVSS is a well-established method, I agree that there are loopholes surrounding risk assessment. 
As a way forward, Spring et al 2021 mentioned an alternative method, SSVC (Stakeholder-Specific Vulnerability Categorization), introduced to the cyber security market in April 2021 by security researchers at Carnegie Mellon University’s Software Engineering Institute (SEI) and the Cybersecurity and Infrastructure Security Agency (CISA), as a method to help security analysts and vulnerability managers with vulnerability prioritization decision making, by implementing a CISA SSVC calculator, which contains 36 funnel decisions in total.  (Keizman, O. 2024). Because SSVC depends on an organization's manual input of values, each suggested choice is exclusive to that firm and its unique vulnerability. It's crucial to remember that scaling SSVC is more difficult due to the human labor required. 




# References:
NIST (2019). NVD - Vulnerability Metrics. [online] Nist.gov. Available at: https://nvd.nist.gov/vuln-metrics/cvss. [Accessed 18 March 2024].

Spring, J., Hatleback, E., Householder, A., Manion, A. and Shick, D. (2021). Time to Change the CVSS? IEEE Security & Privacy, [online] 19(2), pp.74–78. doi: https://doi.org/10.1109/msec.2020.3044475 [Accessed 18 March 2024].  

CISA Stakeholder-Specific Vulnerability Categorization Guide. (n.d.). Available at: https://www.cisa.gov/sites/default/files/publications/cisa-ssvc-guide%20508c.pdf. [Accessed 18 March 2024].  

Keizman, O. (2024). The SSVC risk prioritization method: what it is, when to use it, and alternatives. [online] Vulcan Cyber. Available at: https://vulcan.io/blog/the-ssvc-risk-prioritization-method-what-it-is-when-to-use-it-and-alternatives/ [Accessed 18 March 2024].
