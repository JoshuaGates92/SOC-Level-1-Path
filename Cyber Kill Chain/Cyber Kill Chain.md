## Intro
![[kill chain overview.png]]

Thanks to Lockheed Martin, a global security and aerospace company, that established the Cyber Kill Chain® framework for the cybersecurity industry in 2011 based on the military concept.

## 1. Reconnaissance
Recon is the ==discovery and collection== of information on a system and victim (aka the planning phase).

Open-Source Intelligence (OSINT) is the first step attackers take. Collecting publicly available information is the foundation of establishing an effective attack vector.

==**Email harvesting**== is the process of obtaining email addresses from public, paid, or free services. An attacker can use email-address harvesting for a phishing attack (a type of social-engineering attack used to steal sensitive data, including login credentials and credit card numbers). The attacker will have a big arsenal of tools available for reconnaissance purposes. Here are some of them:

-   [theHarvester](https://github.com/laramies/theHarvester) - other than gathering emails, this tool is also capable of gathering names, subdomains, IPs, and URLs using multiple public data sources 
-   [Hunter.io](https://hunter.io/) - this is  an email hunting tool that will let you obtain contact information associated with the domain
-   [OSINT Framework](https://osintframework.com/) - OSINT Framework provides the collection of OSINT tools based on various categories  
    

An attacker would also use social media websites such as LinkedIn, Facebook, Twitter, and Instagram to collect information on a specific victim he would want to attack or the company. The information found on social media can be beneficial for an attacker to conduct a phishing attack.

## 2. Weaponisation

==**Malware**== is a program or software that is designed to damage, disrupt, or gain unauthorized access to a computer.

An ==**exploit** == is a program or a code that takes advantage of the vulnerability or flaw in the application or system.

A ==**payload**== is a malicious code that the attacker runs on the system.

## 3. Delivery

-   ==Phishing email==: after conducting the reconnaissance and determining the targets for the attack, the malicious actor would craft a malicious email that would target either a specific person (spearphishing attack) or multiple people in the company. The email would contain a payload or malware. For example, "Megatron" would learn that Nancy from the Sales department at company A would constantly like the posts on LinkedIn from Scott, a Service Delivery Manager at company B. He would give it a second guess that they both communicate with each other over work emails. "Megatron" would craft an email using Scott's First Name and Last Name, making the domain look similar to the company Scott is working at. An attacker would then send a fake "Invoice" email to Nancy, which contains the payload.

-   Distributing infected USB drives in public places like coffee shops, parking lots, or on the street. An attacker might decide to conduct a sophisticated USB Drop Attack by printing the company's logo on the USB drives and mailing them to the company while pretending to be a customer sending the USB devices as a gift. You can read about one of these similar attacks at [CSO Online "Cybercriminal group mails malicious USB dongles to targeted companies."](https://www.csoonline.com/article/3534693/cybercriminal-group-mails-malicious-usb-dongles-to-targeted-companies.html)

-   ==Watering hole attack==. A watering hole attack is a targeted attack designed to aim at a specific group of people by compromising the website they are usually visiting and then redirecting them to the malicious website of an attacker's choice. The attacker would look for a known vulnerability for the website and try to exploit it. The attacker would encourage the victims to visit the website by sending "harmless" emails pointing out the malicious URL to make the attack work more efficiently. After visiting the website, the victim would unintentionally download malware or a malicious application to their computer. This type of attack is called a drive-by download. An example can be a malicious pop-up asking to download a fake Browser extension.

## 4. Exploitation
Triggering of malware to gain access to a system through malicious intent

## 5. Installation
Often used through backdoor methods, bypassing security measures and undetected (at least initially).
==Persistent backdoor== can be made which just allows the attacker access into a previously compromised system.

==Timestomping== is the modification of time stamp data including modify, access, create and change times.

## 6. Command and Control

Most common channels of approach here:
-   The protocols HTTP on port 80 and HTTPS on port 443 - this type of beaconing blends the malicious traffic with the legitimate traffic and can help the attacker evade firewalls.    
    
-   DNS (Domain Name Server). The infected machine makes constant DNS requests to the DNS server that belongs to an attacker, this type of C2 communication is also known as DNS Tunneling.

## 7. Actions on Objectives (Exfiltration)

Once you have control of a system, the fun begins:
-   Collect the credentials from users.
-   Perform privilege escalation (gaining elevated access like domain administrator access from a workstation by exploiting the misconfiguration).
-   Internal reconnaissance (for example, an attacker gets to interact with internal software to find its vulnerabilities).
-   Lateral movement through the company's environment.
-   Collect and exfiltrate sensitive data.
-   Deleting the backups and shadow copies. Shadow Copy is a Microsoft technology that can create backup copies, snapshots of computer files, or volumes. 
-   Overwrite or corrupt data.

## Conclusion
The traditional Cyber Kill Chain was designed to secure the network perimeter and protect against malware threats. But the cybersecurity threats have developed drastically nowadays, and adversaries are combining multiple TTP (tactics, techniques, and procedures) to achieve their goal. Adversaries are capable of defeating threat intelligence by modifying the file hashes and IP addresses. Security solutions companies are developing technologies like AI (Artificial Intelligence) and different algorithms to detect even slight and suspicious changes.