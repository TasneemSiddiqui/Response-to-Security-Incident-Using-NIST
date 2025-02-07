<h1> Response to Security Incident Using NIST</h1>
<h2>Scenario</h2>
<I>This scenario is based on a fictional company:</I>
<br /><br />
I am a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. My organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
<br /><br />
During the attack, the organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 
<br /><br />
The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 
<br /><br />
To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets

- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

- Network monitoring software to detect abnormal traffic patterns

- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, I am tasked with using this security event to create a plan to improve my company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). I will use the CSF to help me navigate through the different steps of analyzing this cybersecurity event and integrate my analysis into a general security strategy. The analysis has been broken into different parts as outlined below:

- <b>Identify</b> security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

- <b>Protect</b> internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

- <b>Detect</b> potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

- <b>Respond</b> to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

- <b>Recover</b> affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 

<h3><a href="https://github.com/TasneemSiddiqui/ResponseToSecurityIncidentUsingNIST/blob/main/IncidentReportAnalysis.md">Incident response analysis using NIST CSF</a></h3>
