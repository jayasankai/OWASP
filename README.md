# UNDERSTANDING THE OWASP® TOP 10 SECURITY THREATS (SKF100)

Links : </br>
https://trainingportal.linuxfoundation.org/learn/course/owasp-top-10-security-threats-skf100 </br>
https://cm.lf.training/SKF100/</br>

## Introduction :
Failure to prioritize web application security can have severe consequences:

* data breaches
* Financial loses 
* Reputational damage
* Legal liabilities

Web applications often handle personal, financial, and confidential data, such as credit card numbers, passwords, and medical records. Without proper security measures, this information becomes vulnerable to unauthorised access and misuse.

Compliance with regulatory standards is another crucial aspect of web application security. Many industries are subject to strict regulations that govern data protection and security. Failure to comply with these standards can result in severe penalties and legal consequences. Implementing effective security measures ensures compliance with regulations such as GDPR, PCI DSS, and HIPAA, thereby avoiding legal troubles and demonstrating a commitment to protecting sensitive data.

In conclusion, understanding the importance of web application security is crucial in today’s digital landscape. Protecting sensitive information, safeguarding user privacy, mitigating financial losses, complying with regulatory standards, and preserving business reputation are compelling reasons to invest in robust security measures. Prioritizing web application security is not just a matter of choice; it is a necessity to protect against the increasing threats and risks in the digital realm. By implementing comprehensive security measures, businesses and individuals can ensure the integrity, confidentiality, and availability of web applications, fostering trust, and safeguarding their most valuable assets.

## Understanding the CIA:
1. Confidentiality Ensuring that information is accessible only to those authorized to access it.
2. Integrity Safeguarding the accuracy and completeness of information and processing methods.
3. Availability Ensuring that authorized users have timely and reliable access to information and resources.

## Security vulnerabilities can negatively impact the CIA triad in various ways:
* Confidentiality Breaches may lead to unauthorized access to sensitive data, such as personal information, intellectual property, or financial records. This can result in identity theft, financial fraud, or loss of competitive advantage.
* Integrity An attacker could manipulate data or tamper with processing methods, causing incorrect information to be displayed or processed. This can lead to incorrect decision-making or fraudulent transactions.
* Availability Vulnerabilities may be exploited to disrupt services, rendering them unavailable to legitimate users. This can result in a loss of productivity, customer dissatisfaction, or loss of revenue.

## Access Controls: 
Broken access controls are a critical security risk, as they can lead to unauthorized access to sensitive data and systems, enabling attackers to bypass established security measures. 

Access control enforces that users cannot act outside of their intended permissions. Failures typically lead to unauthorized information disclosure, modification, or destruction of all data or performing a business function outside the user’s limits. Common access control vulnerabilities include:

1. Violation of the principle of least privilege or deny by default, where access should only be granted for particular capabilities, roles, or users, but is available to anyone.
2. Bypassing access control checks by modifying the URL (parameter tampering or force browsing), internal application state, or the HTML page, or by using an attack tool to modify API requests.
3. Permitting viewing or editing someone else’s account, by providing its unique identifier (insecure direct object references).
4. Accessing API with missing access controls for POST, PUT, and DELETE.
5. Elevation of privilege. Acting as a user without being logged in or acting as an admin when logged in as a user.
6. Metadata manipulation, such as replaying or tampering with a JSON Web Token (JWT) access control token, a cookie, or hidden field manipulated to elevate privileges or abuse JWT invalidation.
7. CORS misconfiguration allows API access from unauthorized/untrusted origins.
8. Force browsing to authenticated pages as an unauthenticated user or to privileged pages as a standard user.

## Insecure Direct Object References (IDOR):
Insecure Direct Object References (IDOR) is a common security vulnerability that occurs when an application exposes direct access to internal objects, such as files, database records, or other system resources, without proper access control. This can lead to unauthorized users being able to access, modify, or delete sensitive data, potentially causing severe consequences for the system and its users.

IDOR vulnerabilities typically arise when developers implement insufficient or improper access controls on resources that are referenced by URL parameters, form fields, or other user-controlled inputs. Attackers can exploit these vulnerabilities by manipulating these inputs to gain unauthorized access to resources that they should not be able to access.

## TODO:
