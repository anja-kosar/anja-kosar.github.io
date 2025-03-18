---
layout: post
title: Research Methods & Professional Practice, Week 7, Assignment 1, Literature Review
subtitle: Assignment 1, Literature Review
categories: Week 7

--- 

## Assignment 1

## Literature Review

Literature review on app development for emergency services (healthcare). 

Research Question: How do emergency service mobile applications integrate with existing emergency systems? Focusing on interoperability challenges. 

Author: Anja Kosar
Student ID: 12692515
Module: Research Methods and Professional Practice
University of Essex
MSc Cyber Security

1.	Introduction
This literature review examines the evolving field of emergency healthcare, highlighting the integration of mobile applications into emergency healthcare systems, which have the potential to significantly improve response times, patient outcomes, and overall healthcare delivery in critical situations. In particular, mobile technology has emerged as a powerful resource in various healthcare settings, facilitating immediate access to critical information and enabling healthcare providers to deliver high-quality care (Mosa et al., 2012).  The term app, a shortened form of application, describes a self-contained software program created to perform a specific function. These programs are typically optimized for use on mobile devices, such as smartphones, tablets, and certain wearable technologies like smartwatches. Mobile health (mHealth) applications are a category of apps specifically developed to support healthcare by offering various features aimed at improving patient health. These apps come in a wide range of designs and functionalities. Currently, there are over 165,000 mHealth applications, both free and paid, publicly accessible on major app distribution platforms (Kao et al., 2017).

The evolution of mHealth can be traced back to the early applications of mobile technology in healthcare, primarily focused on remote monitoring and communication. As noted by Free et al. (2013), early mHealth initiatives in the 2000s centered on using SMS messaging for appointment reminders and medication adherence (Free et al., 2013). As smartphone technology advanced, mHealth expanded to encompass a wider range of applications, including remote patient monitoring, chronic disease management, and access to health information (Steinhubl et al., 2013). By the early 2010s, the increasing availability of app stores facilitated the development and dissemination of numerous health-related apps, transforming mobile devices into powerful tools for both patients and healthcare providers (Ventola, 2014).

However, healthcare app development is not without challenges, despite its promise of transformative solutions (EMB, 2023). The integration of these apps into existing healthcare infrastructure faces its own challenges, interoperability. In healthcare, interoperability refers to the ability of different health information systems and technologies to communicate, exchange, and use data effectively, regardless of geographical location (Lindquist, 2024). In emergency services, interoperability is particularly crucial as it allows different emergency systems—such as ambulance services, hospitals, and emergency dispatch centers, to work together during time-sensitive situations. Therefore, developers often find themselves in a complex situation, from ensuring seamless interaction between different healthcare systems to navigating a web of regulations. The diversity of data formats and standards as well as communication protocols pose challenges for developers. The challenge is to create a unified ecosystem that allows disparate systems to exchange information seamlessly (EMB, 2023).

One such application, GoodSAM (Good Smart Alerting Message), gained attention due to its ability to alert trained bystanders in real-time during medical emergencies such as out-of-hospital cardiac arrests (OHCA). Through its integration with emergency services 911 dispatch systems, the app provides key information such as location details using geo location, patient status, and proximity to Automated External Defibrillators (AEDs), thereby enabling immediate intervention and enhancing survival rates (GoodSAM, 2016; Service.Gov.UK, 2019).

The integration of GoodSAM with the London Ambulance Service (LAS) in 2015 marked a significant advancement in EMS technology. Evaluation reports revealed that volunteer responders reached patients an average of 2.5 minutes faster than ambulances, significantly improving the chances of survival during out-of-hospital cardiac arrests (Thompson, 2016). In the East Midlands, survival rates increased from 7% to 15% when alerts were accepted by responders (NIHR, 2025). Similarly, a study by Smith et al., (2022) demonstrated that GoodSAM’s deployment significantly reduced response times in OHCA cases, a critical factor in patient survival. Their research showed a 15-20% increase in survival rates when an immediate responder was available through GoodSAM’s network (Smith et al., 2021). However, while GoodSAM has shown promise, its success, and future development success, hinges on the ability to integrate seamlessly with existing emergency healthcare infrastructures, and their interoperability. 

In contrast to goodSAM, the United Kingdom (UK) introduced the National Health Services (NHS) app. This app provides a convenient and secure way for individuals aged 13 or older, registered with a GP surgery in England or the Isle of Man, to access a range of NHS services. Initially, users can access basic features such as searching for trusted NHS information on various health conditions and treatments, as well as locating nearby NHS services. However, to unlock the full potential of the app, users must verify their identity. Once verified, they can enjoy a broader set of features, including ordering repeat prescriptions and nominating a pharmacy for collection, booking and managing GP appointments, viewing their GP health records to see details like allergies and medications, and even accessing test results if their GP has granted them access. Additionally, users can manage COVID-19 vaccinations, register their organ donation decision, and choose how the NHS uses their health data. The app also integrates with NHS 111 online services, providing instant advice or medical help near the user's location. Depending on the capabilities of their GP surgery or hospital, users may also be able to message healthcare providers, manage hospital appointments, view care plans, and access health services on behalf of someone they care for. The NHS App is available for download on smartphones and tablets via the Google Play Store or App Store and can also be accessed through a web browser on the NHS website (NHS, 2021). A research study by KC et al (2023) highlighted the launch of the NHS app, which resulted in the app generating 8 524 882 downloads and 4 449 869 registrations between January 2019 and May 2021 (KC et al., 2023). The following two years, the app saved the NHS more than 1.1 million by removing SMS messaging, and applying the app services (NHS England, 2024). According to GOV.UK, all integrated care systems (ICSs) and their NHS trusts are aiming to have core digital capabilities, including electronic health records in place by March 2025.

Both studies highlighted the benefits and impact of these apps, however they also identified challenges.

2.	Challenges in integrating applications with emergency healthcare systems
The integration and interoperability of apps pose a significant challenge because of the use of legacy systems by healthcare services, particularly in large organizations like the NHS. Legacy systems in healthcare refer to outdated IT systems, software, or hardware that are still operational despite being technologically obsolete.

In January 2025, the Digital Health Networks CSO Council issued an advisory statement regarding the risks associated with "legacy debt" in NHS trusts. This warning followed a BBC investigation that found 126 instances of serious harm linked to IT issues across 31 trusts. The advisory emphasized the importance of completing safety case reporting and hazard logging for software to mitigate patient safety risks (Lovell, 2025). In another example, the NHS App faced "colossal" integration difficulties due to the need to unify legacy systems across England, while addressing core technical infrastructure, security, and interoperability issues (Kainos, 2024). According to NHS England, the NHS in England is not a unified organization. It consists of hundreds of diverse organizations of varying sizes at the central, national, regional and local levels, each with its own set of functions and responsibilities. Staff in these locations are likely to enter information in various ways on systems with diverse information models supporting varied structures and coding systems, indicating they are heterogenous. The lack of standardization has created significant difficulties in managing information consistently across multiple sources. This is because different systems tend to store various pieces of data in multiple locations that are often disconnected or incompatible with one another. As a result, they frequently encounter data silos, where information is isolated within specific systems, making it challenging to integrate, access, and maintain accuracy (NHS England 2023). As Integrio (2024) observes, legacy systems in healthcare present significant challenges to modernization and interoperability efforts. These systems, often outdated and reliant on obsolete technologies, create barriers to efficient data exchange and integration with modern digital solutions, which can lead to increased costs and security risks (Integrio, 2024). Efforts to address these challenges have included decommissioning legacy systems and migrating data to modern platforms. For example, University Hospitals of Derby and Burton NHS Foundation Trust adopted a cloud-based data archive system that allows clinicians to access historical data seamlessly through their electronic patient record (Archer-Williams, 2024). As stated by Tymoshcenko (2024), with comprehensive change management strategies and clinician involvement, legacy systems can be transformed into efficient digital ecosystems that support high-quality care (Tymoshcenko, 2024). Furthermore, the slow pace of progress towards digitalization within the NHS has been criticized for its lack of support for the improvement of digital capabilities, insufficient funding and a lack of essential digital skills, which has further hindered interoperability efforts (Fieldfisher, 2023). Similarly, a study by Giebel et al., 2023 highlighted the challenges in implementation of mobile health apps (mHealth) in healthcare systems which occurred because of lack of infrastructure, data privacy and security and implementation (Giebel et al., 2023). 

While both apps leverage mobile technology to improve healthcare access, their scopes differ significantly. GoodSAM focuses on emergency response by mobilizing trained individuals during life-threatening situations like cardiac arrests. In contrast, the NHS App provides broader functionality for managing routine healthcare needs and integrating digital tools into primary care pathways. Still, both apps face the challenge of achieving seamless integration with existing infrastructure, highlighting the need for standardized communication protocols across all healthcare systems. Developers face significant challenges when integrating new apps into existing healthcare technology, particularly due to the complexity of communication protocols and legacy systems. NHS Digital identified that integration was hard work, time consuming and costly, with developers encountering poor documentation, out-of-date technology, tricky to access path-to-live environments, overly complex and manual assurance processes and patchy help and support (Heap, 2022). However, developers must also navigate overlapping pre-existing NHS processes for security, information governance compliance with accessibility standards such as WCAG 2.2 AA and alignment with NHS style guidelines to ensure usability across diverse user groups (NHS England Digital, 2024). The key issue is that the NHS heavily relies on API’s (Application Programming Interfaces) for interoperability, as they are the primary method of access to core national services, such as the Personal Demographics Service (PDS), the Electronic Prescription Service (EPS), and the Summary Care Record (SCR), handling over 1.5 billion API transactions per month (Heap, 2022). 

3. Conclusion
4. 
In conclusion, the integration of mobile applications like GoodSAM with existing emergency healthcare systems remains a complex challenge, with interoperability being the most significant barrier to widespread adoption. While both platforms leverage mobile technology for healthcare delivery, their scopes differ significantly. The NHS App excels in providing routine healthcare services but struggles with fragmented integration and variability across practices. In contrast, GoodSAM specializes in life-saving emergency interventions but faces challenges related to responder density and sustained volunteer engagement. Both platforms demonstrate unique strengths within their respective domains but highlight the complexities of integrating digital tools into healthcare systems.

References:
Mosa, A.S.M., Yoo, I. and Sheets, L. (2012). A Systematic Review of Healthcare Applications for Smartphones. BMC Medical Informatics and Decision Making, [online] 12(1). doi: https://doi.org/10.1186/1472-6947-12-67. [Accessed 12 March 2025].

Kao, C.-K. and Liebovitz, D.M. (2017). Consumer Mobile Health Apps: Current State, Barriers, and Future Directions. PM&R, [online] 9(5), pp.S106–S115. doi: https://doi.org/10.1016/j.pmrj.2017.02.018. [Accessed 12 March 2025].

Free, C., Phillips, G., Watson, L., Galli, L., Felix, L., Edwards, P., Patel, V. and Haines, A. (2013). The Effectiveness of Mobile-Health Technologies to Improve Health Care
Service Delivery Processes: A Systematic Review and Meta-Analysis. PLoS Medicine, [online] 10(1), p.e1001363. doi: https://doi.org/10.1371/journal.pmed.1001363. [Accessed 14 March 2025].

Steinhubl, S.R., Muse, E.D. and Topol, E.J. (2013). Can Mobile Health Technologies Transform Health Care? JAMA, 310(22), p.2395. doi: https://doi.org/10.1001/jama.2013.281078. [Accessed 14 March 2025].

Ventola, C.L. (2014). Mobile Devices and Apps for Health Care Professionals: Uses and Benefits. Pharmacy and Therapeutics, [online] 39(5), p.356. Available from: https://pmc.ncbi.nlm.nih.gov/articles/PMC4029126/. [Accessed 14 March 2025].

Lindquist, M. (2024). Interoperability in healthcare explained. [online] Oracle. Available from: https://www.oracle.com/health/interoperability-healthcare/. [Accessed 12 March 2025].

EMB, T. (2023). Troubleshooting Common Challenges in Healthcare App Development. [online] Available from: https://blog.emb.global/common-challenges-in-healthcare-app-development/. [Accessed 13 March 2025].

Service.gov.uk. (2019). GoodSAM Cardiac, Alerting/Dispatch and Lone Working - Digital Marketplace. [online] Available from: https://www.applytosupply.digitalmarketplace.service.gov.uk/g-cloud/services/771069078217164 [Accessed 12 March 2025]. 

GoodSAM GoodSAM Saving Lives through Technology www.goodsamapp.org Cardiac, Alerting and Dispatch. (n.d.). Available from: https://cache.goodsamapp.org/assets/pdf/DispatchBrochure.pdf [Accessed 12 March 2025]. 

Thompson, M. (2016). Evaluation of the LAS. [online] Available from: https://media.nesta.org.uk/documents/las_goodsam_evaluation_report_-_2016-06-29_1.pdf [Accessed 12 March 2025].

Smith, C.M., Lall, R., Fothergill, R.T., Spaight, R. and Perkins, G.D. (2021). The effect of the GoodSAM volunteer first-responder app on survival to hospital discharge following out-of-hospital cardiac arrest. European Heart Journal. Acute Cardiovascular Care, 11(1), pp.20–31. doi: https://doi.org/10.1093/ehjacc/zuab103. [Accessed 12 March 2025].

Talend (n.d.). Overcoming Healthcare’s Data Integration Challenges - Talend. [online] Talend Real-Time Open Source Data Integration Software. Available from: https://www.talend.com/resources/data-integration-challenges-healthcare/. [Accessed 12 March 2025].

Kithome-Kitonyi, C. (2024). Bridging the gap: Medical data standardization and data quality. [online] Rhapsody. Available from: https://rhapsody.health/blog/bridging-the-gap-medical-data-standardization-and-data-quality/. [Accessed 12 March 2025].

Szarfman, A., Levine, J.G., Tonning, J.M., Weichold, F., Bloom, J.C., Soreth, J.M., Geanacopoulos, M., Callahan, L., Spotnitz, M., Ryan, Q., Pease-Fye, M., Brownstein, J.S., Ed Hammond, W., Reich, C. and Altman, R.B. (2022). Recommendations for achieving interoperable and shareable medical data in the USA. Communications Medicine, 2(1). doi: https://doi.org/10.1038/s43856-022-00148-x. [Accessed 12 March 2025].

Digital.nhs.uk. (2025). NHS. NHS App Roadmap. Available from: https://digital.nhs.uk/services/nhs-app/roadmap. [Accessed 12 March 2025].

Kc, S., Tewolde, S., Laverty, A.A., Costelloe, C., Papoutsi, C., Reidy, C., Gudgin, B., Shenton, C., Majeed, A., Powell, J. and Greaves, F. (2023). Uptake and adoption of the NHS App in England: an observational study. British Journal of General Practice, [online] 73(737). doi: https://doi.org/10.3399/BJGP.2022.0150 [Accessed 13 March 2025]. 

NHS England (2024). NHS England» NHS App messaging saved NHS more than £1 million in last year. [online] www.england.nhs.uk. Available from: https://www.england.nhs.uk/2024/05/nhs-app-messaging-saved-nhs-more-than-1-million-in-last-year/. [Accessed 13 March 2025].

Lovell, T. (2025). NHS trusts warned that ‘legacy debt’ could pose patient safety risk. [online] Digital Health. Available at: https://www.digitalhealth.net/2025/01/nhs-trusts-warned-that-legacy-debt-could-pose-patient-safety-risk/ [Accessed 14 March 2025]. 

NHS (2021). About the NHS App. [online] nhs.uk. Available from: https://www.nhs.uk/nhs-app/about-the-nhs-app/. [Accessed 13 March 2025].

Kainos.com. (2024). NHS App: A game-changing approach to digital health. [online] Available from: https://www.kainos.com/insights/success-stories/nhs-app. [Accessed 13 March 2025].

NHS England (2023). NHS England» Interoperability. [online] www.england.nhs.uk. Available from: https://www.england.nhs.uk/long-read/interoperability/. [Accessed 13 March 2025].

Integrio Systems. (n.d.). Legacy Systems in Healthcare: Main Steps & Challenges. [online] Available from: https://integrio.net/blog/legacy-systems-in-healthcare-main-steps-and-challenges. [Accessed 14 March 2025].

Archer-Williams, A. (2024). Legacy information systems: approaches from across the NHS. [online] htn. Available from: https://htn.co.uk/2024/02/08/legacy-information-systems-approaches-from-across-the-nhs/. [Accessed 14 March 2025].

Tymoshchenko, D. (2024). Legacy Systems in Healthcare: Maintain or Replace. [online] Available from: https://acropolium.com/blog/legacy-systems-healthcare/. [Accessed 14 March 2025].

Fieldfisher. (n.d.). Solving the NHS’s interoperability problem. [online] Available from: https://www.fieldfisher.com/en/insights/solving-the-nhs-s-interoperability-problem. [Accessed 13 March 2025].

Giebel, G.D., Speckemeier, C., Abels, C., Plescher, F., Börchers, K., Wasem, J., Blase, N. and Neusser, S. (2023). Problems and Barriers Related to the Use of Digital Health Applications: Scoping Review. Journal of Medical Internet Research, [online] 25(1), p.e43808. doi: https://doi.org/10.2196/43808. [Accessed 13 March 2025].

Department of Health and Social Care (2022). A Plan for Digital Health and Social Care. [online] GOV.UK. Available from: https://www.gov.uk/government/publications/a-plan-for-digital-health-and-social-care/a-plan-for-digital-health-and-social-care. [Accessed 13 March 2025].

Heap, T. (2022). Making integration easier at the NHS. [online] Digital Health. Available from: https://www.digitalhealth.net/2022/05/making-integration-easier-at-the-nhs/ [Accessed 13 March 2025].

NHS England Digital. (n.d.). Standards for NHS App integration. [online] Available from: https://digital.nhs.uk/services/nhs-app/how-to-integrate-with-the-nhs-app/standards-for-nhs-app-integration. [Accessed 13 March 2025].
