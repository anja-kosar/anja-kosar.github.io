---
layout: post
title: Security Risk Management – Week 4 – Seminar 3 – Threat Modeling Exercises
subtitle: Threat Modeling Exercises  
categories: Week 4

--- 

## Threat Modeling Exercises

This week, students were expected to carry out a Week 4 Seminar activity during which the prepared format of choice would have been discussed during the seminar. 
The activity instructions were to read the Spears & Barki (2010) article and prepare answers to the following questions:
Read Shostack (2018) chapters 3-5 (that cover STRIDE and DREAD, Attack Trees and Attack Libraries) as well as Spring et al (2021) (that discusses the history and some failings with CVSS) and then create a threat model based on a chosen scenario. 

#For the purpose of the exercise, my choice of scenario was a large international bank based in the UK, using the STRIDE and Attack Trees. 

## STRIDE
STRIDE - STRIDE was created by Loren Kohnfelder and Praerit Garg in 1999 as an acronym for Spoofing, Tampering, Repudiation, Information disclosure, Denial of service, and Elevation of privilege, to pinpoint possible vulnerabilities and threats in company products. Microsoft's STRIDE methodology is designed to guarantee that an application satisfies the security criteria of Confidentiality, Integrity, and Availability (CIA), in addition to Authorization, Authentication, and Non-Repudiation. Over time, STRIDE has developed to incorporate new tables for specific threats and its variations STRIDE-per-Element and STRIDE-per-Interaction.
The benefit of using STRIDE is that it enables organizations to assess systems and networks, categorizing potential threats in a ranked order, considering both their probability and potential severity. (Allen-Addy, C. 2023)

#Spoofing: Recognize possible risks associated with unauthorized entry to sensitive customer data or financial information by using identity spoofing. Think about situations in which attackers pretend to be real users in order to access private banking systems or customer accounts.
#Tampering: Assess the potential dangers of maliciously tampering with transaction data, account balances, or other vital information within the bank's system. Evaluate weaknesses that may result in unauthorized changes to financial records or transactions.
#Repudiation: Examine the risks associated with repudiation, where users refuse to acknowledge their participation in transactions or activities within the banking system. Think about situations where there are no non-repudiation mechanisms, making it challenging to demonstrate the genuineness of transactions. (Xin, T. and Xiaofang, B. 2014).
#Information Disclosure: Recognize possible risks related to unauthorized entry to sensitive customer information, account specifics, or transaction records. Evaluate weaknesses that may result in data breaches and expose confidential information to unauthorized individuals.
#Denial of Service: Assess the potential risks of denial of service attacks on the online services, ATMs, or other essential systems of banks. Think about situations in which enemies disrupt banking functions by flooding systems with too much traffic or requests.
#Elevation of Privilege: Evaluate the risks associated with unauthorized individuals obtaining higher-level permissions in the bank's systems, enabling them to circumvent security measures. Recognize weaknesses that may result in unauthorized entry to administrative features or confidential information. (Xin, T. and Xiaofang, B. 2014).



## Attack Trees
Attack trees are conceptual diagrams that show the variety of ways in which something can go wrong, and the reason why they might go wrong. Attack trees use a hierarchical representation of the steps needed for a successful attack. Each of the steps gives a requirement for completion for the step linked above it, where a successful attack is a complete set of requirements from the nodes at the bottom of the tree to those at the top. Each path in the tree should be unique, and there should be no loops in the design. (NCSC, N.D)

#Identify Key Assets: Including customer information, financial transactions, online banking platforms, and confidential data.
#Define Root Threats: Identify the main risks that could jeopardize the safety of the bank's assets, like data breaches, unauthorized entry, fraud, or denial of service attacks.
#Construct Attack Trees: 
#Root Node: Begin by addressing the primary danger, such as a potential data breach or unauthorized entry.
#Intermediate Node: Break down the primary danger into smaller threats or potential attack situations that may result in the main threat.
#Leaf Nodes: Divide each middle node into more detailed attack actions or events that might take place.

#Evaluate Attack Paths: Examine how various attack situations may result in vulnerabilities being taken advantage of in the bank's systems. Think about different ways attackers could try to breach the bank's assets and operations.
#Mitigate Strategies: Examine how various attack situations may result in vulnerabilities being taken advantage of in the bank's systems. Think about different ways attackers could try to breach the bank's assets and operations.
#Risk Assessment: Evaluate the probability and consequences of every recognized threat scenario on the bank's functioning and image. Determine the level of risk related to various paths of attack in order to efficiently prioritize security measures. (Fraile, M., Ford, M., Gadyatskaya, O., Kumar, R., Stoelinga, M. and Trujillo-Rasua, R. N.D). 




# References:
www.iriusrisk.com. (n.d.). Threat Modeling Methodology: STRIDE. [online] Available at: https://www.iriusrisk.com/resources-blog/threat-modeling-methodology-stride. [Accessed 15 March 2024]

www.ncsc.gov.uk. (n.d.). Using attack trees to understand cyber security risk. [online] Available at: https://www.ncsc.gov.uk/collection/risk-management/using-attack-trees-to-understand-cyber-security-risk. [Accessed 15 March 2024]

Satori. (n.d.). The STRIDE Threat Model. [online] Available at: https://satoricyber.com/glossary/the-stride-threat-model/. [Accessed 15 March 2024]

Xin, T. and Xiaofang, B. (2014). Online Banking Security Analysis based on STRIDE Threat Model. International Journal of Security and Its Applications, 8(2), pp.271–282. https://doi.org/10.14257/ijsia.2014.8.2.28. [Accessed 15 March 2024]

Saxena, P., Bhandari, S. and Patel, R. (2022). Business, Management and Economics Engineering MODELING THREAT TREES THROUGH STRIDE MODEL CONCEPT FOR THE BANKING SECTOR. [online] Available at: https://businessmanagementeconomics.org/pdf/Priti%20Saxena.pdf [Accessed 15 March 2024]. 

Fraile, M., Ford, M., Gadyatskaya, O., Kumar, R., Stoelinga, M. and Trujillo-Rasua, R. (n.d.). Using attack-defense trees to analyze threats and countermeasures in an ATM: A case study. [online] Available at: https://www.gmv.com/sites/default/files/content/file/2020/05/19/1/poem_atm.pdf [Accessed 15 March 2024].




