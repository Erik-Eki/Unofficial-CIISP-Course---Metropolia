CISSP - Certified Information Systems
=

> *"The hacker has become the hackeed."*

-**Edward Snowden**, circa 2020

> *A password should be like a toothbrush. Use it everyday; change it regularly; and DON’T share it with friends.*
> 
–**USENET**


# (ISC)^2^ Code of Ethics

Preamble: Safety of the commonwealth, duty to our principals (employers, contractors, people we work for) and to each other requires that we adhere, and be seen to adhere, to the highest ethical standards of behavior.

Therefore, strict adherence to this Code is a condition of certification.

## 1.  Protect Society, the Commonwealth, and the Infrastructure. 

As a security professional you must promote safe security practices to the public and make the security of subsystems and infrastructure for the good of the public. "Protecting society” means protect and uphold the principles in society before you do so for your employer and yourself.

> Without a secure society being protected by ethical individuals, there is chaos, crime and lawlessness.


## 2.  Act honorably, honestly, justly, responsibly, and legally.

**Always tell the truth**, set the truth free, for the TRUTH will always defend itself.  The truth has all the weapons, tactics, and practices to defend itself.

**If you lie**, you’ll be working overtime to cover up the lies, and defend your lie, tarnishing your reputation in the process.

If a customer has a sound information security network, don’t try to sell them something they don’t need.  Don’t sell them another firewall when they already have 5 of them.  Don’t try to scare small businesses into getting expensive and advanced biometric systems when all they really need is a surveillance camera and a standard lock.


## 3.  Provide Diligent and Competent Service to Principals.

If you don’t know how to configure a load balancer for a client, **don’t say that you can**.  If you are an expert at Palo Alto firewalls, don’t tell clients that you are an expert at Cisco firewalls.

If you are signing a contract with a security organization, don’t sign a contract with their competition which causes a conflict of interest.


## 4.  Advance and Protect the Profession.

So you studied really hard and finally passed the CISSP exam.
Your friend asks for your study notes, but you say “No, I studied all by myself and through sheer determination I passed it by myself.  I suggest you do that same and write your own notes.”
**This is a terrible response, and selfish**.


Think of all the people that helped you along the way in your road to becoming a CISSP, all the time and effort they put in to answer your questions and your inquiries about cryptography, disaster recovery, test taking strategies.

The canons are applied in order, and when ever there is an ethical dilemma, a CISSP must follow the cannon in the top-down order.

---

### Security policy

Security policy is a document that defines all relevant terminology and should have all the information needed to keep assets safe. It's a broad overview on **"what we’ll do"**, that will be more detailed in standards and then further on with *baselines, guidelines and procedures*.

* The security policy is used to: 
* assign responsibilities
* define roles
* specify audit requirements
* outline enforcement processes
* indicate compliance requirements
* define acceptable risk levels.

An organizational security policy focuses on the organization’s security.
An issue-specific security policy focuses on a certain element of the company.
A system-specific security policy focuses on certain system.
All of these can mandate different security measures to their respected fields and context.

Security policies: **Regulatory, Advisory, and Informative**.

1. A regulatory policy is required whenever industry or legal standards are applicable to your organization. This policy discusses the regulations that must be followed and outlines the procedures that should be used to elicit compliance.
2. An advisory policy discusses behaviors and activities that are acceptable and defines consequences of violations. It explains the senior management’s desires for security and compliance within an organization. Most policies are advisory.
3. An informative policy is designed to provide information or knowledge about a specific subject, such as company goals, mission statements, or how the organization interacts with partners and customers. An informative policy provides support, research, or background information relevant to the specific elements of the overall policy. An informative policy is non-enforceable.

---

# Bureaucracy

Like it or not, you will be working in a company where you'll encounter bureaucracy and corporate confusion or you'll have your own company that will become more bureaucratic the larger it gets.
So you can't run away from it; Let's start with the fundamentals of the corporate ladder:

## Basic Corporate-Management Hiearchy
- Board of Directors
- Chief Executive Officer(CEO)
- Chief Financial Officer(CFO)
- Chief Information Offier(CIO)
- Chief Privacy Officer(CPO)
- Chief Securit Officer(CSO)

*CEO*, *CFO* and *CIO*, department managers and *Chief Infernal Auditor* should form a **Security Steering Committee** that is responsible for making decisions on tactical and strategic security issues within the enterprise as a whole and should not be tied to one or more business units

**The Audit Committee** should be appointed by the board of directors to help it review and evaluate the company’s internal operations, internal audit system, and the transparency and accuracy of financial reporting so the company’s investors, customers, and creditors have continued confidence in the organization.

---
## Detailed Hiearchy for Information Business

- **Senior management** is “big boss” of the organization (From the Board to CSO, etc.). They are responsible for everything and everyone. Should form a Audit- and Security Steering Committee

- **Owner** is typically a member of senior management (e.x. CEO). They take the responsibility for the safeguarding of assigned information assets and cannot fully give the responsibility away, to a custodian for example.
    - Reviews the classification levels of assigned information assets
    - Determining information classification
    - Delegating day-to-day responsibilities and functions to the custodian
    - Keeping inventories and accounting

- **Custodian** is typically a member of the IT department. They implement what the data owner tells them and are responsible for the day-to-day management of assets.

- **System Owner** is responsible for one or more systems, each of which may hold and process data owned by different data owners. A system owner is responsible for integrating security considerations into application and system purchasing decisions and development projects.

- **Security Administrator** is responsible for implementing and maintaining specific security network devices and software in the enterprise. These controls commonly include firewalls, IDS, IPS, antimalware, security proxies, data loss prevention, etc.

- **Security Analyst** helps develop policies, standards, and guidelines, as well as set various baselines.

- **Application Owners**, usually the business unit managers, are responsible for dictating who can and cannot access their applications

- **Supervisor**, also called user manager, is ultimately responsible for all user activity and any assets created and owned by these users.

- **Change Control Analyst** is responsible for approving or rejecting requests to make changes to the network, systems, or software.

- **Data Analyst** is responsible for ensuring that data is stored in a way that makes the most sense to the company and the individuals who need to access and work with it.

- **Process Owner** is responsible for properly defining, improving upon, and monitoring various processes within a company. A process owner is not necessarily tied to one business unit or application.

- **Solution Provider** works with the business unit managers, data owners, and senior management to develop and deploy a solution to reduce the company’s pain points.

- **Users/Operators** are the… Well, users of the services and products of the company. Their responsibility is to abide by the company’s policies and procedures and also not break everything.
    - Employees
    - You, using the company's products

- **Auditor** is the "critiq" that examines the security periodically. They’re responsible for pointing out flaws and vulnerabilities in the security if needed and overall keep it in general check.

---


## Company's Purpose and Direction

- **Company Policy** is a management directive that establishes expectations (goals & objectives), and assign roles & responsibilities. It’s the reason anything is done.

- **Company Control Objective** is the goal(s) that need to be reached. It’s like a strategy on what to do, how to do it, when to do it and if it should be done.

- **Company Standards** are the rules, actions and such that everyone in the company must take part in, strife for and achieve. It’s the reason anything is done the way it’s done.

- **Company Baselines** are the minimum of effort that needs to make things happen that the company must meet. The “things” were decided in standards. Products will start from here and will be brought back here if they don’t comply.

- **Company Guidelines** are like a looser version of standards and baselines, more like a framework and recommendation of “how things should be done”.

- **Company Processes and Procedures** are step-by-step instructions for implementation, a How-to-tutorial.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_afa644ae809aa47cd2be2e1ba11d3b8a.png)


### Jargon

**Separation of duties** makes sure that one individual cannot complete a critical task by herself. Separation of duties is a preventative administrative control put into place to reduce the potential of fraud. For example, an employee cannot complete a critical financial transaction by herself. She will need to have her supervisor’s written approval before the transaction can be completed.

In an organization that practices separation of duties, **collusion** must take place for fraud to be committed. Collusion means that at least two people are working together to cause some type of destruction or fraud. In our example, the employee and her supervisor must be participating in the fraudulent activity to make it happen.

Two variations of separation of duties are **split knowledge** and **dual control**. In both cases, two or more individuals are authorized and required to perform a duty or task. In the case of split knowledge, no one person knows or has all the details to perform a task.

**Rotation of duties** (rotation of assignments) is an administrative detective control that can be put into place to uncover fraudulent activities. No one person should stay in one position for a long time because they may end up having too much control over a segment of the business. This type of control is commonly implemented in financial institutions.

---

## Commercial and Government data classification from highest to lowest

Note: Classification of commercial or nongovernment organizations does not have a set standard.

- Top Secret
    - This data is so sensitive that only few individuals even know of it's existance. Moving this data around or even using it requires special permission to handle. 

    - Only really used in government and military purposes
        - Disclosure of top secret data would cause severe damage to national security.

- Secret
    - Data is too sensitive to be disclosed to most personnel in the organization and the integrity is to be heavily guarded.

    - Only really used in government and military purposes
        - Disclosure of secret data would cause serious damage to national security. This data is considered less sensitive than data classified as top secret.

- Sensitive
    - Data that is to have the most limited access and requires a high degree of integrity. This is typically data that will do the most damage to the organization should it be disclosed.

    - Within government, there's Unclassified(SBU) data:
        - SBU data is data that is not considered vital to national security, but its disclosure would do some harm. Many agencies classify data they collect from citizens as SBU. In Canada, the SBU classification is referred to as protected (A, B, C).
        - Unclassified is data that has no classification or is not sensitive (Equivalent to Public in most cases.

- Confidential
    - Data that might be less restrictive within the company but might cause damage if disclosed.

    - Confidential data is usually data that is exempt from disclosure under laws such as the Freedom of Information Act but is not classified as national security data.

- Private
    - Private data is usually compartmental data that might not do the company damage but must be keep private for other reasons. Human resources data is one example of data that can be classified as private.

- Proprietary
    - Proprietary data is data that is disclosed outside the company on a limited basis or contains information that could reduce the company's competitive advantage, such as the technical specifications of a new product.

- Public
    - Public data is the least sensitive data used by the company and would cause the least harm if disclosed. This could be anything from data used for marketing to the number of employees in the company.


These are only the universal standards, but depending on the data and the size of the organization, you can leave some levels out:

![](https://gitlab.dclabra.fi/wiki/uploads/upload_5d02d5170966a5c4a47d60854102fd53.png)

### Detemining the sensitivity of data (Criteria)

- The usefulness of data
- The value of data
- The age of data
- The level of damage that could be caused if the data were disclosed
- The level of damage that could be caused if the data were modified or corrupted
- Legal, regulatory, or contractual responsibility to protect the data
- Effects the data has on security
- Who should be able to access the data
- Who should maintain the data
- Who should be able to reproduce the data
- Lost opportunity costs that could be incurred if the data were not available or were corrupted

#### Questions:
1. Who should be able to access or maintain the data?
2. Which laws, regulations, directives, or liability might be required in protecting the data?
3. For government organizations, what would the effect on national security be if the data were disclosed?
4. For nongovernment organizations, what would the level of damage be if the data was disclosed or corrupted?
5. Where is the data to be stored?
6. What is the value or usefulness of the data?


### Data Classification Procedures
1. Define classification levels.
2. Specify the criteria that will determine how data are classified.
3. Identify data owners who will be responsible for classifying data.
4. Identify the data custodian who will be responsible for maintaining data and its security level.
5. Indicate the security controls, or protection mechanisms, required for each classification level.
6. Document any exceptions to the previous classification issues.
7. Indicate the methods that can be used to transfer custody of the information to a different data owner.
8. Create a procedure to periodically review the classification and ownership. Communicate any changes to the data custodian.
9. Indicate procedures for declassifying the data.
10. Integrate these issues into the security-awareness program so all employees understand how to handle data at different classification levels.

Using this information, the organization can create a procedure for classifying data. Government organizations already have this procedure defined. Nongovernment organizations have a lot of flexibility in setting the procedures that best suit their needs.

---



# Information System Security Capabilities

## CIA Triad

![](https://gitlab.dclabra.fi/wiki/uploads/upload_a6f8dfce53e02809d084d86ca040e24e.png)

The basics of any information/data system relies on 3 things: Condifentiality, Integrity, Availability.

- **Confidentiality** is lost when someone unauthorized views/uses data or system.
    - **Countermeasures**: Access controls and encryption
- **Integrity** is lost when data or system is corrupted/destroyed/modified.
    - **Countermeasures**: Hashing
- **Availability** is lost when user cannot access system or data due to it not being available.
    - **Countermeasures**: Fault tolerance systems, redundancies and backups. RAID-systems, Failover cluster for servers, Alternate site for location backup. Cold site, Warm site and Hot site.

---

## System self-protection
A trustworthy operating system uses several mechanisms to protect itself:

* Memory segmentation
    * Process isolation
    * Security-domains
    * Virtual machines
* Layering and data hiding
    * Levels of access ro resources
    * Protection rings

Protection techniques are performed by elements of the Trusted Computing Base (TCB)

## Protection Rings to isolate processes
An operating system protects itself by implementing virtual protection rings and placing components in each ring based upon trust levels.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_78d60ddb27c69fe13b93e533571e3ca9.png)

Ring number determines the access level.
A program may access only data that resides on the same ring, or a less privileged ring.
A program may call services residing on the same, or a more privileged ring.

0. Ring 0 contains kernel functions of the OS.
1. Ring 1 contains the OS.
2. Ring 2 contains the OS utilities.
3. Ring 3 contains the applications.

### Segmentation to restrict resource access
Two levels of privilege (rings):

Subjects of higher trust can access more system instructions and operate in privileged mode
Controls (restrictions) must be placed on programs or processes that require Ring Zero privileges

![](https://gitlab.dclabra.fi/wiki/uploads/upload_92f633b621db5ba1951b14b2342029ca.png)

## Security Controls

* Preventive Controls (stops attacks)
* Detective Controls. (records events)
* Corrective Controls. (after an attack  prevents another attack)
* Recovery Controls. (after an attack restores operation)
* Compensating Controls. (substitutes for some other control that is inadequate)

> Data > Application > Host > Intranet > Perimeter > Physical Security

### Due care
Due care is legal duty of the company and if it fails to uphold these duties, it is held liable in court.
It's really about not being careless, otherwise the company could pay for its mistakes.

### Due diligence
Due diligence is having good practices that keep the company afloat, but is not legally liable.
It's about understanding the ins and outs of your information security policies and procedures and striving for quality (even if the company is trying its hardest to cut costs in questionable ways)

#### Baseline
Baseline is the minimum level of security that every system must meet.
Guidelines are recommendations on how to meet standards and baselines

#### Acceptable Use Policy (AUP)
Acceptable use policy is used to assign security roles and ensure responsibilities with said roles.

---

## Reference Monitor Concept - Access Controls

* Reference Monitor
    * Abstract machine that controls the access subjects have to objects
    * Reference Monitor uses Access-control list (ACL) to control the access to resources
    * Actions are logged and auditable
* Security Kernel
    * Components in system that enforce and implement the rules of the reference monitor
    * A **small** security kernel is easy to **verify, test, and validate** as secure.
        * However, in real life, the security kernel might be bloated with some unnecessary code because processes located inside can function faster and have privileged access. To avoid these performance costs, Linux and Windows have fairly large security kernels and have opted to sacrifice size in return for performance gains.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_7034d2ffcb37f1aba0a9f16017620a0f.png)

Subjects are active entities such as people, processes, or devices where as objects are passive entities that are designed to contain or receive information. Objects can be processes, software, or hardware.

## Reference Monitor - Control
* Reference Monitors are access controls found in operating systems and network access control systems
* Validates a subject's access rights to resources to protect the object from unauthorized access or destructive modification
* An abstract machine (service) that mediates all access to objects by subjects
    * Evaluate subject's security clearance to object's (resources) security label
    * Implemented and enforced by the Security Kernel to protect objects
    * Reference monitor should ensure **isolation, completeness and verifiability**

The reference monitor can be designed to use tokens, capability lists, or labels:

* Tokens—Communicate security attributes before requesting access
* Capability lists—Offer faster lookup than security tokens but are not as flexible
* Security labels—Used by high-security systems because labels offer permanence. This is provided only by security labels

Although the reference monitor is conceptual, the security kernel can be found at the heart of every system. The security kernel is responsible for running the required controls used to enforce functionality and resist known attacks. As mentioned previously, the reference monitor operates at the security perimeter—the boundary between the trusted and untrusted realm. Components outside the security perimeter are not trusted. All control and enforcement mechanisms are inside the security perimeter.

---

## Risks, Threats and Vulnerabilities
- Threat Agent
    - An entity that may act on a vulnerability.
- Threat
    - Any potential danger to information life cycle.
- Vulnerability
    - A weakness or flaw that may provide an opportunity for a threat agent.
- Risk
    - The likelihood of a threat agent exploits the discovered vulnerability.
- Exposure
    - An instance of being compromised by a threat agent.
- Countermeasure / safeguard
    - An administrative, operational, or logical mitigation against potential risk(s)

---

> ==System== = Gives rises to > ==Threat== = Exploits > ==Vulnerability== = Leads to > ==Risk== = Can damage > ==Asset== =  Damage to asset causes > ==Exposure== = Can be safeguarded by > ==Countermeasure== = Affects > ==System==

---

### Broad security countermeasures
Employees in sensitive areas should be forced to take their vacations, which is known as a mandatory vacation. While they are on vacation, other individuals fill their positions and thus can usually detect any fraudulent errors or activities.

#### Hiring Practices

- Nondisclosure agreements must be developed and signed by new employees to protect the company and its sensitive information. Any conflicts of interest must be addressed, and there should be different agreements and precautions taken with temporary and contract employees.

- Back ground checks should be done and security awareness should be made mandatory for all new hires.

#### Security Governance
Security governance is a framework that allows for the security goals of an organization to be set and expressed by senior management, communicated throughout the different levels of the organization, grant power to the entities needed to implement and enforce security, and provide a way to verify the performance of these necessary security activities.

#### Metrics
We need a way to assess the effectiveness of our work, identify deficiencies, and prioritize the things that still need work. We need a way to facilitate decision making, performance improvement, and accountability through collection, analysis, and reporting of the necessary information.

There are industry best practices that can be used to guide the development of a security metric and measurement system. The international standard is ISO/IEC 27004:2009, which is used to assess the effectiveness of an ISMS and the controls that make up the security program as outlined in ISO/IEC 27001. So ISO/IEC 27001 tells you how to build a security program and then ISO/IEC 27004 tells you how to measure it.

The NIST 800-55 publication also covers performance measuring for information security, but has a U.S. government slant.

The ISO standard and NIST approaches to metric development are similar, but have some differences. The ISO standard breaks individual metrics down into base measures, derived measures, and then indicator values.

---

# Privacy protection and regulation

Privacy laws can be traced as back as 1361 in England to arrest the peeping toms. Various countried enacted their individual laws thereafter. Modern Privacy benchmark can be found in the 1948 Universal Declaration of Human terrotorial and communications privacy. 

* 4th Amendment-protection against intrusion
* Philosophical-Warren & Brandeis
* Free Market vs Consumer Protection view
* Contract
* Regulations (for example Children´s Online Privacy Protection Act
* EU - Comprehensive Privacy Directive (processing personal data)
* US - EU Safe harbor framework is an example of data protection.


## EU privacy rules
The EU privacy rules include the following requirements about personal data and records:

* Must be collected fairly and lawfully
* Must only be used for the purposes for which it was collected and only for a reasonable period of time
* Must be accurate and kept up-to-date
* Must be accessible to individuals who request a report on personal information held about themselves
* Individuals must have the right to have any errors in their personal data corrected
* Personal data can’t be disclosed to other organizations or individuals unless authorized by law or consent of the individual
* Transmission of personal data to locations where equivalent privacy protection cannot be assured is prohibited

Two important pieces of privacy legislation in the United States are the U.S. Federal Privacy Act of 1974 and the U.S. Health Insurance Portability and Accountability Act (HIPAA) of 1996.
Other are U.S. Gramm-Leach-Bliley Financial Services Modernization Act (GLBA) and U.S. Electronic Communications Privacy Act (ECPA) of 1986.
ECPA provides the legal basis for network monitoring (Althought was amended extensively by the USA PATRIOT Act of 2001.)

---

## Asset retention
Information in the form of data must be stored in digital media or in hard printed copies. Based on the requirements of the law and based on corporate policies, data needs to be retained even after its useful life. Data is also retained in media as a backup and used in business continuity and disaster recovery scenarios.


### Data Retention Policy

* Data must be stored securely and appropriately with regard to sensitivity and confidentiality
* Data must be retained for as long as neccessary

### Storage

* Use Secure data centers for storage
* Only authorized personnel are required to have access to data, etc

### Retention

* Follow required laws and regulations for data retention. For example the data protection Act stipulates that personal "shall not be kept for longer than necessary for that purpose".
* The maximum number of years of retention is regarded as retention time.

### Destruction and disposal

* Follow procedures for destruction and disposal
* NIST SP 800-88 revision 1 stipulates guidelines for Media Sanitazion
* Key concept: Data remanence
    * Refers to data that remains on storage media after imperfect attempts to erase it
    * Happens on magnetic media,flash drives and SSDs
    * ![](https://gitlab.dclabra.fi/wiki/uploads/upload_17dc567cf5ec9e8e88b2d3fff17378a4.png)

#### Overwriting data

* Deleting a file does not erase its contents
* You must rewrite on top of the sectors it used
* Also called shredding or wiping
* A single pass is enough for a magnetic hard drive

#### Degaussing

* Exposing a magnetic disk or tape to high magnetic field
* Can be a secure erase if performed properly

#### Destruction

* Physically destroy the storage media
* More secure than overwriting
* Paper shredders destroy printed data

### Employee Retention Policy
* Employees are one of the most critical assets
* Employees are also on the the most expensive assets
* Losing a long term employee can be a big loss
* Create an environment suitable for growth from within
* Create an incentive system for long term employees
    * Extra vacation
    * Pay raise
    * Other fringe benefits such as parking, cell phone
* Human Resources should investigate all departure
    * What is the root cause
    * Can it be prevented

---


## Data Life Cycle Management
Sensitive assets, such as data, must be appropriately protected throughout their lifecycles. Data life cycle management (DLM) is a policy-based approach to managing the flow of an information system's data throughout its life cycle: from creation and initial storage to the time when it becomes obsolete and is deleted. As a rule, newer data, and data that must be accessed more frequently, is stored on faster, but more expensive storage media, while less critical data is stored on cheaper, but slower media.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_66e81568e528028285add1c198b6b17f.png)

### Scoping and tailoring

![](https://gitlab.dclabra.fi/wiki/uploads/upload_5abc1569b1c10c7f37ee5b3c847d2971.png)

### Standards and Control Frameworks to choose from
Several excellent control frameworks are available for security professionals’ use. In no circumstances is it necessary to start from scratch. Instead, the best approach is to start with one of several industry leading control frameworks, and then add or remove individual controls to suit the organization’s needs.

* PCI-DSS
* OCTAVE (Operationally Critical Threat, Asset, and Vulnerability Evaluation
* ISO 27002
    * Code of practice for information security management
* COBIT (Control Objectices for Information and related Techonology)
    * A governance model
* ITIL (Information Technology Infrastructure Library)
    * Framework for IT service management
* NIST 800-53
    * Recommended Security Controls for Federal Information Systems and Organizations.
### Certification and Accreditation
* Certification: A system meets the requirements of the data owner
* Accreditation: data owner accepts the certification
### Cryptography

Crypto plays a critical role in data protection, whether we’re talking about data in motion through a network, or at rest on a server or workstation. Cryptography is all about hiding data in plain sight, because there are situations where persons may be able to access sensitive data; crypto denies people that access unless they are in possession of an encryption key and the method for decrypting it.

---

## Secure Data Handling

### Controlling access to media
* Librarian to controls access
* Log who takes what materials out and when
* Materials should be properly labelled
* Media must be properly sanitized when necessary (Degaussing / Physically destroying)
### Protecting audit data and logs
* Intruders cover tracks by deleting logs
* Must make use of a central log server
* Log server must be hardened with restricted access
* Log server must be well protected to be reliable
* Write once media
* Signature tools such as syslogNG for reliability
* May be used in a trial
* Great fraud and investigation tools
* Requires some planning
* Protect your audit trail
### Issues with log audit
* Quantity of log
* Event filtering in real time
* Clipping levels
* Finding good auditing tools t oreduce size of logs
* Developing procedures
* Train personnel on how to read logs
* Protect the logs
* User of proper integrity mechanisms
* Storage and preservation of logs

### SIEM (Security Information and Event Management)
Security information and event management (SIEM) collects logs and other security-related documentation for analysis. Think of it as a machine that clues together all the IT security elements.
**A SEM** system centralizes the storage and interpretation of logs and allows near real-time analysis which enables security personnel to take defensive actions more quickly. **A SIM** system collects data into a central repository for trend analysis and provides automated reporting for compliance and centralized reporting.
Combine SEM and SIM and you get SIEM: A quicker identification, analysis and recovery of security events.
![](https://gitlab.dclabra.fi/wiki/uploads/upload_9d4be9d987d3524a165ad7dbd5ffc43e.png)
Some of the SIEM functions:
* Store RAW information from systems logs
* Aggregate logs in a single directory
* Will normalize the data in a common format
* May include alerting and reporting tools
* Often use for compliance requirements
* Great for incident response and investigation

### Link Encryption
* Usually performed by ISP or site to site
* Encrypts all the data (headers and payload)
* Must decrypt at each node to route the packets
* Introduce a GAP at each of the decryption point
* A compromised node could lead to capture of data
* Provides confidentiality
* Hides addressing information
* Can be combined with end-to-end encryption
* IPSec in tunnel mode is a similar concept
### End to end encryption
* Usually between users within an organization
* Only the data is encrypted
* Routing information is in clear text
* No need to decrypt in transit or at each node
* Can be combined with link encryption
* IPSec is transport mode is a similar concept

![](https://gitlab.dclabra.fi/wiki/uploads/upload_3b8dac79bccdd462541d7fa8eacb8aca.png)

## Software Development Life Cycle (SDLC)
![](https://gitlab.dclabra.fi/wiki/uploads/upload_5e5ae64a2df22a05f2940d0e724c623c.png)

---


# Security Models

![](https://gitlab.dclabra.fi/wiki/uploads/upload_90e22119000e9d2e8431bf27ab9a7f94.png)

## Bell-LaPadula Security Model (1973)
* Bell–LaPadula model focuses on data confidentiality and controlled access to classified information
* Uses no read-up & no write down
    * A subject at a given security level may not read an object at a higher security level (no read up)
    * A subject at a given security level must not write to any object at a lower security level (no write down)

![](https://gitlab.dclabra.fi/wiki/uploads/upload_695c3ab185abffd938a16fe1d9422859.png)

## Biba Security Model (1977)
* The Biba Model is a formal state transition system of computer security policy that describes a set of access control rules designed to ensure data integrity
    * A subject at a given level of integrity must not read an object at a lower integrity level (no read down)
    * A subject at a given level of integrity must not write to any object at a higher level of integrity (no write up)

![](https://gitlab.dclabra.fi/wiki/uploads/upload_676d8083c6e5f3c40f25eea68b20426a.png)

## Comparing Bell-Lapadula and Biba security models
* If you need to protect secrets, use Bell-Lapadula
    * No "write down"
    * No "read up"
* If you need to stay on target, use Biba
    * No "write up"
    * no "read down"
* Both of these are designed for the military, to protect high-level secrets

## State Machine Model

The state machine model is based on a finite state machine, as shown in the next picture. State machines are used to model complex systems and deals with acceptors, recognizers, state variables, and transaction functions. The state machine defines the behavior of a finite number of states, the transitions between those states, and actions that can occur.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_b0944827a4a59cb7ab5a23bcd6ef5a15.png)

## Clark-Wilson security model (1987)
* Designed for businesses, to protect integrity of data at all levels, not just the high value secrets
* Based on transactions
    * Well-formed transactions move a system from one consistent state to another consistent state
* A data integrity model
* Two principals: users and programs (called transformation procedures or TPs)
* Two types of data: unconstrained data times (UDIs) and constrained data items (CDIs)
* Users must be authenticated
* Transaction logs are kept

![](https://gitlab.dclabra.fi/wiki/uploads/upload_cac732e8f9f00c55cc256b2401152c94.png)

## Mandatory Access Control (MAC) security model
A mandatory access control scheme is where access controls are created by a central authority (typically, the OS, system administrator) and enforced by the OS.  Contrast this with discretionary access controls, where the owner of a file has the power to change access permissions.

Under some schemes, a trusted user might be able to change access controls.

Mandatory Access Control is considered more robust than Discretionary Access Control, because a hijacked process or user account cannot monkey around with access control lists.


In the next picture the data both users want to access are labeled Top Secret.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_36142095caa42fa6ed096fb7e194fd18.png)

Based on organizational policies, User A has a classification of Secret and User B has a classification of Top Secret. The MAC software compares the user classification, or label, to the data's label. If the user's classification is the same or higher than that of the data, and the user meets other requirements related to access, then the user is granted permission to use the data. In our example, User B is granted access because her classification is the same as the data. User A is denied access because he has a lower classification.

## Discretionary Access Control (DAC) security model
* The owner of an object contols who and what may access it. Access is at the owner's discretion
    * Example: shared file server where access permissions are administed by the owners (users) of its contents

![](https://gitlab.dclabra.fi/wiki/uploads/upload_3055ae794568511d9d1cc4d3ff54c814.png)

## Role Based Access Control (RBAC) security model
Role Based Access Control is an approach to access control that is newer than MAC or DAC.

The complexities and limitations of the two previous approaches boiled down to this:


* It's a huge hassle to deal with access control lists: Whenever anything changes (a user must be downgraded in terms of access, for example) the system administrator must comb through all files that user has access to, and revoke their privileges.
* Processes run with the same access permissions as the user that called them. In the canonical example, Solitare on Windows has access to your printer, network stack, data files, etc, even though there's no reason it should.

Role Based Access Control is an attempt to address these two problems.

To deal with the complexity issue, RBAC groups users into roles, and permissions into Rights. Thus, changing a user's permissions can be achieved just by changing the roles they are allowed to assume.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_5b2ad5b94c281d4fdc26d801abb29995.png)

This approach has more benefits. Since users are allowed to change roles, they can change to a lower-level (less permissions) role before executing untrusted code.

That insight allows us to tackle the second limitation of the MAC/DAC approach.

## Noninterference security model
The Noninterference model was designed to make sure that objects and subjects of different levels don’t interfere with the objects and subjects of other levels. The model uses inputs and outputs of either low or high sensitivity. Each data access attempt is independent of all others and data cannot cross security boundaries.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_34dc0c28db5043e91cfa7742f1534cb4.png)

## Chinese wall security model
Chinese wall is a business term describing an information barrier within an organization that was erected to prevent exchanges or communication that could lead to conflicts of interest. For example, a Chinese wall may be erected to separate and isolate people who make investments from those who are privy to confidential information that could influence the investment decisions. Firms are generally required by law to safeguard insider information and ensure that improper trading does not occur.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_78384c50924f696010c65911748b2779.png)

# Network Components Security

## Firewalls

A firewall controls traffic flow between a trusted network (such as a corporate LAN) and an untrusted or public network (such as the Internet). A firewall can comprise hardware, software, or a combination of both hardware and software. The CISSP candidate must understand the various types of firewalls and common firewall architectures.

### Firewall types

The three basic classifications of firewalls are:

* packet-filtering
* circuit-level gateway
* application-level gateway

### Packet-filtering

A packet-filtering firewall (or screening router) is one of the most basic (and inexpensive) types of firewalls and is ideally suited for a low-risk environment. A packet-filtering firewall permits or denies traffic based solely on the TCP, UDP, ICMP, and IP headers of the individual packets. It examines the traffic direction (inbound or outbound), the source and destination IP address, and the source and destination TCP or UDP port numbers. This information is compared with predefined rules that have been configured in an access control list (ACL) to determine whether a packet should be permitted or denied. A packet-filtering firewall typically operates at the Network or Transport layer of the OSI model. Some advantages of a packet-filtering firewall are that:

* It’s inexpensive (can be implemented as a router ACL)
* It’s fast and flexible
* It is transparent to users

Disadvantages of packet-filtering firewalls are that:

* Access decisions are based only on address and port information
* It has no protection from IP or DNS address spoofing
* It doesn’t support strong user authentication
* Configuring and maintaining ACLs can be difficult
* Logging information may be limited

![](https://gitlab.dclabra.fi/wiki/uploads/upload_08df92f33ba386c9c22aacb3804b4393.png)

A more advanced variation of the packet-filtering firewall is the dynamic packet-filtering firewall. This type of firewall supports dynamic modification of the firewall rule base by using context-based access control (CBAC) or reflexive ACLs, for example.

### Circuit-level gateway

A circuit-level gateway controls access by maintaining state information about established connections. When a permitted connection is established between two hosts, a tunnel or virtual circuit is created for the session, thus allowing packets to flow freely between the two hosts without the need for further inspecting individual packets. This type of firewall operates at the Session Layer of the OSI model.

Advantages of this type of firewall include:

* Speed (after a connection is established, individual packets aren’t analyzed.)
* Support for many protocols
* Easy maintenance

Disadvantages of this type of firewall include:

* Dependence on trustworthiness of the communicating users or hosts (after a connection is established, individual packets aren’t analyzed.)
* Limited logging information about individual data packets is available after the initial connection is established

A stateful inspection firewall is a type of circuit-level gateway that captures data packets at the Network Layer and then queues and analyzes (examines state and context) these packets at the upper layers of the OSI model.

### Application-level gateway

An application-level (or Application Layer) gateway operates at the Application Layer of the OSI model, processing data packets for specific IP applications. This type of firewall is generally considered the most secure and is commonly implemented as a proxy server. In a proxy server, no direct communication between two hosts is permitted. Instead, data packets are intercepted by the proxy server, which analyzes the packet’s contents and if permitted by the firewall rules, sends a copy of the original packet to the intended host.


Advantages of this type of firewall include:

* Data packets aren’t transmitted directly to communicating hosts, thereby masking the internal network’s design and preventing direct access to services on internal hosts
* It can be used to implement strong user authentication in applications

Disadvantages of this type of firewall include:


* It reduces network performance because every packet must be passed up to the Application Layer of the OSI model to be analyzed
* It must be tailored to specific applications (This can be difficult to maintain or update for new or changing protocols.)

## Firewall architectures

The basic firewall types that we discuss in the previous sections may be implemented in a firewall architecture as we describe in the following sections. The four basic types of firewall architectures are screening router, dual-homed gateway, screened-host gateway, and screened-subnet.


### Screening router

A screening router is the most basic type of firewall architecture employed. An external router is placed between the untrusted and trusted networks, and a security policy is implemented by using ACLs. Although a router functions as a choke point between a trusted and untrusted network, an attacker - after being granted access to a host on the trusted network - may potentially be able to compromise the entire network.

Advantages of a screening router architecture include that it’s

* Completely transparent
* Relatively simple and inexpensive

Disadvantages of the screening router architecture include that it:

* Is difficult to configure and maintain
* May have difficulty handling certain traffic
* Has limited or no logging available
* Uses no user authentication
* Is difficult to mask the internal network structure
* Has a single point of failure
* Doesn’t truly implement a firewall choke-point strategy

Still, using a screening router architecture is better than using nothing.

### Dual-homed gateways

Another common firewall architecture is the dual-homed gateway. A dual-homed gateway (or bastion host) is a system with two network interfaces (NICs) that sits between an untrusted and trusted network. A bastion host is a general term often used to refer to proxies, gateways, firewalls, or any server that provides applications or services directly to an untrusted network. Because it’s often the target of attackers, a bastion host is sometimes referred to as a sacrificial lamb.

However, this term is misleading because a bastion host is typically a hardened system employing robust security mechanisms. A dual-homed gateway is often connected to the untrusted network via an external screening router. The dual-homed gateway functions as a proxy server for the trusted network and may be configured to require user authentication. A dual-homed gateway offers a more fail-safe operation than screening routers because by default, data isn’t normally forwarded across the two interfaces. Advantages of the dual-homed gateway architecture include

* It operates in a fail-safe mode
* Internal network structure is masked

Disadvantages of the dual-homed gateway architecture include:

* Its use may inconvenience users
* Proxies may not be available for some services
* Its use may cause slower network performance

### Screened-host gateways

A screened-host gateway architecture employs an external screening router and an internal bastion host. The screening router is configured so that the bastion host is the only host accessible from the untrusted network (such as the Internet). The bastion host provides any required Web services to the untrusted network, such as HTTP and FTP, as permitted by the security policy. Connections to the Internet from the trusted network are routed via an application proxy on the bastion host or directly through the screening router.

Here are some of the advantages of the screened-host gateway:

* It provides distributed security between two devices.
* It has transparent outbound access.
* It has restricted inbound access.

Here are some disadvantages of the screened-host gateway:
It’s considered less secure because the screening router can bypass the bastion host for certain trusted services.

* Masking the internal network structure is difficult.
* It can have multiple single points of failure (router or bastion host).

### Screened-subnet

The screened-subnet is perhaps the most secure of the currently designed firewall architectures. The screened-subnet employs an external screening router, a dual-homed (or multi-homed) host, and a second internal screening router. This implements the concept of a network DMZ (or demilitarized zone). Publicly available services are placed on bastion hosts in the DMZ.

Advantages of the screened-subnet architecture include that:

* It’s transparent to end users
* It’s flexible
* Internal network structure can be masked
* It provides defense in depth instead of relying on a single device to provide security for the entire network

Disadvantages of a screened-subnet architecture include that it


* Is more expensive than other firewall architectures
* Is more difficult to configure and maintain
* Can be more difficult to troubleshoot

## Virtual Private Networks (VPNs)

A Virtual Private Network (VPN) creates a secure tunnel over a public network, such as the Internet. Either encrypting or encapsulating the data as it’s transmitted across the VPN creates a secure tunnel. The two ends of a VPN are commonly implemented by using one of the following methods:

* Client-to-VPN Concentrator (or Device)
* Client-to-Firewall
* Firewall-to-Firewall
* Router-to-Router

Common VPN protocol standards include Point-to-Point Tunneling Protocol (PPTP), Layer 2 Forwarding Protocol (L2F), Layer 2 Tunneling Protocol
(L2TP), Internet Protocol Security (IPSec), and Secure Sockets Layer (SSL).

### Point-to-Point Tunneling Protocol (PPTP)

The Point-to-Point Tunneling Protocol (PPTP) was developed by Microsoft to enable the Point-to-Point Protocol (PPP) to be tunneled through a public network. PPTP uses native PPP authentication and encryption services (such as PAP, CHAP, EAP), which we discuss later in the section “RAS.” It’s commonly used for secure dial-up connections using Microsoft Win9x or NT/2000 clients. PPTP operates at the Data Link Layer of the OSI model and is designed for individual client-server connections.

### Layer 2 Forwarding Protocol (L2F)

The Layer 2 Forwarding Protocol (L2F) was developed by Cisco and provides similar functionality as PPTP. As its name implies, L2F operates at the Data Link Layer of the OSI model and permits tunneling of Layer 2 WAN protocols such as HDLC and SLIP.

### Layer 2 Tunneling Protocol (L2TP)

The Layer 2 Tunneling Protocol (L2TP) is an IETF standard that combines Microsoft (and others) PPTP and Cisco L2F protocols. Like PPTP and L2F, L2TP operates at the Data Link Layer of the OSI model to create secure VPN connections for individual client-server connections. The L2TP addresses the following end-user requirements:

* Transparency: Requires no additional software.
* Robust authentication: Supports PPP authentication protocols, Remote Authentication Dial-In User Service (RADIUS), Terminal Access Controller Access Control System (TACACS), smart cards, and one-time passwords.
* Local addressing: The VPN entities, rather than the ISP, assign IP addresses.
* Authorization: Authorization is managed by the VPN server-side similar to direct dial-up connections.
* Accounting: Both the ISP and user perform Accounting.

### IPSec

Internet Protocol Security (IPSec) is an IETF open standard for VPNs that operates at the Network Layer of the OSI model. It’s the most popular and robust VPN protocol in use today. IPSec ensures confidentiality, integrity, and authenticity by using Layer 3 encryption and authentication to provide an end-to-end solution. IPSec operates in two modes:

* Transport mode: Only the data is encrypted
* Tunnel mode: The entire packet is encrypted

The two main protocols used in IPSec are:

* Authentication Header (AH): Provides integrity, authentication, and non-repudiation
* Encapsulating Security Payload (ESP): Provides confidentiality (encryption) and limited authentication

Each pair of hosts communicating in an IPSec session must establish a security association.

A security association (SA) is a one-way connection between two communicating parties; thus, two SAs are required for each pair of communicating hosts. Additionally, each SA only supports a single protocol (AH or ESP). Therefore, if both an AH and ESP are used between two communicating hosts, a total of four SAs is required. An SA has three parameters that uniquely identify it in an IPSec session:

Security Parameter Index (SPI): The SPI is a 32-bit string used by the receiving station to differentiate between SAs terminating on that station. The SPI is located within the AH or ESP header.


* Destination IP address: The destination address could be the end station or an intermediate gateway or firewall, but must be a unicast address.
* Security Protocol ID: The Security Protocol ID must be either an AH or ESP association.

Key management is provided in IPSec by using the Internet Key Exchange (IKE). IKE is actually a combination of three complementary protocols: the Internet Security Association and Key Management Protocol (ISAKMP), the Secure Key Exchange Mechanism (SKEME), and the Oakley Key Exchange Protocol. IKE operates in three modes: Main Mode, Aggressive Mode, and Quick Mode.

### SSL

The Secure Sockets Layer (SSL) protocol operates at the Transport Layer of the OSI model. SSL VPNs have rapidly gained widespread popularity and acceptance in recent years due to their ease of use and low cost. An SSL VPN requires no special client hardware or software (other than a Web browser) and little or no client configuration. SSL VPNs provide secure access to Web-enabled applications and thus are somewhat more granular in control - a user is granted access to a specific application rather than to the entire private network. This can also be considered a limitation of SSL VPNs; not all applications will work over an SSL VPN and many convenient network functions (file and print sharing) may not be available over an SSL VPN.

### Intrusion detection and prevention systems (IDS and IPS)

Intrusion detection is defined as real-time monitoring and analysis of network activity and data for potential vulnerabilities and attacks in progress. One major limitation of current IDS technologies is the requirement to filter false alarms lest the operator (system or security administrator) be overwhelmed with data. Intrusion detection systems (IDS) are classified in many different ways including active and passive, network-based and host-based, and knowledge-based and behavior-based.

### Active and passive IDS

An active IDS (now more commonly known as an intrusion prevention system - IPS) is a system that’s configured to automatically block suspected attacks in progress without any intervention required by an operator. IPS has the advantage of providing real-time corrective action in response to an attack but has many disadvantages as well. An IPS must be placed in-line along a network boundary; thus, the IPS itself is susceptible to attack. Also, if false alarms and legitimate traffic haven’t been properly identified and filtered, authorized users and applications may be improperly denied access. Finally, the IPS itself may be used to effect a Denial of Service (DoS) attack by intentionally flooding the system with alarms that cause it to block connections until no connections or bandwidth are available.

A passive IDS is a system that’s configured to only monitor and analyze network traffic activity and alert an operator to potential vulnerabilities and attacks. It’s not capable of performing any protective or corrective functions on its own. The major advantages of passive IDS are that these systems can be easily and rapidly deployed and are not normally susceptible to attack themselves.

### Network-based and host-based IDS

A network-based IDS usually consists of a network appliance (or sensor) with a Network Interface Card (NIC) operating in promiscuous mode and a separate management interface. The IDS is placed along a network segment or boundary and monitors all traffic on that segment.

A host-based IDS requires small programs (or agents) to be installed on individual systems to be monitored. The agents monitor the operating system and write data to log files and/or trigger alarms. A host-based IDS can only monitor the individual host systems on which the agents are installed; it doesn’t monitor the entire network.

### Knowledge-based and behavior-based IDS

A knowledge-based (or signature-based) IDS references a database of previous attack profiles and known system vulnerabilities to identify active intrusion attempts. Knowledge-based IDS is currently more common than behavior-based IDS. Advantages of knowledge-based systems include:
It has lower false alarm rates than behavior-based IDS
Alarms are more standardized and more easily understood than behavior-based IDS

Disadvantages of knowledge-based systems include:

* Signature database must be continually updated and maintained.
* New, unique, or original attacks may not be detected or may be improperly classified.

A behavior-based (or statistical anomaly-based) IDS references a baseline or learned pattern of normal system activity to identify active intrusion attempts. Deviations from this baseline or pattern cause an alarm to be triggered. Advantages of behavior-based systems include that they:

* Dynamically adapt to new, unique, or original attacks
* Are less dependent on identifying specific operating system vulnerabilities

Disadvantages of behavior-based systems include:

* Higher false alarm rates than knowledge-based IDS
* Usage patterns that may change often and may not be static enough to implement an effective behavior-based IDS

## Remote access

Remote access is provided through various technologies (such as cable modems and wireless devices) and protocols (such as asynchronous dial-up, ISDN, xDSL), as we discuss in the earlier section “WAN technologies and protocols.”

Remote access security is provided through various methods and technologies as we describe in the following sections.


### Remote access security methods

Remote access security methods include restricted allowed addresses, caller ID, and callback.

### Restricted address

The restricted address method restricts access to the network based on allowed IP addresses, essentially performing rudimentary node authentication but not user authentication.

### Caller ID

The caller ID method restricts access to the network based on allowed phone numbers, thus performing a slightly more secure form of node authentication because phone numbers are more difficult to spoof than IP addresses. However, this method can be difficult to administer for road warriors that routinely travel to different cities.

### Callback

The callback method restricts access to the network by requiring a remote user to first authenticate to the remote access service (RAS) server. The RAS server then disconnects and calls the user back at a preconfigured phone number. Like caller ID, this method can be difficult to administer for road warriors.

One limitation of callback is that it can be easily defeated by using call forwarding.

## Remote access security technologies

Remote access security technologies include RAS servers that utilize various authentication protocols associated with PPP, RADIUS, and TACACS.

### RAS

Remote access service (RAS) servers utilize the Point-to-Point Protocol (PPP) to encapsulate IP packets and establish dial-in connections over serial and ISDN links. PPP incorporates the following three authentication protocols:

* **PAP**: The Password Authentication Protocol (PAP) uses a two-way hand-shake to authenticate a peer to a server when a link is initially established. PAP transmits passwords in clear text and provides no protection from replay or brute force attacks.
* **CHAP**: The Challenge Handshake Protocol (CHAP) uses a three-way handshake to authenticate both a peer and server when a link is initially established and, optionally, at regular intervals throughout the session. CHAP requires both the peer and server to be preconfigured with a shared secret that must be stored in plain text. The peer uses the secret to calculate the response to a server challenge by using an MD5 one-way hash function. MS-CHAP, a Microsoft enhancement to CHAP, allows the shared secret to be stored in an encrypted form.
* **EAP**: The Extensible Authentication Protocol (EAP) adds flexibility to PPP authentication by implementing various authentication mechanisms including MD5-challenge, S/Key, generic token card, digital certificates, and so on. EAP is implemented in many wireless networks.


### RADIUS

The Remote Authentication Dial-In User Service (RADIUS) protocol is an open-source, UDP-based client-server protocol. Defined in RFC 2058 and RFC 2059, RADIUS provides authentication and accountability. A user provides username/password information to a RADIUS client by using PAP or CHAP.

The RADIUS client encrypts the password and sends the username and encrypted password to the RADIUS server for authentication. Note: Passwords exchanged between the RADIUS client and RADIUS server are encrypted, but passwords exchanged between the PC client and the RADIUS client are not necessarily encrypted @md if using PAP authentication, for example. However, if the PC client happens to also be the RADIUS client, all password exchanges are encrypted regardless of the authentication protocol being used.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_b8d4c55fb5376dd7ff1ab005ca2a19c6.png)

### Diameter

The Diameter protocol is the next-generation RADIUS protocol. Diameter overcomes several RADIUS shortcomings. For instance, it uses TCP rather than UDP, supports IPSec or TLS, and larger address space. Diameter is defined by RFC 3588.

### TACACS

The Terminal Access Controller Access Control System (TACACS) is a UDP-based access control protocol, originally developed for the MILNET, which provides authentication, authorization, and accountability (AAA). The original TACACS protocol has been significantly enhanced, primarily by Cisco, as XTACACS (no longer used) and TACACS+ (the most common implementation of TACACS). TACACS+ is TCP-based (port 49) and supports practically any authentication mechanism (PAP, CHAP, MS-CHAP, EAP, token cards, Kerberos, and so on). The basic operation of TACACS+ is similar to RADIUS, including the caveat about encrypted passwords between client and server. The major advantages of TACACS+ are its wide support of various authentication mechanisms and granular control of authorization parameters.

---

# Network Attack mitigation

Most attacks against networks are Denial of Service (DoS) or Distributed Denial of Service (DDoS) attacks in which the objective is to consume a network’s bandwidth to make network services unavailable. But there are several other types of attacks, some of which are discussed in this section.

## SYN flood

In a SYN flood attack, TCP packets requesting a connection (SYN bit set) are sent to the target network with a spoofed source address. The target responds with a SYN-ACK packet, but the spoofed source never replies. Half-open connections are incomplete communication sessions awaiting completion of the TCP three-way handshake. These connections can quickly overwhelm a system’s resources while waiting for the half-open connections to time out. This causes the system to crash or otherwise become unusable.

SYN floods are countered on Cisco routers by using two features: TCP Intercept, which effectively proxies for the half-open connections; and Committed Access Rate (CAR), which limits the bandwidth available to certain types of traffic. Checkpoint’s FW-1 firewall has a feature known as SYN Defender that functions similar to the Cisco TCP Intercept feature. Other defenses include changing the default maximum number of TCP half-open connections and reducing the timeout period on networked systems.

## ICMP flood

In an ICMP flood attack, large numbers of ICMP packets (usually Echo Request) are sent to the target network to consume available bandwidth and/or system resources. Because ICMP isn’t required for normal network operations, the easiest defense is to drop ICMP packets at the router or filter them at the firewall.


## UDP flood

In a UDP flood attack, large numbers of UDP packets are sent to the target network to consume available bandwidth and/or system resources. UDP floods can generally be countered by dropping unnecessary UDP packets at the router. However, if the attack is using a required UDP port (DNS port 53), other countermeasures need to be employed.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_89cf0e2e3ab0a27d5af7066ce6be96f2.png)

## Smurf

A Smurf attack is a variation of the ICMP flood attack. (Read the earlier section “ICMP flood.”) In a Smurf attack, ICMP Echo Request packets are sent to the broadcast address of a target network by using a spoofed IP address on the target network. The target, or bounce site, then transmits the ICMP Echo Request to all hosts on the network. Each host then responds with an Echo Reply packet, overwhelming the available bandwidth and/or system resources. Countermeasures against Smurf attacks include dropping ICMP packets at the router.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_a01bc97dde3f0f78a3a78aaa91eb2abf.png)

## Fraggle

A Fraggle attack is a variant of a Smurf attack (see the preceding section) that uses UDP Echo packets (UDP port 7) rather than ICMP packets. Cisco routers can be configured to disable the TCP and UDP services (known as TCP and UDP small servers) that are most commonly used in Fraggle attacks.

## Teardrop

In a Teardrop attack, the length and fragmentation offset fields of sequential IP packets are modified, causing the target system to become confused and crash.


## Session hijacking (Spoofing)

IP spoofing involves altering a TCP packet so that it appears to be coming from a known, trusted source, thus giving the attacker access to the network.

* Network Countermeasures
* Access Control lists
* Firewalls
* Intrusion Detection System (IDS)
* Network based IDS
* Host based IDS
* Protection of network cabling
* Anti-virus software
* Private addressing
* 10.0.0.0/8, 172.16.0.0/12 and 192.168.0.0/16
* Close unnecessary ports and services
* Security patches
* Unified Threat Maangement (UTM)
* Security appliances that perform manu functions, such as firewall, IDS, IPS, Antivirus, Anti-spam and Web content filtering
* Gateways - filtering intermediaries


# Access Control

5.1: Physical and Logical Access Control
5.1: Physical and Logical Access Control
Different types of Access Control
Access controls are necessary to protect the confidentiality, integrity, and availability of objects (and by extension, their information and data).
In CISSP documentation, there was something about medieval castles and stuff...

## Control types

We have the classic set of controls:
* Preventive
* Detective
* Corrective
* Deterrent
* Recovery
* Compensating

![](https://gitlab.dclabra.fi/wiki/uploads/upload_e9ec723cfdb58639942cecc73445ea3d.png)
![](https://gitlab.dclabra.fi/wiki/uploads/upload_3ea5a8b7527d536c96c3bea856e66e73.png)

## Administrative controls

Administrative controls include the policies and procedures that an organization implements as part of its overall information security strategy. Administrative controls ensure that technical and physical controls are understood and properly implemented in accordance with the organization’s security policy. The purpose of administrative controls is often both preventive and detective. These may include:

* Policies and procedures
* Security awareness training
* Asset classification and control
* Employment policies and practices (background checks, job rotations, and separation of duties and responsibilities)
* Account administration
* Account, log, and journal monitoring
* Review of audit trails

## Technical controls

Technical (or logical) controls use hardware and software technology to implement access control.

Preventive technical controls include:

* Encryption: Data Encryption Standard (DES), Advanced Encryption Standard (AES), Merkle-Hellman Knapsack.
* Access control mechanisms: Biometrics, smart cards, and tokens.
* Access control lists
* Remote access authentication protocols: Password Authentication Protocol (PAP), Challenge Handshake Authentication Protocol (CHAP), Remote Authentication Dial-In User Service (RADIUS), Lightweight Directory Access Protocol (LDAP).

Detective technical controls include:

* Violation reports
* Audit trails
* Network monitoring and intrusion detection
* 

## Physical controls

Physical controls ensure the safety and security of the physical environment. These can be preventive or detective in nature.

Preventive physical controls include

* Environmental controls (for example: heating, ventilation, and air conditioning [HVAC])
* Security perimeters (fences, locked doors, and restricted areas)
* Guards and dogs

Detective physical controls include:

* Motion detectors
* Video cameras
* Environmental sensors and alarms (to detect heat, smoke, fire, and water hazards)

When a control failure results in no accesses permitted, this is called fail closed. When a control failure results in all accesses permitted, this is called fail open.

### Preventative access control

A preventative access control is deployed to stop unwanted or unauthorized activity from occurring. Examples of preventative access controls include fences, locks, biometrics, mantraps, lighting, alarm systems, separation of duties, job rotation, data classification, penetration testing, access control methods, encryption, auditing, presence of security cameras or closed circuit television (CCTV), smart cards, callback, security policies, security awareness training, and antivirus software.

### Penetration testing
Penetration Testing normally has 6 phases: Planning > Reconnaissance > Scanning (enumeration) > Vulnerability assessment > Exploitation > Reporting. The 6th phase for a real attack would be delete logs/evidence and install backdoors.

### Deterrent access control

A deterrent access control is deployed to discourage the violation of security policies. A deterrent control picks up where prevention leaves off. The deterrent doesn't stop with trying to prevent an action; instead, it ges further to exact consequences in the event of an attempted or successful violation. Examples of deterrent access controls include locks, fences, security badges, security guards, mantraps, security cameras, trespass or intrusion alarms, separation of duties, work task procedures, awareness training, encryption, auditing, and firewalls.

### Detective access control

A detective access control is deployed to discover unwanted or unauthorized activity. Often detective controls are after-the-fact controls rather than real-time controls. Examples of detective access controls include security guards, guard dogs, motion detectors, recording and reviewing of events seen by security cameras or CCTV, job rotation, mandatory vacations, audit trails, intrusion detection systems, violation reports, honey pots, supervision and reviews of users, incident investigations, and intrusion detection systems.

### Corrective access control

A corrective access control is deployed to restore systems to normal after an unwanted or unauthorized activity has occurred. Usually corrective controls have only a minimal capability to respond to access violations. Examples of corrective access controls include intrusion detection systems, antivirus solutions, alarms, mantraps, business continuity planning, and security policies.

### Recovery access control

A recovery access control is deployed to repair or restore resources, functions, and capabilities after a violation of security policies. Recovery controls have more advanced or complex capability to respond to access violations than a corrective access control. For example, a recovery access control can repair damage as well as stop further damage. Examples of recovery access controls include backups and restores, fault tolerant drive systems, server clustering, antivirus software, and database shadowing.

Compensation access control a compensation access control is deployed to provide various options to other existing controls to aid in the enforcement and support of a security policy. Examples of compensation access controls include security policy, personnel supervision, monitoring, and work task procedures.

Compensation controls can also be considered to be controls used in place of or instead of more desirable or damaging controls. For example, if a guard dog cannot be used because of the proximity of a residential area, a motion detector with a spotlight and a barking sound playback device can be used.

### Directive access control

A directive access control is deployed to direct, confine, or control the actions of subject to force or encourage compliance with security policies. Examples of Directive access controls include security guards, guard dogs, security policy, posted notifications, escape route exit signs, monitoring, supervising, work task procedures, and awareness training.

Access controls can be further categorized by how they are implemented. In this case, the categories are administrative, logical/technical, or physical.

Administrative access controls Administrative access controls are the policies and procedures defined by an organizations security policy to implement and enforce overall access control. Administrative access controls focus on two areas: personnel and business practices (e.g., people and policies). Examples of administrative access controls include policies, procedures, hiring practices, background checks, data classification, security training, vacation history, reviews, work supervision, personnel controls, and testing.

Logical/technical access controls Logical access controls and technical access controls are the hardware or software mechanisms used to manage access to resources and systems and provide protection for those resources and systems. Examples of logical or technical access controls include encryption, smart cards, passwords, biometrics, constrained interfaces, access control lists (ACLs), protocols, firewalls, routers, intrusion detection systems, and clipping levels.

## Access control services

Access control systems provide three essential services:

* Authentication/Identification
* Authorization
* Accountability

### Authentication/Identification

Authentication (who can log in) is actually a two-step process consisting of identification and authentication (I&A). Identification is the means by which a user claims a specific identity to a system. Authentication is the process of verifying that identity. For example, a username/password combination is one common technique (albeit a weak one) that demonstrates the concepts of identification (username) and authentication (password).
Authentication determines who can log in.

* **Something you know**, such as a password or a personal identification number (PIN): This concept is based on the assumption that only the owner of the account knows the secret password or PIN needed to access the account. Of course, passwords are often shared, stolen, guessed, or otherwise compromised.
* **Something you have**, such as a smart card or token: This concept is based on the assumption that only the owner of the account has the necessary key to unlock the account. Of course, keys are often lost, stolen, borrowed, or duplicated.
* **Something you are**, such as fingerprint, voice, retina, or iris characteristics: This concept is based on the assumption that the finger or eyeball attached to your body is actually yours and uniquely identifies you. Of course, fingers and eyes can be lost or. . . . Actually, the major drawback with this authentication mechanism is **acceptance** - people are uneasy about using these systems.

***Hacker=good, Cracker=bad***.
Hackers perform a vital role in the Internet and computing community by helping to debug source code, identify vulnerabilities, and improve software development - all of which serve the greater good. Conversely, crackers typically include script kiddies, cyberpunks, cyberterrorists, common criminals, and other vermin . . . all motivated by less noble causes.

#### Passwords

* Human nature: Write them down, share them, use easy to remember, weak passwords, automate logins, not logging off.
* Transmission and storage: FTP and PAP for example transmit passwords in clear text. Passwords may also be stored in plain text files or by using a weak hashing algorithm.
* Easily broken: Brute force and dictionary attacks.
* Refutable: Don't guarantee absolute proof of identity.

***Do's:***

* Lenght: Min 6-8, set max to avoid *memory-overflow* attacks
* Complexity
* Aging: max 30,60,90 days, min 1 day
* History: Remember 5 last passwords, so user can't just add a number after the last password.
* Limited attempts: 3 recommended
* Lockout duration: 30 minutes recommended
* Limited time periods: Only accesible on work hours
* System messages
    * Logon banner: Instead of "Welcome", have a legal warning
    * Last username: Disable
    * Last successful logon: Enable

#### Biometrics

* **Physical access controls**: The individual presents the required biometric characteristic, and the system attempts to identify the individual by matching the input characteristic to its database of authorized personnel. This is also known as a one-to-many search.
* **Logical access controls**: The user enters a username or PIN (or inserts a smart card) and then presents the required biometric characteristic for verification. The system attempts to authenticate the user by matching the claimed identity and the stored biometric image file for that account. This is also known as a one-to-one search.

**False Reject Rate (FRR)** or Type I error: The percentage of authorized users who are incorrectly denied access.
**False Accept Rate (FAR)** or Type II error: The percentage of unauthorized users who are incorrectly granted access.
**Crossover Error Rate (CER)**: The point at which the FRR equals the FAR, stated as a percentage.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_e482f2cb0cf72b9c604c13207d7c09e0.png)

#### Single sign-on (SSO)

Woo-hoo!: After you’re authenticated, you’ve got the keys to the kingdom. Read that as unrestricted access to all authorized resources!
Labor intensive: SSO can be difficult and time consuming to implement. But, hey - that’s why you get paid (or should get paid) the big bucks!

#### Kerberos

The Kerberos client prompts the subject (such as a user) for identification and authentication (username and password). Using the authentication information (password), the client temporarily generates and stores the subject’s secret key by using a one-way hash function and then sends the subject’s identification (username) to the Key Distribution Center (KDC). The password/secret key is not sent to the KDC.
![](https://gitlab.dclabra.fi/wiki/uploads/upload_026f3f940ab5d40a8a2c654a7c0888ea.png)
The KDC Authentication Service (AS) verifies that the subject (known as a principal) exists in the KDC database. The KDC Ticket Granting Service (TGS) then generates a Client/TGS Session Key encrypted with the subject’s secret key, which is known only to the TGS and the client (temporarily). The TGS also generates a Ticket Granting Ticket (TGT), comprising the subject’s identification, the client network address, the valid period of the ticket, and the Client/TGS Session Key. The TGT is encrypted by using the secret key of the TGS server, which is known only to the TGS server. The Client/TGS Session Key and TGT are then sent back to the client.
![](https://gitlab.dclabra.fi/wiki/uploads/upload_d18571c658071476e26229c9a087484a.png)
The client decrypts the Client/TGS Session Key with the secret key that was generated by using the subject’s password, authenticates the subject (user), and then erases the stored secret key to avoid possible compromise. The TGT, which was encrypted with the secret key of the TGS server, cannot be decrypted by the client. 
![](https://gitlab.dclabra.fi/wiki/uploads/upload_1717b44b7bbdf0146e670a523d6898d3.png)
When the subject requests access to a specific object (such as a server, also known as a principal), it sends the TGT, the object identifier (such as a server name), and an authenticator to the TGS server. The authenticator is a separate message that contains the client ID and a timestamp, and using the Client/TGS Session Key encrypts it. See Figure 4-5.
![](https://gitlab.dclabra.fi/wiki/uploads/upload_a6fe7258ae02bae8a65a4586b09fd765.png)
The TGS server generates both a Client/Server Session Key, which is encrypted by using the Client/TGS Session Key, and a Service Ticket, which comprises the subject’s identification, the client network address, the valid period of the ticket, and the Client/Server Session Key. The Service Ticket is encrypted by using the secret key of the requested object (server), which is known only to the TGS server and the object. The Client/Server Session Key and Service Ticket are then sent back to the client. 
![](https://gitlab.dclabra.fi/wiki/uploads/upload_7bcb4dbfa6d8d4be7b2132333fc1096d.png)
The client decrypts the Client/Server Session Key by using the Client/Server TGS Key. The Service Ticket, which was encrypted with the secret key of the requested object, cannot be decrypted by the client. 
![](https://gitlab.dclabra.fi/wiki/uploads/upload_5e105a05677b1e2ef6ba51e079fe3790.png)
The client can then communicate directly with the requested object (server). The client sends the Service Ticket and an authenticator to the requested object (server). The authenticator, comprising the subject’s identification and a timestamp, is encrypted by using the Client/Server Session Key that was generated by the TGS. The object (server) decrypts the Service Ticket by using its secret key. The Service Ticket contains the Client/Server Session Key, which allows the object (server) to then decrypt the authenticator. If the subject identification and timestamp are valid (according to the subject identification, client network address, and valid period specified in the Service Ticket), then communication between the client and server is established. The Client/Server Session Key is then used for secure communications between the subject and object.
![](https://gitlab.dclabra.fi/wiki/uploads/upload_79b1ad19698a60f180874ad502dd2a85.png)

#### Identity as a Service (IDaaS)

![](https://gitlab.dclabra.fi/wiki/uploads/upload_9a77d2fd2b57ac88499cbd4118525570.png)

* Also called "Cloud identity"
* Integrates easily with cloud hosted applications and third party services
* Easier deployment of two-factor authentication
* Compounds challenges with internal identity management and account/access revocation
* Larger attack services
* IdaaS enables IT to create a security policy for application from user roles:
* Digital Identity (IDAAS) also provide users a Cloud portal with their applications and data accessible in one click (or tap the touch screen). The best solutions to IDAAS also create a secure access policy that protects application data. Safety rules that include the user, role, network, device type, time, location, and many other elements too, can be implemented to ensure access to certain users only.
* Securing devices used to access the company’s business data:
* The establishment of a truly effective application security policy means the implementation of a security policy of the devices used to access these applications. Today we use personal devices (BYOD) enterprise, a password must at least be provided to locate
* Example of IDaaS: Microsoft Accounts (formerly Microsoft Live ID)

### Authorization

Authorization (also referred to as establishment) defines the rights and permissions granted to a user account or process (what you can do). After a user is authenticated, authorization determines what that user can do with a system or resource.
Authorization (or establishment) determines what a subject (either a person or a system) can do.

* Both operating systems and applications can provice this functionality
* Authorization can be provided based on user, groups, roles, rules, physical location, time of day (Temporal isolation)* or transaction type (example a teller may be able to withdraw small amounts but require a manager for large withdrawals
* Authorization principals
* Default NO access (implicit deny)
* "Need to Know"
* Authorization creep
    * Permissions accumulate over time even if you don't need then anymore)
* Auditing authorization can help mitigate this. SOX requires yearly auditing


### Accountability

Accountability is the ability to associate users and processes with their actions (what they did). Audit trails and system logs are components of accountability. An important security concept that’s closely related to accountability is non-repudiation. Non-repudiation means that a user (user-name Madame X) can’t deny an action because her identity is positively associated with her actions.
Non-repudiation means that a user cannot deny an action.