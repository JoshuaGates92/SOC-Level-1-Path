Two core concepts in network security:
1. Authentication
2. Authorisation

### Control level:
1. Physical - prevent unauthorised physical access to networking devices, cable boards, locks, and all linked components.
2. Technical - Data security controls prevent unauthorised access to network data, like installing tunnels and implementing security layers.
3. Administrative - Administrative security controls provide consistency in security operations like creating policies, access levels and authentication processes.

#### Two approaches to these control levels:
| Access Control                                                                                               | Threat Control                                                                                                                                |
|--------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| The starting point of Network Security. It is a set of controls to ensure authentication and authorisation.  | Detecting and preventing anomalous/malicious activities on the network. It contains both internal (trusted) and external traffic data probes. |


## Traffic Analysis

Traffic analysis is one of the essential approaches used in network security, and it is part of multiple disciplines of network security operations listed below:

-   Network Sniffing and Packet Analysis (Covered in [**Wireshark room**](https://tryhackme.com/room/wiresharkthebasics))
-   Network Monitoring (Covered in [**Zeek room**](https://tryhackme.com/room/zeekbro))
-   Intrusion Detection and Prevention (Covered in [**Snort room**](https://tryhackme.com/room/snort))  
-   Network Forensics (Covered in [**NetworkMiner room**](https://tryhackme.com/room/networkminer))
-   Threat Hunting (Covered in [**Brim room**](https://tryhackme.com/room/brim))

### Two techniques:
| Flow Analysis                                                                                                                                                                                                                                                                                                            | Packet Analysis                                                                                                                                                                                                                                                                                                     |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Collecting data/evidence from the networking devices. This type of analysis aims to provide statistical results through the data summary without applying in-depth packet-level investigation. Advantage:  Easy to collect and analyse. Challenge:  Doesn't provide full packet details to get the root cause of a case. | Collecting all available network data. Applying in-depth packet-level investigation (often called Deep Packet Inspection ( DPI) ) to detect and block anomalous and malicious packets. Advantage:  Provides full packet details to get the root cause of a case. Challenge:  Requires time and skillset to analyse. |

Benefits:
-   Provides full network visibility.
-   Helps comprehensive baselining for asset tracking.
-   Helps to detect/respond to anomalies and threats.



