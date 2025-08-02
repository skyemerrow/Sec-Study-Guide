# CompTIA Security+ (SY0-701) Exam Objectives

## About the Exam

The CompTIA Security+ certification exam (SY0-701) validates that a successful candidate has the knowledge and skills to:
* Assess the security posture of an enterprise environment and recommend appropriate security solutions
* Monitor and secure hybrid environments, including cloud, mobile, and IoT
* Operate with an awareness of applicable regulations and policies, including governance, risk, and compliance principles
* Identify, analyze, and respond to security events and incidents

## Test Details

* **Exam Number**: SY0-701
* **Number of Questions**: Maximum of 90
* **Question Types**: Multiple-choice and performance-based
* **Length of Test**: 90 minutes
* **Recommended Experience**: A minimum of 2 years of experience in IT administration with a focus on security, hands-on experience with technical information security, and broad knowledge of security concepts.

## Exam Objectives (Domains)

The exam is divided into the following domains and their corresponding weight on the test:

| Domain | Percentage of Examination |
| :--- | :--- |
| 1.0 General Security Concepts | 12% |
| 2.0 Threats, Vulnerabilities, and Mitigations | 22% |
| 3.0 Security Architecture | 18% |
| 4.0 Security Operations | 28% |
| 5.0 Security Program Management and Oversight | 20% |
| **Total** | **100%** |

### 1.0 General Security Concepts
* **1.1 Compare and contrast various types of security controls.**
    * **Categories**: Technical, Managerial, Operational, Physical.
    * **Control types**: Preventive, Deterrent, Detective, Corrective, Compensating, Directive
* **1.2 Summarize fundamental security concepts.**
    * Confidentiality, Integrity, and Availability (CIA)
    * Non-repudiation
    * Authentication, Authorization, and Accounting (AAA)
    * Zero Trust
    * Physical security, including bollards, fencing, and security guards
    * Deception and disruption technology, such as honeypots and honeynets
* **1.3 Explain the importance of change management processes and the impact to security.**
    * **Business processes**: Approval process, stakeholders, impact analysis, backout plan
    * **Technical implications**: Allow lists/deny lists, downtime, legacy applications, documentation
    * Version control
* **1.4 Explain the importance of using appropriate cryptographic solutions.**
    * Public key infrastructure (PKI)
    * Encryption levels: Full-disk, partition, file, volume
    * Asymmetric and Symmetric encryption
    * Hashing, including salting and key stretching
    * Digital signatures
    * Certificates and Certificate authorities (CAs)

### 2.0 Threats, Vulnerabilities, and Mitigations
* **2.1 Compare and contrast common threat actors and motivations.**
    * **Threat actors**: Nation-state, Hacktivist, Insider threat, Organized crime
    * **Attributes of actors**: Internal/external, resources, level of sophistication
    * **Motivations**: Data exfiltration, financial gain, revenge, war, espionage
* **2.2 Explain common threat vectors and attack surfaces.**
    * **Message-based**: Email, SMS, Instant messaging
    * **File-based** and **Voice call** vectors
    * **Vulnerable software**: Unsupported systems and applications
    * **Supply chain**: Managed service providers (MSPs), vendors, suppliers
    * **Human vectors/social engineering**: Phishing, Vishing, Impersonation, Business email compromise
* **2.3 Explain various types of vulnerabilities.**
    * **Application**: Memory injection, Buffer overflow, Race conditions, Malicious updates
    * **Web-based**: SQL injection (SQLI), Cross-site scripting (XSS)
    * **Hardware**: Firmware, End-of-life, Legacy systems
    * **Virtualization**: VM escape, Resource reuse
    * **Cloud-specific**: Supply chain, Service provider, Hardware provider
    * **Mobile device**: Side loading, Jailbreaking
    * Zero-day vulnerabilities
* **2.4 Given a scenario, analyze indicators of malicious activity.**
    * **Malware attacks**: Ransomware, Trojan, Worm, Spyware, Virus, Rootkit
    * **Physical attacks**: Brute force, RFID cloning
    * **Network attacks**: Distributed denial-of-service (DDoS), DNS attacks, On-path attacks
    * **Password attacks**: Spraying, Brute force
    * **Indicators**: Account lockout, Impossible travel, Missing logs, Out-of-cycle logging
* **2.5 Explain the purpose of mitigation techniques used to secure the enterprise.**
    * Segmentation, Access control, Application allow list, Isolation
    * Patching, Encryption, Monitoring, Least privilege
    * Hardening techniques: Installation of endpoint protection, Host-based firewall, Disabling ports/protocols, Default password changes

### 3.0 Security Architecture
* **3.1 Compare and contrast security implications of different architecture models.**
    * **Architecture and infrastructure concepts**: Cloud, On-premises, Containerization, Serverless
    * **Network infrastructure**: Physical isolation (air-gapped), Logical segmentation
    * **loT, Industrial control systems (ICS)/SCADA, Embedded systems**
* **3.2 Given a scenario, apply security principles to secure enterprise infrastructure.**
    * **Infrastructure considerations**: Device placement, Security zones, Attack surface, Failure modes
    * **Firewall types**: Web application firewall (WAF), Unified threat management (UTM), Next-generation firewall (NGFW)
    * **Network appliances**: Jump server, Proxy server, Intrusion prevention system (IPS)/intrusion detection system (IDS)
    * **Secure communication/access**: Virtual private network (VPN), Transport Layer Security (TLS), Internet protocol security (IPSec)
* **3.3 Compare and contrast concepts and strategies to protect data.**
    * **Data types**: Regulated, Trade secret, Intellectual property, Financial information
    * **Data classifications**: Sensitive, Confidential, Public, Restricted, Private
    * **Data states**: Data at rest, Data in transit, Data in use
    * **Methods to secure data**: Geographic restrictions, Encryption, Hashing, Tokenization, Segmentation, Permission restrictions
* **3.4 Explain the importance of resilience and recovery in security architecture.**
    * **High availability**: Load balancing vs. clustering, Fail over
    * **Site considerations**: Hot, Cold, Warm sites
    * **Backups**: Geographic dispersion, Onsite/offsite, Frequency
    * **Continuity of operations**: Capacity planning, people, technology, infrastructure
    * **Power**: Generators, Uninterruptible power supply (UPS)

### 4.0 Security Operations
* **4.1 Given a scenario, apply common security techniques to computing resources.**
    * **Secure baselines**: Establish, Deploy, Maintain
    * **Hardening targets**: Mobile devices, Workstations, Servers, Cloud infrastructure, IoT devices
    * **Wireless security**: Wi-Fi Protected Access 3 (WPA3), AAA/RADIUS, Cryptographic protocols
    * **Application security**: Input validation, Secure cookies, Static code analysis, Sandboxing
* **4.2 Explain the security implications of proper hardware, software, and data asset management.**
    * **Acquisition/procurement** and **Assignment/accounting**
    * **Monitoring/asset tracking** and **Disposal/decommissioning**
    * **Sanitization** and **Destruction**
    * **Data retention**
* **4.3 Explain various activities associated with vulnerability management.**
    * **Identification methods**: Vulnerability scan, Penetration testing, Bug bounty program
    * **Analysis**: Confirmation (False positive/negative), Prioritization (CVSS/CVE)
    * **Response and remediation**: Patching, Insurance, Compensating controls, Exceptions
    * **Validation**: Rescanning, Audit, Verification
* **4.4 Explain security alerting and monitoring concepts and tools.**
    * **Monitoring computing resources**: Systems, Applications, Infrastructure
    * **Activities**: Log aggregation, Alerting, Reporting, Archiving
    * **Tools**: Security information and event management (SIEM), Antivirus, Data loss prevention (DLP), NetFlow
* **4.5 Given a scenario, modify enterprise capabilities to enhance security.**
    * **Firewall**: Rules, Access lists, Screened subnets
    * **IDS/IPS**: Trends, Signatures
    * **Web filter**: URL scanning, Content categorization
    * **Email security**: DMARC, DKIM, SPF
    * **Network access control (NAC)**, **Endpoint detection and response (EDR)**
* **4.6 Given a scenario, implement and maintain identity and access management.**
    * **Provisioning/de-provisioning user accounts**
    * **Federation** and **Single sign-on (SSO)**
    * **Access controls**: Mandatory, Discretionary, Role-based, Rule-based, Attribute-based
    * **Multifactor authentication**: Implementations (biometrics, security keys), Factors (something you know, have, are, somewhere you are)
    * **Password concepts**: Best practices (length, complexity, age), Password managers, Passwordless
* **4.7 Explain the importance of automation and orchestration related to secure operations.**
    * **Use cases**: User/Resource provisioning, Ticket creation, Escalation, Continuous integration and testing
    * **Benefits**: Efficiency, Enforcing baselines, Scaling securely, Employee retention
    * **Other considerations**: Complexity, Cost, Single point of failure
* **4.8 Explain appropriate incident response activities.**
    * **Process**: Preparation, Detection, Analysis, Containment, Eradication, Recovery, Lessons learned
    * **Training and Testing**: Tabletop exercise, Simulation
    * **Digital forensics**: Legal hold, Chain of custody, Acquisition, Preservation
* **4.9 Given a scenario, use data sources to support an investigation.**
    * **Log data**: Firewall logs, Application logs, Endpoint logs, OS-specific security logs
    * **Data sources**: Vulnerability scans, Automated reports, Packet captures

### 5.0 Security Program Management and Oversight
* **5.1 Summarize elements of effective security governance.**
    * **Guidelines, Policies, Standards, Procedures**
    * **External considerations**: Regulatory, Legal, Industry, Global
    * **Types of governance structures**: Boards, Committees, Government entities
    * **Roles and responsibilities**: Owners, Controllers, Processors, Custodians
* **5.2 Explain elements of the risk management process.**
    * **Risk identification** and **Risk assessment**
    * **Risk analysis**: Qualitative, Quantitative, Single loss expectancy (SLE), Annualized loss expectancy (ALE)
    * **Risk register**: Key risk indicators, Risk owners, Risk threshold
    * **Risk management strategies**: Transfer, Accept, Avoid, Mitigate
    * **Business impact analysis**: Recovery time objective (RTO), Recovery point objective (RPO)
* **5.3 Explain the processes associated with third-party risk assessment and management.**
    * **Vendor assessment**: Penetration testing, Right-to-audit clause, Supply chain analysis
    * **Vendor selection**: Due diligence, Conflict of interest
    * **Agreement types**: Service-level agreement (SLA), Non-disclosure agreement (NDA), Business partners agreement (BPA)
* **5.4 Summarize elements of effective security compliance.**
    * **Compliance reporting**: Internal, External
    * **Consequences of non-compliance**: Fines, Sanctions, Reputational damage, Loss of license
    * **Compliance monitoring**: Due diligence/care, Attestation
    * **Privacy**: Legal implications, Data subject, Right to be forgotten
* **5.5 Explain types and purposes of audits and assessments.**
    * **Attestation** and **Internal/External audits**
    * **Penetration testing**: Physical, Offensive, Defensive, Integrated
    * **Known, Partially known, Unknown environments**
    * **Reconnaissance**: Passive and Active
* **5.6 Given a scenario, implement security awareness practices.**
    * **Phishing**: Campaigns, Recognizing an attempt, Responding to reported messages
    * **Anomalous behavior recognition**: Risky, Unexpected, Unintentional
    * **User guidance and training**: Policy/handbooks, Situational awareness, Insider threat, Password management, Social engineering
    * **Reporting and monitoring**: Initial and Recurring training

