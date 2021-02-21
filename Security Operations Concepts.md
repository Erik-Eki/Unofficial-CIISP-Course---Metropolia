Security Operations Concepts
=

# Handling sensitive information


Sensitive information such as financial records, employee data, and information about customers must be handled according to these guidelines:

1. Marking: This refers to the words that must appear on documents containing sensitive information. An example marking might read Company confidential, handle according to instructions.
1. Handling: The organization should have established procedures for the handling of marked documents. These procedures detail how such documents may be transported, faxed, e-mailed, and sent over networks.
1. Storage: Similar to the handling guideline, the organization must have procedures and requirements specifying how marked information must be stored.
1. Destruction: Sooner or later, a document with sensitive information must be destroyed. The organization must have procedures detailing how to destroy sensitive information that is retained, regardless of whether the data is in a hard copy format or is saved as an electronic file.

# Background checks and security clearances

Pre-and post-employment background checks can provide an employer with valuable information about an individual being considered for a job or position within an organization. Such checks can give an immediate indication of an individual’s integrity and can help screen out unqualified applicants.

Basic background checks should be conducted for all personnel with access to sensitive information or systems within an organization. A basic background check should include


* Reference checks: Personal, professional, and employment
* Verification of data in employment applications and resumes: Social Security numbers, education, professional/technical certifications, military records, and previous employment
* Other records: Court, local law enforcement, and motor vehicle records

Personnel who fill more sensitive positions should undergo a more extensive pre-employment screening and background check, possibly including


* Credit records
* Drug testing
* Special background investigation: FBI and INTERPOL records, field interviews with former associates, or a personal interview with a private investigator

Periodic post-employment screenings (such as credit records and drug testing) may also be necessary, particularly for personnel with access to financial data or personnel being considered for promotions to more sensitive or responsible positions.


# Hiring and termination practices

Hiring and termination practices should be formalized within an organization to ensure fair and uniform treatment and to protect the organization and its information assets.

Standard hiring practices should include background checks and employment agreements (as we discuss in the earlier section “Background checks and security clearances”), as well as a formal indoctrination and orientation process. This process may include formal introductions to key organizational personnel, creating user accounts and assigning IT resources (PCs and notebook computers), assigning security badges and parking permits, and a general policy discussion with human resources personnel.

Formal termination procedures should be implemented to help protect the organization from potential lawsuits, property theft and destruction, unauthorized access, or workplace violence. Procedures should be developed for various scenarios including resignations, termination, layoffs, accident or death, immediate departures versus prior notification, and hostile situations. Termination procedures may include:

* Surrendering keys, security badges, and parking permits
* Conducting an exit interview
* Security escort to collect one’s personal belongings and/or to leave the premises
* Returning company materials (notebook computers, mobile phones, PDAs)
* Changing door locks and system passwords
* Formal turnover of duties and responsibilities
* Removing network and system access and disabling user accounts
* Policies regarding retention of e-mail, personal files, and employment records
* Notification of customers, partners, vendors, and contractors, as appropriate

# Owner

An information owner is normally assigned at an executive or senior-management level within an organization, such as director or vice-president. An information owner doesn’t legally own the information that he or she is assigned; the information owner is ultimately responsible for the safeguarding of assigned information assets and may have fiduciary responsibility or be held personally liable for negligence in protecting these assets under the concept of due care.

Typical responsibilities of an information owner may include


* Determining information classification levels for assigned information assets
* Determining policy for access to the information
* Maintaining inventories and accounting for assigned information assets
* Periodically reviewing classification levels of assigned information assets for possible downgrading, destruction, or disposal
* Delegating day-to-day responsibility (but not accountability) and functions to a custodian

# Custodian

An information custodian is the individual with day-to-day responsibility for protecting information assets. IT systems or network administrators often fill this role. Typical responsibilities may include:

* Performing regular backups and restoring data when necessary
* Ensuring that directory and file permissions are properly implemented and provide sufficient protection
* Assigning new users to appropriate permission groups and revoking user privileges, when required

The distinction between owners and custodians, particularly regarding their different responsibilities, is an important concept in information security management. The information owner is the individual that has ultimate responsibility for the security of the information, whereas the information custodian is the individual responsible for the day-to-day security administration.

# Users

An end-user (or user) includes just about everyone within an organization. Users aren’t specifically designated. They can be broadly defined as anyone with authorized access to an organization’s internal information or information systems. Typical user responsibilities include


* Complying with all security requirements defined in organizational policies, standards, and procedures, applicable legislative or regulatory requirements, and contractual requirements (such as non-disclosure agreements and service-level agreements)
* Exercising due care in safeguarding organizational information and information assets
* Participating in information security training and awareness efforts
* Reporting any suspicious activity, security violations, security problems, or security concerns to appropriate personnel

# Separation of duties and responsibilities

The concept of separation (or segregation) of duties and responsibilities ensures that no single individual has complete authority and control of a critical system or process. This practice promotes security in the following ways:

* Reduces opportunity for waste, fraud, or abuse
* Provides two-man control (or dual-control, two-person integrity)
* Reduces dependence on individuals

In smaller organizations, this practice can sometimes be difficult to implement because of limited personnel and resources.


# Job rotations

Job rotations (or rotation of duties) are another effective security control with many benefits to an organization. Similar to the concept of separation of duties and responsibilities, job rotations involve regularly transferring key personnel into different positions or departments within an organization. Job rotations benefit an organization in the following ways:


* Reduce opportunity for waste, fraud, or abuse
* Reduce dependence, through cross-training opportunities, on individuals; also promotes professional growth
* Reduce monotony and/or fatigue for individuals

As with the practice of separation of duties, job rotations can be difficult to implement in smaller organizations.

 Tip   A side-benefit of job rotations is that persons are far less likely to commit fraudulent activities, for fear that they will be caught if they are unexpectedly rotated into another position.
 
# Logging Techniques

* Logging is the process of recording information about events to a log file or database
* Logging captures events, changes, messages and other data that describe activities that occured on a system
* When information is needed about an incident, logs are a good place to start
* Logics will commonly record these details:
    * What happened
    * When it happened
    * Where it happened
    * Who did it
    * How it happened (sometimes)

## Common Log Types
* Security Logs
    * Record access to resources such as files, folders, printers
* System Logs
    * Records systems events such as when a system/service starts or stops
    * Can help administrators to detect potentially malicious activity
* Application Logs
    * Record information related to specific application
    * For example a database developer can record when anyone accesses specific objects such as tables or views
* Firewall Logs
* Proxy Logs
* Change Logs
    * As part of an overall change management process
    * After a disaster administrators can can use change logs to return system to its last known state, including all applied changes

# Clipping Levels

Have you ever tried to log in to your workplace 300 times at 4 a.m.? Most people have not, and that's where clipping levels come in. Clipping levels are a way to allow users to make an occasional mistake. A clipping level is a threshold for normal mistakes a user may commit before investigation or notification begins.

   
A clipping level establishes a baseline violation count to ignore normal user errors.

The clipping level allows the user to make an occasional mistake, but if the established level is exceeded, violations are recorded or some type of response occurs. Look no further than your domain controller to see a good example of how clipping levels work. As a domain administrator, you might allow users to attempt to log in three times with an incorrect password. If the user can't get it right on the third try, the account is locked and he or she is forced to call an administrator for help. If an administrator or help-desk personnel is contacted to reset a password, some second type of authentication should be used to protect against a social-engineering attack.

To prevent social-engineering attacks, individuals who call to have their password reset should be required to provide additional authentication, such as date of birth, PIN, or passphrase.

# Preventative Measures
* Intrusion Detection System
    * Detects malicious actions
* Intrusion Prevention System
    * Prevents malicioous actions
* Network-based
    * Protects a whole network
* Host-based
    * Protects only one host

![](https://gitlab.dclabra.fi/wiki/uploads/upload_51727b64ec536d4086b7e100b2c23173.png)
![](https://gitlab.dclabra.fi/wiki/uploads/upload_5eb9df48f8b1d977b2c0b3a458b9c746.png)

## Types of IDS
* Pattern matching
    * Compares events to static signatures
* Protocol behavior
    * Detects protocol errors, like SYN/FIN TCP packets
* Anomaly detection
    * Reports traffic that varies from normal baseline

## Security Information and Event Management (SIEM)
* Correlates data from many sources
* Continuous Monitoring
* Now recommended, replacing the earlier Certification and Accrediation approach of examining a system once every 3 years

## Endpoint Security
* Security suites, including
    * Antivirus, application whitelisting, removable media contols, disk encryption, Host Intrusion Prevention Systems and firewalls

## Antivirus
* Mostly depend on signature detection
    * Blacklisting
* Application whitelisting
    * Only allow known good software to run
    * May use
        * File path and name
        * Hash
        * Code Signature

## Honeypots
* System designed to attract attackers
* May have legal risks
    * Attacker may claim they were invited in
* Honey nets
    * Real or simulated network of honeypots