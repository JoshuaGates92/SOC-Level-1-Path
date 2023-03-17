## Introduction to IDS/IPS

SNORT is an open-source, rule-based Network Intrusion Detection and Prevention System (NIDS/NIPS)

### Intrusion Detection System(IDS) vs Intrusion Prevention System(IPS)

#### IDS
- Passive monitoring system, generating alerts of suspicious activity
	- 2 main types:
		1. Network Intrusion Detection System(NIDS) - Investigate entire network (subnet)
		2. Host-based Intrusion Detection System(HIDS) - Monitors network flow from a singular endpoint device. Investigate traffic in and out of a specific device rather than the subnet as a whole.

### IPS
- Active monitoring system
	- 4 main types:
		1. Network Intrusion Prevention System(NIPS) - Monitors traffic from various areas of subnet.
		2. Behaviour-based Intrusion Prevention System(Network Behaviour Analysis - NBA) - Behaviour based systems monitor the traffic. 
			- Difference between these and NIPS is these require a training period or baselining to learn what 'normal traffic' is on that subnet
		3. Wireless Intrusion Prevention System(WIPS) - It's in the name
		4. Host-based(HIPS) - Terminates connection from malicious devices

### Detection/Prevention Techniques

1. Signature-based: relies on rules that identify the specific patterns of the known malicious behaviour. This model helps detect ==known threats==.
2. Behaviour-based: identifies new threats with new patterns that pass through signatures. The model compares the known/normal with unknown/abnormal behaviours. This model helps detect ==previously unknown or new threats==.
3. Policy-based: compares detected activities with system configuration and security policies. This model helps detect ==policy violations==.

## Snort Rules
![[SNORT Rule anatomy.png]]




