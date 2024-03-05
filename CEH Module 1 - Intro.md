# A1). Information Security Triangle or CIA Trait and Non-Repudiation
		- **Confidentiality**
		  >>Keeping Data Secure<<
		    -Confidentiality Ensures that Information is only accessible by right person i.e. only Authorized person can see the information. Protection from unauthorized access. Confidentiality is ensured by implementing Authentication Checks (User Name and Password), Captcha (Mitigate Brute-force and prevent from Bots), etc. Confidential info should be stored in private offline storage and keep in a safe place, or encrypt data if possible.
	            - Popular attacks affecting confidentiality : Data Breaches, Card Skimming, Keylogging, Phishing, Dumpster Diving, etc.
		- **Integrity**
		  >>Keeping Data Clean<<	  
	            -Integrity Ensures that Information can only tempered by Authorized by person or it should not be tempered by unauthorized person. Info. either in rest or transit should not be tempered. Integrity is ensured by Encryption, double-triple Encoding, Hashing, salted hashing, MAC (Message Authentication Code), or we can say with the help of Cryptography.
		    - Popular Attacks affecting Integrity : MITM, Packet sniffing, etc
		- **Availability**
		  >>Keeping Data Accessible<<
		    -Availability ensures that Info. is only available to the right person at the right time, i.e. whenever the info. is requested it should be available.
	            -Popular Attacks Affecting Availability : DOS, DDOS, etc.
		Note: In addition, other properties, such as authenticity, accountability, non-repudiation and reliability can also be involved.
 		-**Authenticity** Refers to the characterstic of a communication, document, or any data that ensures the quality of being geniune.
	        
	        -**Auditing & Accountability** Basically keep tracking of everthing, like, who's been logging in when are they loggin in whose access this data. 
                -**Non-Repudiation**Non-Repudiation ensures that Person A or Person B can't deny for action performed or happened on there side. For Example, suppose Person A send Money to Person B, so person B can't say money was never received. Like we have proof (Bank Statement, Account Balance Increment, Balance Deduction on Person A's side).
		
# A2). Different Hackers
	**Black Hat**- Hackers that seek to perform malicious activities.
	**Gray Hat** - Hackers that perform good or bad activities but do not have the permission of the organization they are hacking against.
	**White Hat/Ethical hackers**- They use their skills to improve security by exposing vulnerabilities before malicious hackers.
	**Script Kiddie / Skiddies**- Unskilled individual who uses malicious scripts or programs, such as a web shell, developed by others to attack computer systems and networks and deface websites.
	**State-Sponsored Hacker**- Hacker that is hired by a government or entity related.
	**Hacktivist**- Someone who hacks for a cause; political agenda.
	**Suicide Hackers** - Are hackers that are not afraid of going jail or facing any sort of punishment; hack to get the job done.
	**Cyberterrorist** - Motivated by religious or political beliefs to create fear or disruption.	

# A3). Types of Penetration Testing
		**White Box Testing** --> You will get the complete details about system from client like Network access, login ID-Password, etc.
		**Black Box Testing** --> You have to enumerate as much as possible by your own.
		**Grey Box Testing** --> You will get only little details like network access.

# A4). Teams in Penetration Testing**
		**Red Team** --> Perform like an Hacker and try to hack into Computer Systems, physical Security, Network Security, etc
		**Blue Team** --> Act as a Defender, and implement necessary security checks to ensure System Security. Also react on Red team's Actions/Attacks. Blue team also work as Incident Response team.

# A5). Few Terms used in Hacking
	**Vulnerability**- A system flaw, weakness on the system (on design, implementation etc).
	**Threat**- Exploits a vulnerability.
	**Exploit**- Exploits are a way of gaining access to a system through a security flaw and taking advantage of the flaw for their benefit.
	**Payload**- Component of an attack; is the part of the private user text which could also contain malware such as worms or viruses which performs the malicious action; deleting data, 		   sending spam or encrypting data.
	**Zero-day attack** - Attack that occurs before a vendor knows or is able to patch a flaw.
	**Daisy Chaining / Pivotting** - It involves gaining access to a network and /or computer and then using the same information to gain access to multiple networks and computers that contains desirable information.
	**Enterprise Information Security Architecture (EISA)** - determines the structure and behavior of organization's information systems through processes, requirements,principles and models.
	**Deep Web & Dark web:**
	  -Deep Web:- is the space where Spiders and Crawlers are not allowed. for example : Facebook.com/abc is accessible to spiders and crawlers but messages sent ABC to XYZ is only accessible or visible to ABC and XYZ. i.e. not visible through public search engines or not visible publicly.
	  -Dark Web:- Dark web is a part of internet which is only accessible through TOR (The Onion Routing) Browser. These sites have special Top level Domain (TLD) Names '.onion'. For Example: 46787sd6fasdf69756g79aas6df96asd.onion, abc.onion 
# A6). Information Security Threat Categories : (Optional)
		**Network Threats: Like**
			- ***MITM  - Man In The Middle*** - Hacker sit between client and Source
			- ***DOS - Denial of Service*** - Sending tons of junk packets to disturb server so that server was not able to respond authentic requests.
			- ***PASSWORD BASED ATTACKS*** - Default passwords, Brute Force, Dictionary ATTACKS
		**Host Threats: Like**
			- ***Unauthorized Access*** - Gaining Access without permission
			- ***Physical Security Threats*** - Open Access, Visible WiFi Routers
		**Operation Security Threats: Like**
			- ***Unpatched OS \ Insecure OS***
			- ***Zero Days***
# A7). Phases of Hacking or how to successfully hack into system
		- **Reconnaissance**
			Passive = Acquiring Info without interacting with Target Directly.
			Active = Gain Info by Acquiring the target Directly. (Via Calls, Emails, help Desk or Technical Department)
		- **Scanning**
			Scan IP's for Open Ports and Possible Vulnerabilities like Older version of OS, Running Services .
		- **Gaining Access**
			Attacker Gain Access by found Vulnerabilities in Scanning Phase (By Password Cracking, Insecure Authentication, Buffer Overflow, Etc)
		- **Maintaining Access**
			Maintain Access by Creating backdoor, installing Rootkit, Trojan, etc)
		- **Clearing Traces/Logs**
			Clear Footprints like connection established, Activities performed) Clear Date defining Hackers Identity