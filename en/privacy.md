---
layout: content
lang: en
showBreadCrumbs: true
title: CoronaMelder Privacy Statement
--- 
## About CoronaMelder

CoronaMelder (app) is a technical tool that helps limit the spread of the COVID-19 virus. If you have installed CoronaMelder on your smartphone, you will receive a message if you have been in the proximity (for some time) of a person who has tested positive for COVID-19, and this person has also installed CoronaMelder. If you may have been infected by another CoronaMelder user, the app recommends that you have yourself tested if you have any symptoms. Below we will briefly explain how CoronaMelder works.

The app recognises other smartphones on which the app is installed via Bluetooth Low Energy. The other smartphones are recognised using random codes (series of numbers) known as Rolling Proximity Indicators (RPIs). These codes are updated every 10 to 20 minutes, and are derived from Temporary Exposure Keys (TEKs). TEKs are also random codes, but are regenerated on a daily basis to be stored on the user's phone for 14 days. 

If your smartphone is in proximity to another smartphone on which the app is installed, their respective RPIs are exchanged and stored locally on those phones. If an app user has tested positive for COVID-19, the user may voluntarily choose to report this in the app. If the user chooses to do so, the app will send the TEKs created in the past 14 days and stored locally on the smartphone to a backend server. The backend server will only accept transmitted TEKs if the user and the Dutch Municipal Health Service (GGD) have confirmed such transmission with a validation code. On the backend server, the TEKs received are converted into other codes known as Diagnosis Keys (DKs). 

The backend server then makes the DKs available for automatic download by the smartphones on which the app is installed. After your smartphone has downloaded the DKs from the server, the phone will be disconnected from the server. This automated process is repeated several times per day to keep any contamination risks up-to-date. Your smartphone then calculates on the basis of the downloaded DKs whether there is a match with the various RPIs of other smartphones that have been in proximity to your smartphone. Immediately thereafter, the DKs will be removed from your smartphone. 

If there is a match, an assessment is made using a number of weighting factors as to whether there has been high-risk contact. If that is the case — in other words, if you have recently been in close proximity to a person infected with COVID-19 — you will be notified that there is an increased risk of contamination. The app also recommends having yourself tested for contamination with the virus if you have any symptoms.



### 1. Who is responsible for the processing of the personal data? 
To the extent personal data are processed in the design and management of CoronaMelder, the Minister of Health, Welfare and Sport is the controller.

In so far as the Municipal Health Service (GGD) uses personal data obtained via the app during source and contact tracing, your regional GGD is the controller. Visit <a href="https://www.ggd.nl" target="_blank" rel="noopener noreferrer">www.ggd.nl</a> to find your GGD by entering the postal code of your home address. If you do not have a home address in the Netherlands, you can enter the postal code of your place of residence.

### 2. For what purpose are personal data processed? 
This app has been developed as an addition to source and contact tracing by the GGD. Its purpose is to quickly and easily inform users who have an increased risk of infection, while ensuring a high degree of anonymity. 

### 3. Basis for processing personal data 
Personal data can be processed in the app. The basis for the processing of personal data is, in brief, a public duty. For the Minister of Health, Welfare and Sport this is the public duty to, in brief, lead the fight against COVID-19 and to ensure the national support structure is maintained and improved.

For the GGDs, the duty is to perform source and contract tracing if there has been a report of an infection with COVID-19.

The introduction of CoronaMelder as a supporting tool for source and contact trading thus helps carry out the aforementioned duties of the Minister of Health, Welfare and Sport and the GGDs.

Use of CoronaMelder is voluntary. CoronaMelder therefore asks for your permission before you can use the app. If you do not give this permission, you will not be able to use CoronaMelder. Your permission will also be asked before you can share your details with the GGD, if you test positively.


### 4. What personal data are processed? 
The following data are processed in the app:

* Rolling Proximity Indicators (RPIs)
* Temporary Exposure Keys (TEKs)
* Diagnosis Keys (DKs)
* Pseudo MAC address
* Signal strength and duration of contact
* First day of illness
* Validation code
* Exposure Risk Value (high, mid, low)
* IP address

These data may be personal data. 

A TEK is a randomly, cryptographically generated series of numbers serving as a temporary reference. TEKs are converted into DKs on the backend server. In addition, an RPI is generated every 10 to 20 minutes, which is a temporary series of numbers that are also cryptographically generated. This series of numbers is a derivative of a TEK, and is exchanged with other smartphones on which the app is installed, and which have been in close proximity to the smartphone concerned for a specific period of time. The RPIs are transmitted and received via Bluetooth Low Energy and are thus used in combination with the signal strengths of both transmission and reception (to determine the distance between users), and the duration of the (Bluetooth) contact. The RPIs received are removed from the smartphones after 14 days. 

TEKs, DKs and RPIs are all pseudonymised identification keys.

In order to minimise the risk of users being identified, when RPIs are exchanged, the MAC address (a unique hardware number of the Bluetooth transmitter) of the smartphone is replaced by a randomly generated code, a pseudo MAC address, which, like the RPIs, changes every 10 to 20 minutes. 

The validation code is generated through a functionality provided by the app and is shown in the app. The validation code is used by the GGD to validate the TEKs sent to the GGD. The GGD places this validation code, with the date of the first day of illness, in the GGD portal. This GGD portal is only accessible to GGD employees. The backend server only accepts user TEKs if a validation code is provided that has been validated by the GGD in this manner. During the validation phase, IP addresses are processed for administration and security purposes.

In addition to the DKs, the first day of illness and validation code, the IP address is sent to the backend server. This is inherent to the use of Internet and IP technology. The IP address is stored separately from the other data, so that no IP addresses are stored on the central server. As a result, it is impossible to trace who sent which information.

### 5. Statistical information 
The data collected with the app will only be used for the purposes stated in this privacy statement. No statistical information is generated. 

### 6. Who is provided with personal data?
The sending and receiving of RPIs takes place locally on users' smartphones. Once an infection has been detected, the user can choose to send his or her TEKs, along with a unique validation code, to the backend server. The backend server is administered by the CIBG with KPN as subcontractor (processor).

The GGD processes the validation code, with the date of the first day of illness, in the app's GGD portal, which is only accessible to authorised GGD employees.

The smartphones of other users periodically – a few times a day – retrieve the DKs stored on this backend server. 

### 7. Retention of personal data
The data stored locally on your smartphone will be retained for 14 days. After these 14 days, these data are automatically and permanently deleted. In addition, you are able to delete the stored data yourself at any time. 

In so far as your data are stored on the backend server, they will be retained for 14 days from the time of uploading. After these 14 days, the data will be deleted. 

IP addresses processed for administration and security purposes will be deleted after a maximum of 7 days.

### 8. Your rights with regard to your personal data 
You have a number of rights to maintain control over your personal data. You can find them here on the website of the Dutch Data Protection Authority (Autoriteit Persoonsgegevens).

As CoronaMelder has been designed in accordance with the principles of data minimalization and privacy by design, you can only invoke your rights under the GDPR to a limited extent. Moreover, data are practically untraceable and are only stored for a short period of time. It follows from Article 11 of the GDPR that the rights under Articles 15 to 20 of the GDPR do not apply if the controller cannot or no longer identify the data subject.

In the first phase – before users upload TEKs to the backend server – data are only processed on the smartphones of CoronaMelder users. The Minister of Health, Welfare and Sport and the GGDs do not have access to them. In this case, a request to change or delete data, for example, cannot be complied with, although of course these data will be removed from the smartphone automatically after a maximum of fourteen days. 

Owing to the privacy-by-design nature of the app, it is impossible to trace which codes belong to the infected user after uploading the TEKs (and subsequently DKs). It is technically impossible for the Ministry of Health, Welfare and Sport and the GGD offices to link the codes stored (temporarily) on the backend server to users who uploaded their TEKs. Because it is impossible to identify the user on the basis of the codes, the rights under Articles 15 to 20 of the GDPR do not apply.

The enforcement of GDPR rights will therefore only be required to a limited extent, simply because the data cannot be traced to persons or only to a very limited extent, or because these data no longer exist because of the short retention periods. This complies with Article 11 of the GDPR, which states that the rights included in Articles 11 to 20 of the GDPR do not apply if data subjects can no longer be identified.


However, it is still possible to make a request invoking your privacy rights. You may send your request to the GGD responsible in your place of residence. On <a href="https://www.ggd.nl" target="_blank" rel="noopener noreferrer">www.ggd.nl</a> you can enter the postal code of your home address to see which GGD is responsible in your place of residence. If you do not have a home address in the Netherlands, you can enter the postal code of your place of residence.
You always have the right to lodge a complaint about the processing of your personal data with the Dutch Data Protection Authority or before the courts. More information about this can be found here. 

You can find the contact details of the Data Protection Officer of the GGD responsible in your place of residence via the GGD’s website.

You can find the contact details of the Data Protection Officer of the Ministry of Health, Welfare and Sport on that ministry’s website.

### 9. Protection of your personal data
The Minister of Health, Welfare and Sport and the GGD take the protection of your data seriously and take appropriate measures to prevent any abuse, loss, unauthorised access, undesired disclosures and unauthorised changes.

### 10. Amendment of privacy statement
This privacy statement is subject to amendment. In that case, we will publish the amended privacy statement on our website, after it will have immediate effect. 
Most recent update: 10 September 2020
