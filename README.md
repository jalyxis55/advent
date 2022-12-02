# THM XMas Advent

## Day 1: The Story

### Security Frameworks
**Security Frameworks:** documented processes that define policies and procedures organizations should follow to establish and manage security controls. 

### NIST Cybersecurity Framework
The **Cybersecurity Framework (CSP)** was developed by the *National Institute of Standards and Technology (NIST)*, and it provides guidance for organizations to manage and reduce cybersecurity risk. 

`5 Essential Functions: 
1. Identify
2. Protect
3. Detect
4. Respond
5. Recover`

### ISO 27000 Series
The **International Organization of Standardization (ISO)** develops a series of frameworks for different industries and sectors.
- ISO 27001 and 27002 outline the requirements and procedures for creating, implementing and managing an information security management system (ISMS).

### MITRE ATT&CK Framework
The **MITRE ATT&CK** framework is a knowledge base of tactics, techniques, and procedures (TTPs), curated and detailed to ensure security teams can identify attack patterns. Similar structure to a periodic table, mapping techniques against phases of the attack chain and referencing system platforms exploited.

### Cyber Kill Chain
The **Cyber Kill Chain** describes the stages commonly followed by cyber attacks and security defenders. Seven stages: 
1. Recon
2. Weaponization
3. Delivery
4. Exploitation
5. Installation
6. Command & Control
7. Actions on Objectives

### Unified Kill Chain
The **Unified Kill Chain** is a unification of the MITRE ATT&CK and Cyber Kill Chain frameworks. Provides a model to defend against cyber attacks from the adversary's perspective. Describes 18 phases of attack based on TTPs

### CYCLE: In
1. *Reconnaissance:* The attacker performs research on the target using publicly available information
2. *Weaponization:* Setting up the needed infrastructure to host the command and control center (C2) is crucial in executing attacks
3. *Delivery:* Payloads are malicious instruments delivered to the target through numerous means, such as email phishing and supply chain attacks
4. *Social Engineering:* The attacker will trick their target into performing untrusted and unsafe action against the payload they just delivered, often making their message appear to come from a trusted in-house source
5. *Exploitation:* If the attacker finds an existing vulnerability, a software or hardware weakness, in the network assets, they may use this to trigger their payload
6. *Persistence:* The attacker will leave behind a fallback presence on the network or asset to make sure they have a point of access to their target
7. *Defense Evasion:* The attacker must remain anonymous throughout their exploits by disabling and avoiding any security defense mechanisms enabled, including deleting evidence of their presence
8. *Command & Control:* (Prepared infrastructure) A communication channel between the compromised system and the attacker's infrastructure is established across the internet

### CYCLE 2: Through
9. *Pivoting:* (Persistence system) This system will become the attack launchpad for other systems in the network
10. *Discovery:* The attacker will seek to gather as much information about the compromised system, such as available users and data. Alternatively, they may remotely discover vulnerabilities and assets within the network. This opens the way for the next phase.
11. *Privilege Escalation:* Restricted access prevents the attacker from executing their mission. Therefore, they will seek higher privileges on the compromised systems by exploiting identified vulnerabilities or misconfiguraitons
12. *Execution:* With elevated privileges, malicious code may be downloaded and executed to extract sensitive information or cause further havoc on the system
13. *Credential Access:* Part of the extracted sensitive information would include login credentials stored in the hard disk memory. This provides the attacker with more firepower for their attacks.
14. *Lateral Movement:* Using the extracted credentials, the attacker may move around different systems or data storages within the network

### CYCLE 3: Out
15. *Collection:* After finding the jackpot of data and information, the attacker will seek to aggregate all they need. By doing so, the assets' confidentiality would be compromised entirely, especially when dealing with trade secrets and financial or personally identifiable information (PII) that is to be secured
16. *Exfiltration:* The attacker must get their loot out of the network. Various techniques may be used to ensure they have achieved their objectives without triggering suspicion
17. *Impact:* When compromising the availability or integrity of an asset or information, the attacker will use all the acquired privileges to manipulate, interrupt, and sabotage. They will have to recover, reputation, financial, and social damage
18. *Objectives:* Attackers may have other goals to achieve that may affect the social or technical landscape that their targets operate within. Defining and understanding these objectives tend to help security teams familiarize themselves with adversarial attack tools and conduct risk assessments to defend their assets. 
