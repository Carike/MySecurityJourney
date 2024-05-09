# Yellow Belt

![Yellow Belt](/images/yellow_belt.png)

## Six Foundational Truths of Application Security

The six foundational truths of application security are do not trust user input, shift left, avoid hardcoded credentials, third-party software care and feeding, threat modeling, and knowledge. Applying the foundational truths of application security will save you pain.

## Secure Design Principles Part 1

In this module, we explore secure design principles such as defense in depth, avoid security by obscurity, keep security simple and usable security. Employing a common understanding of secure design principles encourages secure design, and secure design equals less vulnerabilities.​

## Secure Design Principles Part 2

In this module, we explore secure design principles such as to minimize the attack surface, fail securely, least privileged, separation of duties, do not trust services/infrastructure, and secure defaults. Employing a common understanding of secure design principles encourages secure design, and secure design equals less vulnerabilities.​​

## Input Validation

This module explores input validation, which is checking data sent to your application before putting it to use. We explore the different types of input validation, how to determine if input validation is implemented correctly, and the implementation steps for correct input validation. Input validation protects what comes into your application, and attackers will send bad data inbound to see what happens.​​

## Output Encoding

This module explores output encoding, which is translating special characters into some equivalent form that is no longer dangerous in the target interpreter. We examine encoding, escaping, and contextual output encoding, various language approaches to encoding, and review examples. Output encoding protects what comes out of the application, and sometimes input. Improper encoding or escaping allow an attacker to change the commands that are sent to another component, inserting malicious commands instead. Encoding is a safety issue. The safety of the users of your application is at stake.​

## Authentication Theory

In this module, we define authentication as it relates to proving identity and multiple factors. We will uncover how authentication works and the issues for consideration. Authentication is an essential security feature of all applications. If authentication is flawed, the door into your application is open.​​

## Authorization Theory

This module explains why permissions must be checked, privileges must be limited, and access control is mandatory to prevent unauthorized access. We uncover how authorization works and the issues for consideration. Authorization is an essential security feature of all applications. If access control is flawed, users may access any information they want within your application.​

## Logging and Exception Handling

This module examines how audit records track both legitimate user and attacker activity. We explore the threats and weaknesses of logging, events to log, data to exclude from logs and design principles to improve logging. Without proper logging, it is impossible to investigate an application compromise or data breach. Without stable exception handling, applications behave in unknown and unspecified ways.​

## Cryptography

In this module, we explore the basic building blocks of cryptography; encryption, decryption, keys, and algorithms. A small mistake in configuration or coding will result in removing protection and rendering a crypto implementation useless. Your application must use cryptography well to protect data in transit and at rest.​

## Risk Management for AppSec​

In this module, we explain the principles of risk management, and how it applies to your world. The software contains risk, and risk management principles help with risk reduction. Technical people must understand the risk.​

## The Hacker Mindset

In this module, we examine how hackers think differently; learn how their brains work. The term “hacker” is thrown around in the media with reckless abandon and is synonymous with cyber-criminal. The hacker mindset is adaptable and applicable to anyone, with no life of crime required.​​

## OWASP Top 10: Part 1

In this module, we review Injection, Broken Authentication, and Sensitive Data Exposure. We examine a description of each item, the risk to products and applications, applicable languages, and how to mitigate each risk. The OWASP Top 10 is the most popular application security document and contains the definitive industry list of security risks.​

## OWASP Top 10: Part 2

In this module, we review XML External Entity, Broken Access Control, Security Misconfiguration, and Cross-Site Scripting. We examine a description of each item, the risk to products and applications, applicable languages, and how to mitigate each risk. The OWASP Top 10 is the most popular application security document and contains the definitive industry list of security risks.​​

## OWASP Top 10: Part 3

In this module, we review Insecure Deserialization, Using Components with Known Vulnerabilities, and Insufficient Logging & Monitoring. We examine a description of each item, the risk to products and applications, applicable languages, and how to mitigate each risk. The OWASP Top 10 is the most popular application security document and contains the definitive industry list of security risks.​​

## Buffer Overflows and Remote Code Execution

In this module, we define overflows as when too much data is placed into a data structure, and data transforms into code. We explain how a buffer overflow works, differentiate between stack-based, heap-based, and integer overflows, and devise a plan to mitigate buffer overflows in your applications. Buffer overflow results in an attacker controlling the flow of a program on your computer. With control flow comes the ability to drop to a shell.​

## Denial of Service

This module reviews denial of service, an attack against the availability of a product or system. We examine denial of service-based threats, differentiate between the different flavors of denial of service, and realize how denial of service attacks are mitigated. We also explore real-life examples. Denial of service takes your product or application offline and renders it unusable by your customers.​​

## XSS, Part One

This module reviews XSS (“Cross Site Scripting”), an attacker-controlled JavaScript executing in a user’s browser. We explore stored or persistent XSS and devise a plan to mitigate XSS in your applications. We also review real-life XSS examples.​

## XSS, Part Two

This module reviews XSS (“Cross Site Scripting”), an attacker-controlled JavaScript executing in a user’s browser. We explore reflected and DOM-based XSS and devise a plan to mitigate XSS in your applications. We also review real-life XSS examples.​

## Injection: SQL and Command

This module reviews injection, an attack that allows an attacker to execute commands within your application or product, outside of your control. SQL and command injection attacks insert structured commands from an attacker directly inside an application. We review the critical types of injection attacks and devise a plan to mitigate injection in your applications.​

## Cross-Site Request Forgery

This module examines CSRF, an attack that forces an end user to execute unwanted actions on a web application in which they're currently authenticated. A successful CSRF attack can force the user to transfer funds, change their email address, and so forth. If the victim is an admin, CSRF can compromise the entire web application. We review examples and how to mitigate this type of attack.​​

## Insecure Communications

This module examines how insecure communications could result in the COMPLETE disclosure of all your customer data. We explore how to determine if a conversation is adequately authenticated and encrypted. We also review best practices for securing network communications.​​ ​

## Social Engineering

This module explores attacks against the human element. We examine the influence of the human factor in tech-based attacks, the tactics that social engineers utilize, a general social engineering process, and various social engineering scenarios that technical people might deal with. Social engineering attacks target engineers and professional people every day.​​

## AppSec in an Agile World, Part One

This module outlines how to incorporate application security into the Agile development methodology. We differentiate between the security activities of a standard sprint and a security sprint. Agile is the way of the future for software development and building security in is the only avenue for true security success.​​

## AppSec in an Agile World, Part Two

This module outlines how to incorporate application security into the Agile development methodology. We differentiate between the security activities of a standard sprint and a security sprint. Agile is the way of the future for software development and building security in is the only avenue for true security success.​

## AppSec in a DevOps World

This module examines how to integrate application security into a DevOps pipeline. We review the DevOps methodology and all things continuous, the security activities to go fast, and the security activities to the DevOps methodology. DevOps is changing the velocity of software delivery and must have security built-in.​

## Security Behaviors for DevOps

This module examines the seven security behaviors that drive security into DevOps. DevOps is changing the velocity of software delivery and must have security built-in.​​

## Security Requirements

This module explains how writing security requirements must be a part of every SDL. We explore how security requirements are used to impact a product or applications development positively, trusted sources, and how to apply and work with specific, basic security requirements. Implementation of security requirements forms the foundation of your product or application's security posture.​​

## Threat Modeling Basics

This module explains the importance of threat modeling, the purpose and advantages of threat modeling, and how threat modeling can be implemented. Threat modeling is basic application security hygiene, just like brushing your teeth. Do it early and often.​

## Threat Modeling Process

This module examines the process of performing threat modeling and the application of the threat modeling process. Threat modeling results in fewer security bugs to fix up to and after release, reduces possible avenues of attack (which Customers like), and drives the focus of security testing.​​

## Threat Modeling Examples

In this module, we review why engineers and testers need threat modeling, analyze example threat models and watch as experts perform threat modeling using examples.​​

## Static Application Security Testing (SAST)

In this module, we review tools and processes for discovering vulnerabilities in source code. We explore the uses of a SAST tool, the SAST tool workflow for a developer, and survey the available SAST offerings. SAST is a spell checker for security problems. You may have these tools, but not understand how they work or what they do.​

## Dynamic Application Security Testing (DAST)

In this module, we review tools and processes for discovering vulnerabilities in runtime web applications. DAST is a run-time checker for security problems. Fuzzers find implementation flaws you have not considered. Explore the uses of DAST tools, the DAST tool workflow for a developer, and the available DAST/Fuzz offerings. You may have these tools, but not understand how they work or what they do.​ ​

## Next Generation AppSec Tools

In this module, we discuss how IAST/RASP/SCA/CWPP is set to replace SAST/DAST/WAF over time. We review Interactive Application Security Testing (IAST), Runtime Application Self Protection (RASP), Software Composition Analysis (SCA), and Cloud Workload Protection Platform (CWPP). We also discuss the uses of these new tools and survey the available tool offerings.

## Vulnerability Scanning

In this module, we discuss tools and processes for discovering vulnerabilities in system-level components and operating systems. Vulnerability scanning identifies issues in the infrastructure beneath your application or product. You’ll receive the output from vulnerability scans and need to make changes to fix. We explain how a vulnerability scanner works, the uses of a vulnerability scanning tool, the vulnerability tool workflow for a developer, and survey the available vulnerability scanning offerings.​

## Penetration Testing and Bug Bounty

In this module, we explore penetration testing ( attacking applications and products using human expertise) and bug bounty ( a marketplace for the use of penetration testing skills). We examine the benefits of pen testing and bug bounty, the process for pen testing and bug bounty, and survey available pen testing and bug bounty offerings.

## Secure Code Review Part 1

In this module, we explain the process and checklists for performing security code review. We examine how to do code review for input validation. server-side validation, output encoding, and default/hardcoded credentials. Secure code review discovers potential vulnerabilities that manifest in code and design and mitigates those vulnerabilities that manifest in code and design and mitigates those issues by modifying the code.

## Secure Code Review Part 2

The process and checklists for performing security code review. Examine how to do code review for parameterized SQL queries, user management/authentication, session management, authorization, cryptography, logging/error handling, and security configuration. Secure code review discovers potential vulnerabilities that manifest in code and design and mitigates those issues by modifying the code.

## LINDDUN Privacy Threat Modeling

In this module, we explain the difference between contextual and transactional data, the growing value of privacy threat modeling, and the essential elements of the LINDDUN methodology.

## LINDDUN Privacy Threat Modeling Process

In this module, we dive into steps of applying LINDDUN by demonstrating how to create DFD diagrams, apply threat trees to DFD elements, prioritize threats, and plan mitigations.

## LINDDUN Threat Mitigations

In this module, we reveal the high-level goals of privacy threat mitigation, the four interrogative questions to apply to stored data, basic mitigation strategies, and privacy-enhancing technologies.

## CWE Top 25 Part 1

In this module, we review the CWE top 25 a list of the top 25 most dangerous software security weaknesses. We examine Cross-Site Scripting, Out-Of-Bounds Write and Read, Improper Restrictions of Operations within Memory Buffers, Improper Input Validation, and SQL Injection. We go over the consequences and mitigations of each of these weaknesses, as well as some common mitigations that can be used with most weaknesses.​​

## CWE Top 25 Part 2

In this module, we review the CWE top 25 a list of the top 25 most dangerous software security weaknesses. We examine Information Exposure, Use After Free, Cross-Site Request Forgery, OS Command Injection, Integer Overflow or Wraparound, and Path Traversal. We go over the consequences and mitigations of each of these weaknesses.​

## CWE Top 25 Part 3

In this module, we review the CWE top 25 a list of the top 25 most dangerous software security weaknesses. We examine NULL Pointer Dereference, Improper Authentication, Unrestricted Upload of File with Dangerous Type, Incorrect Permission Assignment for Critical Resource, Code Injection, and Insufficiently Protected Credentials. We go over the consequences and mitigations of each of these weaknesses.​​

## CWE Top 25 Part 4

In this module, we review the CWE top 25 a list of the top 25 most dangerous software security weaknesses. We examine Improper Restriction of XML External Entity Reference, Use of Hard-coded Credentials, Deserialization of Untrusted Data, Improper Privilege Management, Uncontrolled Resource Consumption, Missing authentication for critical function, and Missing Authentication. We go over the consequences and mitigations of each of these weaknesses.​​

## Server-Side Request Forgery

In this module, we define Server-Side Request Forgery, describe the different kinds of Server-Side Request Forgery attacks, and explain mitigation to prevent SSRF attack
