# <u>Introduction</u>

## <u> Fundamental Security Concepts </u>
The whole principle is to avoid **Theft, Tampering and Disruption** of the systems through **CIA Triad** (Confidentiality, Integrity and Availability).

<p align="center">
<img width="50%" src="https://i.ytimg.com/vi/AJTJN4wDBM8/hqdefault.jpg">
</p>

- **Confidentiality**
Keeping systems and data from being accessed, seen, read to anyone who is not authorized to do so.
Information is accessible only to the autorized personnel.

## Confidentiality
- Confidentiality protects information from unauthorized disclosure.

#### Confidentiality_Concerns
1. Snooping
	- snooping gathering information that is left out in the open.
	- "Clean desk policies" protect against snooping.
2. Dumpster Diving
	- Dumpster diving is to dump data anywere or dustbin.
	- "Shedding" protects against dumpster diving.
3. Eavesdropping
	- listing sensitive information
	- "Rules about sensitive conversations" prevent eavesdropping
4. Wiretapping
	- Electronic evaesdropping - listing through wire(internet)
	- "Encryption" protects against Wiretapping
5. Social Engineering
	- The attacker uses psychological tricks to persuade an employee to give then sensitive information or access to internal systems.
	- Best defence is to "Educating users"



- **Integrity**
TRUSTWORTHINESS OF DATA OR RESOUCES: Protect the data from modification or deletion by unauthorized parties, and ensuring that when authorized people make changes that shouldn't have been made the damage can be undone.

## Integrity
- Integrity protects information from unauthorized changes.
#### Integrity_Concerns
1. Unauthorized modification
	- Attacks make changes without permission.
	- "Least priviege" protects against integrity attacks
2. Impersonation
	- Attacks pretend to be someone else
	- "User education" protects against attacks
3. Man-in-the-middle (MITM)
	- Attacks place the attacker in the middle of a communications session.
	- "Encryption" protects against MITM attacks
4. Replay
	- Attacks eavesdrop on logins and reuse the captured credentials.
	- "Encryption" protects against Replay attacks




- **Availability**
ACCESSIBLE WHEN REQUIRED BY AUTHORIZED USERS: Systems, access channels, and authentication mechanisms must all be working properly for the information they provide and protect to be available when needed.

## Availability
- Availability protects authorized access to systems and data.
#### Availability_Concerns
1. Denial of service (DoS)
	- Unlimited request to a server
	- "Block unauthorized connections" to protect against denial of service attacks.
2. Power outages
	- Naturally or Man-made
	- "Redundant power and generators" protect against power outages.
3. Hardware failures
	- any component failures
	- "Redundant components" protect against hardware failure
4. Destruction
	- Naturally or Man-made
	- "Backup data centers" protect against destruction.
5. Service outages
	- Programing error and the failure of underlying equipment.
	- building systems that are resilient in the face of errors and hardware failures.


- **Authenticity**
Refers to the characterstic of a communication, document, or any data that ensures the quality of being geniune.
	
**Note:** *In addition, other properties, such as authenticity, accountability, non-repudiation and reliability can also be involved. (ISO/IEC 27000:2009)*

- **Auditing & Accountability**
Basically keep tracking of everthing, like, who's been logging in when are they loggin in whose access this data.

- **Non-Repudiation**
Non-repudiation is the assurance that someone cannot deny the validity of something. Non-repudiation is a legal concept that is widely used in information security and refers to a service, which provides proof of the origin of data and the integrity of the data.

### **Security, Functionality and Usability balance**

There is an inter dependency between these three attributes. When **security goes up, usability and functionality come down**. Any organization should balance between these three qualities to arrive at a balanced information system.
