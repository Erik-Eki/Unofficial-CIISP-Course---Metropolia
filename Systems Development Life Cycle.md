Systems Development Life Cycle
=

![](https://gitlab.dclabra.fi/wiki/uploads/upload_9afc41b087a0001fa7412dbdc27fb259.png)

# The Open Web Applications Security Project

The Open Web Application Security Project, or OWASP, has published a short list of standards that have been adopted by organizations, most notably the Payment Card Institute and its Data Security Standard (PCI DSS). The top ten software vulnerabilities cited by OWASP are:


* Unvalidated input
* Broken access control
* Broken authentication and session management
* Cross-site scripting (XSS) flaws
* Buffer overflows
* Injection flaws
* Improper error handling
* Insecure storage
* Denial of service
* Insecure configuration management

# Steps of Development
* Conceptual definition
    *  “Attractive, fits in the palm of the hand, intuitive VCR-like controls, long battery life, holds thousands of songs.”
* Functional requirements
    * Marketing department's wishes.
    * "Weight: no more than 2 oz, battery life: 500 hrs, capacity: 100,000 songs, quality: DVD-audio and video quality"
* Functional specifications
    * What the engineering department can actually do.
    * "Weight: 5.5 oz, battery life: 20 hrs, capacity: 20,000 songs, quality: DVD–quality video and audio"
* Design
    * Entity-relationship diagrams, data flow diagrams, database schemas, over-the-wire protocols, and more.
* Coding
    * Coding usually includes unit testing.
* Code review
    * A bunch of prima donna engineers examine each other’s program code and get into religious arguments about levels of indenting and the correct use of curly braces. 
* Unit test
    * Testing the pieces separately
* System test
    * Occurs when all the components of the entire system have been assembled, and the entire system is tested from end to end
* Certification
    * The formal evaluation of the system. The system is declared fully functional. Every intended feature performs as planned.
* Accreditation
    * The people in the mahogany offices have said that it’s okay to put the system into production. That could be to offer it for sale, build and ship, or whatever put into production means in your organization.
* Maintenance
    * At this point, the system is in production, and now its customers start putting in change requests because of a bunch of bone-headed mistakes made while developing requirements and specifications
    * Good documentation in the form of those specification and design documents is important because the developers who wrote this system have probably moved on to some other cool project . . . and the new guys who don’t know beans are left to maintain it.
* Notes about the life cycle
    * Larger organizations implement the software development life cycle with a complex, formal process.
    * The seemingly expensive overhead of project management and all these reviews, approvals, and so on are intended to prevent the organization from making costly mistakes by pushing a project along too fast and possibly skipping important steps.
* Change Management
    * The "What"
    * The process of approving modifications to a production environment
    * Performed by a Change Review Board, which has members from departments such as Development, Operations, and Customer Support, as well as other stakeholders in the organization
* Configuration Management
    * The "How"
    * The process of recording modifications to a production environment

# Software Development

## Agile Software Development
* Agile methods include Scrum and Extreme Programming (XP)
* Agile Manifesto:
    * "We are uncovering better ways of developing software by doing it and helping others do it. Through this work we have come to value:
        * Individuals and interactions over processes and tools
        * Working software over comprehensive documentation
        * Customer collaboration over contract negotiation
        * Responding to change over following a plan"

## Scrum
* Stop running the relay race
    * Doing only one step and handing off the project
* Take up rugby
    * A team foes the distance as a unit

## Software Development Life Cycle SDLC
* System or software development benefits from a formal project management structure (life cycle of systems development)
* It has been shown that it is better to follow a collection of proven processes used to design, develop, test, implement and maintain proprietary software
* Produce a quality product that meets users needs
* Balance application security with performance and stability from the start of the project to delivery
* Stay within budget and deliver a secure product on time
* As each goal is achieved, new ones are often set

## The Broader Systems Development Life Cycle
* Systems Development Life Cycle (SDLC): methodology for design and implementation of information system within an organization transitioning through various p**hases**
* SDLC is a formal process for problem solving based on a structured sequence of procedures
* Security is considered from **start to finish**
* Using a mandatory methodology
    * Ensures a rigorous process to manage a complex process
    * Increases probability of success and customer satisfaction
    * Code is reviewed by someone other than the programmer
* Agile SDLC - iterative process absed on feedback
* Traditional SDLC framework consists of 6 phases

## Software Development Life Cycle phases
Six phases of SDLC are:

1. Analyze
    * Customer Input & Review after phase 1
2. Quote & Approve
3. Mockup
    * For example: creating user interfaces that show the end user what the software will look like without having to build the software or the underlying functionality
    * Customer Input & Review after phase 3
4. Create
    * Software is developed
5. Stage & Test
    * Making sure that the software is functioning properly
    * Customer Input & Review after phase 5
6. Release
    * Software goes in to production mode
    * Move back to Analyze phase if necessary

## Software Escrow
* Third party archives source code of proprietary software
* Source code is revealed if the product is orphaned
* ## Code Repository Security
* Like GitHub
* Contents must be protected
* Developers shouldn't publish code that contains secrets
## DevOps
* Old system had strict separation of duties betweem developers, quality assurance and production
* DevOps is more agile, with everyone working together in the entire service lifecycle

## What is wanted an/or needed for success
Initiation - Could we solve a business problem?

* In any successful project you must clearly define where you are going to be able to get there
* What does the customer say they want?
* Evaluate their need carefully and repeat it back
* Probe for possible additional future wants or needs
* Make suggestion and try to guide them to a total solution
* Evaluate their environment, people polcies and hardware
* Ask stakeholder to provide stories of what they expect
* Write estimates up from the customer's perspective

## NIST SDLC
* SP 800-64 is depicted below:

![](https://gitlab.dclabra.fi/wiki/uploads/upload_ac92b393359a65fa14907b13d7d241e2.png)


# Database Security in Software Development
## Database
* Structured collection of data
* Databases allow
* Queries (searches)
* Insertions
* Deletions
* Database Management Systems (DBMS)
* Controls all access to the database
* Enforces Database security

## Database Concepts
* Database Administrator (DBA)
* Query language
* For example. Structured Query Language (SQL)
* Interference attack
* Enumerating low-privilege data to find missing items which must be high-privilege
* Aggregation attack
* Combining many low-privilege records to deduce high-privilege data

## Types of databases
* Relational
* Hierarchical
* Object-oriented
* Flat file
    * Simple text file

## Relational Database Terms
* Tables have rows (records or tuples) and columns (fields or attributes)
* Primary Key field is guaranteed to be unique, like a SSN
* Foreign key is a field in another table that matched the primary key
* Join connects two tables by a matching field

## Integrity
* **Referential** integrity
    * Foreign keys match primary keys
* **Semantic** integrity
    * Field values match data type (no letters in numerical fields)
* **Entity** integrity
    * Each tuple has a non-null primary key

![](https://gitlab.dclabra.fi/wiki/uploads/upload_1531dad36e9cb0c44af38280bc26c58a.png)


## Database Normalization
* Removes redundant data

## Database Views
* Contained user interface
* Shows only some data and options
* Like a PoS (point of Sale) device

## Data dictionary
* Describes the tables
* This is metadata - data about data
* Database schema
    * Describes the attributes and values of the tables

## Simple database schema

![](https://gitlab.dclabra.fi/wiki/uploads/upload_8c9f85be9ff3692bd8a0f16575de1611.png)

## Database Integrity
* Mitigate unauthorized data modification
* Two users may attempt to change the same record simultaneously
* The DBMS attempts to **commit** an update
* If the commit is unsuccesful, the DBMS can **rollback** and restore from a **save point**
* **Database journal** logs all transactions

## Database Replication and Shadowing
* Highly Available (HA) databases
    * Multiple servers
    * Multiple copies of tables
* Database replication
    * Mirrors a live database
    * Original and copy are in use, serving clients
* Shadow database
    * Live backup, not used

## Data Warehousing and Data Mining
* Data Warehouse
    * A large collection of data
    * Terabytes (1000 GB)
    * Petabytes (1000 TB)
* Data Mining
    * Searching for patterns
    * For example. credit card fraud
