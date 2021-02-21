CISSP - Threats, Risks and Recovery
=

# Threat Modeling

![](https://gitlab.dclabra.fi/wiki/uploads/upload_6552620a0cddbb612ef79e3e94cf17e3.png)


Threat modeling allows system security staff to communicate the potential damage of security flaws and prioritize remediation efforts.

Threat modeling procedures:
- Identify the assets
    - Entry and Exit point
    - System assets and resources
    - Trust levels (acces categories)
- Describe the architecture
- Break down the applications
- Identify the threats
- Document and classify the threats
- Rate the threats

Threat modeling covers the following:

- Assets - what valuable data and equipment should be secured?
- Threats - What may an attacker do to the system?
- Vulnerabilities - What flaws in the system all an attacker to realize a threat?

---

# Risk management
Risk management is about determining levels of risk, from the initial risk to the “worst case scenario”. It’s about getting the risk level to acceptable levels.
#### Risk assessment
Carrying out a risk assessment from the perspective of the protection of sensitive data is called a privacy impact analysis.
#### Risk vs. Privacy
Privacy is different from security. Privacy indicates the amount of control an individual should be able to have and expect as it relates to the release of their own sensitive information. Security is the mechanisms that can be put into place to provide this level of control.
It is becoming more critical (and more difficult) to protect personal identifiable information (PII) because of the increase of identity theft and financial fraud threats. PII is a combination of identification elements (name, address, phone number, account number, etc.). Organizations must have privacy policies and controls in place to protect their employee and customer PII.

---
NIST 800-30 is a Standard Risk Management Guide for Information Technology. It contains 9 steps on risk management listed below:

- System Characterization
- Threat Identification
- Vulnerability Identification
- Control analysis
- Likelihood Determination
- Impact Analysis
- Risk Determination
- Control Recommendations
- Results Documentation


#### NIST Special Publication 800-37
NIST 800-37 provides four steps for Applying the Risk Management Framework to Federal Information Systems.

1. NIST 800-37 Step 1
    Initiation Phase - IS and risk mitigation plan is researched.

2. NIST 800-37 Step 2
    Security Certification Phase - security of the system is assessed and documented.

3. NIST 800-37 Step 3
    Security Accreditation Phase - Decision to accept the risk is made and documented by the approving authority.

4. NIST 800-37 Step 4
    Continuous Monitoring Phase - ongoing security of the system is verified


#### Qualitative Risk Assesment
For a given scope of assets, identify:
- Vulnerabilities
- Threats
- Threat probability (Low / Medium / High)
- Impact (Low / Medium / High)
- Countermeasures

#### Quantitative Risk Assesment
Extension of a qualitative risk assessment

Metrics for each risk are:
- Asset value: replacement cost and/or income derived through the use of an asset
- Exposure Factor (EF): Portition of asset's value lost through a threat
- Single Loss Expectancy (SLE) = Asset ($) x EF (%)
- Annualized Rate of Occurence (ARO): Propability of loss in a year
- Annualized Loss Expectancy (ALE) = SLE ($) x ARO (%)

### Handling Risk
The best way to handle a risk depends of the cost, value of assets and how much actual risk is reduced.
Here's how to calculate it:
- Threat * Vulnerability * Asset value = Total risk
- Total risk - Countermeasures = Residual risk

---
* Risk reduction
    * Implement a countermeasure to alter or reduce the risk.

* Risk transference
    * Purchase insurance to transfer a portion or all of the potential cost of a loss to a third party.

* Risk acceptance
    * Deal with risk by accepting the potential cost and loss if the risk occurs.

* Risk rejection
    * Pretend that the risk doesn’t exist and ignore it. Although this is not a prudent course of action, it is one that some organizations choose to take.

---

## Business Continuity
Business continuity is about keeping the company afloat after a disaster. It's not just technological and virtual disasters, but also natural, human and envronmental.
There are new regulatory requirements that infer executive management obligations for fiscal responsibility.
The safety of the organization's personnel should be guaranteed at the expense of efficient or even successful restoration of operations or recovery of data.

### Physical Recovery

#### Recovery team
Selection criteria

- Location of residence
- Skills and experience
- Ability and willingness to respond
- Health and family (determines probability to serve)
- Identify backups
    - Other team members, external resources
#### Emergency response
- Personnel safety: includes first-aid, searching for pesonnel, etc
- Evacuation: evacuation procedures to prevent any hazard to employees
- Asset protection: includes buildings, vehicles and equipment
- Damage assessment: this could involve outside structural engineers to assess gamae to buildings and equipment
- Emergency notification: response team communication, and keeping management and organization staff informed
#### Public utilities and infrastructure
- Often interrupted during a disaster
- Electricity: UPS (Uninterruptible Power Supply), generator
- Water: building could be closed if no water is available for fire suppression
- Natural gas: heating
- Wasterwater: if disabled, building could be closed
- Steam heat
#### Logistics and supplies
- Food and drinking water
- Blankets and sleeping cots
- Sanitation (toilets, showers, etc)
- Tools
- Spare parts
- Waste bins
- Information
- Communications
- Fire protection (extinguishers, sprinklets, smoke alarms, fire alarms)
#### Business resumption planning
- Alternate work locations
- Alternate personnel
- Communications
    - Emergency, support of business processes
- Standby assets and equipment
- Access to procedures, business records
#### Restoration and recovery
- Repairs to facilities, equipment
- Replacement equipment
- Restoration of utilies
- Resumption of business operations in primary business facilities
#### Improving system resilience and recovery
- Off-site media storage
    - Assurance of data recovery
- Server clusters
    - Improved availability
    - Geographics clusters: members far apart
- Data replication
    - Application, DMBS, OS or Hardware
    - Maintains current data on multiple servers even in remote places

### Business Continuity Plan (BCP)
BCP's goal is to ensure that the business will continue to operate before, throughout and after a disaster. BCP is a long-term strategy on keeping the organization operational in in a different location and/or with different tools.
BCP cycle:
- Identification
- Prevention
- Declaration
- Escalation
- Containment
- implementation
- Recovery
    - Business Recovery
        - Facility
        - Operations
    - Process Recovery
        - Human resources
        - Business Unit
    - It Recovery
        - Data
        - Telecommunication
Business as usual -> Disaster occurs -> Recovery Point Objective(RPO) -> Recovery Time Objective(RTO) -> Word Recovery Time(WRT)
RTO + WRT = Moximum Tolerable Downtime(MTD)

### Disaster Recovery Plan (DRP)
The DRP provides a short-term plan for dealing with specific IT-oriented disruptions. It deals with getting the organization operating normally by recovering critical IT-systems after a disaster and does not go into the long-term impacts of the disaster to the organization.

### Integrating Security Risk Considerations into Acquisition Strategy and Practice
This is about minimizing the introduction of new or unknown risks into the organization. It is often said that security in an organization is only as strong as its *weakest link*. When organizations have a merger or acquisition, one is more secure than the other so before merging sufficient security analysis and measures are to be taken.
A minimum security requirements are to be established and may require a transition period. Just merging these aren't really viable, because there may be many instances of overlap, underlap, and contradiction between the organizations security requirements.
How Facebook Moved 20 Billion Instagram Photos Without You Noticing: https://www.wired.com/2014/06/facebook-instagram/

Any new hardware, software or services should be evaluated before aquirement on how it will impact the organization’s overall security and risk posture, and how it will affect other hardware, software, or services already in place within the organization. For example, integration issues can have a negative impact on a system’s integrity and availability.
Third-party assessments and monitoring should also be evaluated. Contracts (including privacy, non-disclosure requirements, and security requirements) and service-level agreements (SLAs, discussed later in this section) should be reviewed to ensure that all important security issues and regulatory requirements still are addressed adequately.

Service-level agreements (SLAs) establish minimum performance standards for a system, application, network, or service. An organization establishes internal SLAs to provide its end-users with a realistic expectation of the performance of its information systems and services. 
For example, an SLA with an Internet service provider might establish a maximum acceptable downtime which, if exceeded within a given period, results in invoice credits or (if desired) cancellation of the service contract.

---

# Awareness, training and education within organization
Security awareness is an often-overlooked factor in an information security program. Although security is the focus of security practitioners in their day-to-day functions, it’s often taken for granted that common users possess this same level of security awareness. As a result, users can unwittingly become the weakest link in an information security program.
Security is constantly in flux so it is required to keep awareness, training and education up-to-date and people's knowledge needs to updated. These should be tested at least once a year.
Employees and personnel should be educated and trained on security ideally by the senior-level management.

#### Awareness
- Indoctrination and orientation: New employees and contractors should receive basic indoctrination and orientation. During the indoctrination, they may receive a copy of the corporate information security policy, be required to acknowledge and sign acceptable-use statements and non-disclosure agreements, and meet immediate supervisors and pertinent members of the security and IT staff.
- Presentations: Lectures, video presentations, and interactive computer-based training (CBTs) are excellent tools for disseminating security training and information. Employee bonuses and performance reviews are sometimes tied to participation in these types of security awareness programs.
- Printed materials: Security posters, corporate newsletters, and periodic bulletins are useful for disseminating basic information such as security tips and promoting awareness of security.

#### Training

- Classroom training: Instructor-led or other formally facilitated training, possibly at corporate headquarters or a company training facility
- Self-paced training: Usually web-based training where students can proceed at their own pace
- On-the-job training: May include one-on-one mentoring with a peer or immediate supervisor
- Technical or vendor training: Training on a specific product or technology provided by a third party
- Apprenticeship or qualification programs: Formal probationary status or qualification standards that must be satisfactorily completed within a specified time period

#### Education

- Continuing education requirements: Continuing Education Units (CEUs) are becoming popular for maintaining high-level technical or professional certifications such as the CISSP or Cisco Certified Internetworking Expert (CCIE)
- Certificate programs: Many colleges and universities offer adult education programs that have classes about current and relevant subjects for working professionals
- Formal education or degree requirements: Many companies offer tuition assistance or scholarships for employees enrolled in classes that are relevant to their profession

### National Initiative for Cybersecurity Education (NICE)
NICE has evolved from the Comprehensive National Cybersecurity Initiative, and extends its scope beyond the federal workplace to include civilians and students in kindergarten through post-graduate school. The goal of NICE is to establish an operational, sustainable and continually improving cybersecurity education program for the nation to use sound cyber practices that will enhance the nation’s security.
![](https://gitlab.dclabra.fi/wiki/uploads/upload_df0e9068ce96d5b918b3a11b008fb7b5.png)

The National Institute of Standards and Technology (NIST) is leading the NICE initiative, comprised of over 20 federal departments and agencies, to ensure coordination, cooperation, focus, public engagement, technology transfer and sustainability. Many NICE activities are already underway and NIST will highlight these activities, engage various stakeholder groups and create forums for sharing information and leveraging best practices. NIST will also be looking for “gaps” in the initiative -- areas of the overarching mission that are not addressed by ongoing activities.

NICE is a part of Comprehensive National Cybersecurity Initiative (CNCI) where government and industry collaborated to create a training & educational framework for cybersecurity workforce.
![](https://gitlab.dclabra.fi/wiki/uploads/upload_1640efb7432e7691d0cbdf91d4ce097a.png)