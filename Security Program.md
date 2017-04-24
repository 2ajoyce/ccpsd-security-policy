# CCPSD Security Policy

## Purpose
This policy outlines district wide security measures with the goal of (1) ensuring the confidential information held by the District in an electronic format is not exposed to unauthorized disclosure; (2) protecting the District's network and resources from attack while ensuring continuous high quality service to business processes in day to day use.

## Applicability and Enforcement
Compliance with applicable CCPSD security policy is mandatory for all CCPSD employees and program participants. Failure to comply will result in disciplinary action determined by the appropriate authority. Disciplinary action may include but is not limited to; forfeiture of the privilege to use technology resources, disciplinary action, and/or legal action

## Created and Maintained By
This security policy has is established and maintained by the school board. The CEO is granted additional powers in these proceedings for the purposes of breaking stalemates and quickly reacting to dynamic and urgent situations.

## Policies
* Access Control
* Business Continuity Plan
* Configuration Management
* Data Integrity Assurance
* Data Security Categorization
* Disaster Recovery Plan 
* Identification and Authentication
* Incident Response
* Monitoring
* Network Security
* Operational Security
* Personnel Training
* Security Awareness & Training
* Security Model
* System and Services Acquisition
* Wired Management
* Wireless Management

## Access Control
System and application access wil be granted by the Information Security Officer (ISO) in charge of the school based on user roles. The ISO will follow a least access policy that allows users the minumum of required access in order to perform their duties.
* Authentication - All users will be assigned a SSID upon entering the CCPSD system. Users will be required to set a password complient with standard(NUMBER NOT DEFINED YET)(lists password requirements and duration length).
* Authorization - Users are authorized to log in at any CCPSD network. Access to specific network resources or programs is limited to the school and authorized by the ISO in charge of that school. Procedure (BLANK) details the specifics on how to request access to a resource.

## Business Continuity Plan


## Configuration Management
### System Configuration
All systems on the CCPSD network must meet the guidelines specified in the appropriate section of this list.
#### School owned faculty accessible systems
These systems must meet the guidelines in Specification Document(Not Included)
**Sample Guidelines**
* Disable booting from devices other than the hard drive.
* BIOS is password protected.
* OS is kept patched and updated with centralized patching.
* Services from (this) whitelist only unless otherwise approved.
* Mandatory antivirus program installed and scheduled to run and update.
* Mandatory system firewall enabled with the rules from (this) list.
* Must connect to the internet through the network firewall.
* Only faculty accounts are allowed to log in.

#### School owned student accessible systems
These systems must meet the guidelines in Specification Document(Not Included)
**Sample Guidelines**
* Disable booting from devices other than the hard drive.
* BIOS is password protected.
* OS is kept patched and updated with centralized patching.
* Services from (this) whitelist only unless otherwise approved.
* Mandatory antivirus program installed and scheduled to run and update.
* Mandatory system firewall enabled with the rules from (this) list.
* Must connect to the internet through the network firewall.
* System is rebuilt at least once a week to reset the machine.

#### Privately owned systems
These systems are not required to meet any guidelines and as such they should only be connected to the network through wifi to enable client isolation.

#### School owned web servers
These systems must meet the guidelines in Specification Document(Not Included)
**Sample Guidelines**
* OS is kept patched and updated with centralized patching.
* Services from (this) whitelist only unless otherwise approved.
* Mandatory antivirus program installed and scheduled to run and update.
* Mandatory system firewall enabled with the rules from (this) list.
* Only designated accounts specified by the ISO can log into this machine.

#### School owned database servers
These systems must meet the guidelines in Specification Document(Not Included)
**Sample Guidelines**
* OS is kept patched and updated with centralized patching.
* Services from (this) whitelist only unless otherwise approved.
* Antivirus is not included on this system as it is never exposed to the internet.
* Mandatory system firewall enabled with the rules from (this) list.
* Must connect to the internet through the network firewall.
* Only designated accounts specified by the ISO can log into this machine.

#### School owned application servers
These systems must meet the guidelines in Specification Document(Not Included)
**Sample Guidelines**
* OS is kept patched and updated with centralized patching.
* Services from (this) whitelist only unless otherwise approved.
* Mandatory antivirus program installed and scheduled to run and update.
* Mandatory system firewall enabled with the rules from (this) list.
* Must connect to the internet through the network firewall.
* Only designated accounts specified by the ISO can log into this machine.

## Data Integrity Assurance
Each school will maintain a single main data center supplemented by data closets located around the school. The data center can be supplemented by additional data centers if necessary. This addition will be based on the size of the school in question and should be brought up with the CIO of the school district prior to construction. Any additional data centers will be subject to the same restrictions as the original data center. Data center construction requirements can be found in Specification Document(NOT ADDED). Data closet requirements can be found in Specification Document(Not Added).

### Non-Inclusive Specification Document Previews For Homework Purposes
#### Data Centers
The following guidelines must be met to the satisfaction of the school districts CIO:
* The data center must be centrally located in a room with solid walls and no windows.
* The walls, ceiling, and floor must be constructed of enough material to block sound and ensure  security. Cinderblock would be ideal but thicker than average stick construction can also work. 
* The room must have no openings or entrances that do not classify as either a solid door that can remain locked, a cable route that runs into a wall or other enclosed space, a vent for climate control that runs through an enclosed space, or a drain.
* The room must have a battery backup capable of running all critical services for a minimum of 30 minutes.
* The room must have a generator backup capable of running all critical services for a minimum of 8 hours.
* The room must have video surveillance with footage stored in real time at a location not inside the data center.
* The room must have a locking mechanism on the door that prevents access by unauthorized personel.
* The room must be autommatically and continiously monitored for flooding, smoke, and carbon monoxide. 
* The room must have drainage sufficent to drain 10 times the volume of water the enters the room in pipes.
* The room must have automated humidity controls.
* All alarms in the room must make enough noise to be clearly heard anywhere inside of the room as well as sending out alerts over the network through preconfigured channels. These alarms will be automatically tested monthly.

#### Data Closets
* The data closet must be located in a room with solid walls and no windows.
* The walls, ceiling, and floor must be constructed of enough material to block sound and ensure  security. Cinderblock would be ideal but thicker than average stick construction can also work. 
* The room must have no openings or entrances that do not classify as either a solid door that can remain locked, a cable route that runs into a wall or other enclosed space, a vent for climate control that runs through an enclosed space, or a drain.
* The room must have a battery backup capable of running all critical services for a minimum of 30 minutes.
* The room must have video surveillance with footage stored in real time at a location not inside the data closet.
* The room must have a locking mechanism on the door that prevents access by unauthorized personel.
* The room must be autommatically and continiously monitored for flooding, smoke, and carbon monoxide. 
* All alarms in the room must make enough noise to be clearly heard anywhere inside of the room as well as sending out alerts over the network through preconfigured channels. These alarms will be automatically tested monthly.


## Data Security Categorization
The following categories are tiered so that every category is a subset of the following categories. 
For example, Personally Identifiable Information is also restricted by the guidelines set in Confidential Information, Internal Information, and Public Information. 
Likewise, Confidential Information is restricted by it's own guidelines, as well as the guidelines of Internal Information and Public Information. Confidential Information is not subject to the guidelines of PII.

1. Personally Identifiable Information (PII)
	* PII information includes any information that could be used to distinguish or trace an individuals identity. The following list is non-inclusive.
		* Name
		* SSN
		* Date and location of birth
		* Bio-metric records
	* Disclosure of PII must meet all guidelines of applicable laws. 
2. Confidential Information
	* Confidential Information is important or highly sensitive material. Generally confidential information is not linked to an individual.  The following list is non-inclusive
		* System Access Passwords
		* Encryption Keys
		* Sponsor Information
		* Financial Information
	* Access to confidential information has to be cleared by the information owner through Procedure (NumberNotDecided)
3. Internal Information
	* Internal Information is intended for unrestricted use inside of the the CCPSD system. In certain situations internal information may be shared with affiliated organizations as appropriate. Internal information requires no permission for distribution within the CCPSD system. The following list is non-inclusive.
		* Personnel Directories
		* Internal Policies
		* System Wide Communications
	* Any information not explicitly classified as PII, Confidential, or Public will be classified as Internal information by default.
4. Public Information
    * Public information may be disclosed outside of the CCPSD system.
    * Public information must be cleared for release by a designated authority.
    * Each school in the CCPSD system will have at least one designated authority to clear information as public.

## Disaster Recovery Plan
### Plan
### Process
### Utilities
### Secure Recovery
### High Availablility & Fault Tolerance
### Computer Incident Response Team
### Computer Emergency Reponse Team
### Testing

## Monitoring
Automated logging occurs on every CCPSD owned system. All logs are sent to a central location inside the main data closet. The main data log storage is mirrored to a secure off site location in real time. The off site mirroring is non reversable and read only from within the network being monitored. Continuity between the on and off site log storage will be monitored automatically and discrepancies will be reported to the ISO. Details on how to set up the automated logging on each type of device can be found in Procedure(Not Included).

## Network Security
### Switch configuration
All switches deployed will be managed switches. They will run four VLAN's. Vlan 1 will be for the wireless. Vlan 2 will be for the wired school owned faculty accessible systems. Vlan 3 will be for the wired school owned student accessible systems. Vlan 4 will be used for switch and other device managment. Access to Vlan 4 is highly restricted.
### Wireless Design
All wireless is accessible with a CCPSD SSID and password. All wireless is client isolated and considered unsecure. Wireless access points are to be replaced and configured using Specification Document(Not Added).
### Firewall
One non-application layer firewall is deployed at the border of the network. This firewall is to be replaced and configured using Specification Document(Not Added). 
### Phone
All phone access is handled over VOIP. These phones and systems should be configured using Specification Document(Not Added).
### Tunneling
Some information may need to be accessible outside of the school. This exterior access is to be handled through secure tunnelling configured though the systems and using the standards outlined in Specification Document(Not Added).

## Operational Security
Host Security
* All computers will be tethered to the desk they rest on.
* All staff computers will reside in offices which are to be locked when not in use.
* All computers available for public use will be configured according to procedure(BLANK).
* All computers available for student use will be configured according to procedure(BLANK).
* All computers available for faculty use will be configured according to procedure(BLANK).
* Additional resources(software, ect) can be requested on a machine using procedure(BLANK).

Network Security
* All staff computers must connect to a secure network.
* Schools must provide private wireless access to its students and staff throughout the building. This network is not considered secure.
* Complete client isolation will be implimented on unsecure networks. Network resources will be exempt from this rule so they are available to all clients.
* Schools must provide wired ethernet ports in every staff office equal to the number of staff in that office. These will must be secure.
* Schools will configure their networks following procedure(BLANK).
* Schools will employ a firewall meeting criteria (BLANK) at the entrance to their network. This defense need not be diversified. The cost of diversification would be wasted on a network that is open in so many other areas.

## Security Awareness & Training
CCPSD, lead by the Information Security Officer (ISO) will ensure that:
* all students are reminded of cyber security principals in the beginning of any class where 80% of classtime is spent in a computer lab.
* all parents are annually reminded of cyber security principals.
* all staff not associated with IT attend an appropriate security training workshop at least once every two years.
* all staff associated with IT attend an appropriate security training workshop at least once every year.
* all staff responsible for storing (or maintaining services that store) Confidential or Personally Identifiable Information attend an appropriate security training workshop at least once every year. These individuals will also be responsible for keeping any required certifications up to date.

## Security Model
CCPSD uses the Clark-Wilson Security model. This model uses security classifications which are set up by the schools ISO based on job title. Special circumstances and access can be handled through procedure (BLANK). Different classifications have different network resource access permissions and access to different levels of data (PII, ect). Users must use correct procedures to modify data as in most cases direct interaction will not be permitted.

