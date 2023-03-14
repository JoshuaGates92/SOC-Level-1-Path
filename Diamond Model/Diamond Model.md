**The Diamond Model of Intrusion Analysis** was developed by cybersecurity professionals - Sergio Caltagirone, Andrew Pendergast, and Christopher Betz in 2013.

Four core features:
1. Adversary
2. Infrastructure
3. Capability
4. Victim

This model also includes social, political and technology components

## Adversary

An actor or organization responsible for utilizing a capability against the victim to achieve their intent.

==**Adversary Operator**==  is the “hacker” or person(s) conducting the intrusion activity.

==**Adversary Customer**==  is the entity that stands to benefit from the activity conducted in the intrusion. It may be the same person who stands behind the adversary operator, or it may be a separate person or group.

## Victim

Target of the adversary

==**Victim Personae**== are the people and organizations being targeted and whose assets are being attacked and exploited. These can be organization names, people’s names, industries, job roles, interests, etc.

==**Victim Assets**== are the attack surface and include the set of systems, networks, email addresses, hosts, IP addresses, social networking accounts, etc., to which the adversary will direct their capabilities.

## Capability

The capability highlights the adversary’s tactics, techniques, and procedures (TTPs).

==**Capability Capacity**== is all of the vulnerabilities and exposures that the individual capability can use. 

  

An ==**Adversary Arsenal**== is a set of capabilities that belong to an adversary. The combined capacities of an adversary's capabilities make it the adversary's arsenal.


## Infrastructure

**Infrastructure** – is also known as software or hardware. Infrastructure is the physical or logical interconnections that the adversary uses to deliver a capability or maintain control of capabilities. For example, a command and control centre (C2) and the results from the victim (data exfiltration). 

The infrastructure can also be IP addresses, domain names, email addresses, or even a malicious USB device found in the street that is being plugged into a workstation. 

==**Type 1 Infrastructure**== is the infrastructure controlled or owned by the adversary. 

==**Type 2 Infrastructure**== is the infrastructure controlled by an intermediary. Sometimes the intermediary might or might not be aware of it. This is the infrastructure that a victim will see as the adversary. Type 2 Infrastructure has the purpose of obfuscating the source and attribution of the activity. Type 2 Infrastructure includes malware staging servers, malicious domain names, compromised email accounts, etc.

## Event Meta Features

Meta-features are not required, but they can add some valuable information or intelligence to the Diamond Model.

## Social-Political Component

The **social-political** component describes the needs and intent of the adversary, for example, financial gain, gaining acceptance in the hacker community, hacktivism, or espionage.

## Technology

**Technology** – the technology meta-feature or component highlights the relationship between the core features: capability and infrastructure. The capability and infrastructure describe how the adversary operates and communicates. A scenario can be a watering-hole attack which is a methodology where the adversary compromises legitimate websites that they believe their targeted victims will visit.

