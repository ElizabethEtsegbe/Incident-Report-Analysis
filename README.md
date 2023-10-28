# Incident Report Analysis

## Summary

The company faced a severe security event when all network services suddenly stopped responding. The cybersecurity team determined that the disruption was a result of a distributed denial of service (DDoS) attack initiated through a flood of incoming ICMP packets. The team took immediate action to block the attack and suspend non-critical network services to facilitate the restoration of essential network services.

## Incident Handling Based on NIST CSF

| **NIST CSF Function** | **Actions Taken**                                           |
|-----------------------|------------------------------------------------------------|
| **Identify**          | - Identified malicious actor(s) responsible for the ICMP flood attack. - The entire internal network was affected, necessitating swift response and recovery actions. |
| **Protect**           | - Implemented a new firewall rule to restrict the rate of incoming ICMP packets. - Introduced an Intrusion Detection System/Intrusion Prevention System (IDS/IPS) to filter out suspicious ICMP traffic based on defined characteristics. |
| **Detect**            | - Configured source IP address verification on the firewall to identify spoofed IP addresses in incoming ICMP packets. - Utilized network monitoring software to detect and analyze abnormal traffic patterns and pinpoint signs of the attack. |
| **Respond**           | - Implemented isolation of affected systems to prevent further disruption. - Initiated the restoration process for critical network systems and services. - Analyzed network logs for evidence of suspicious or abnormal activities. - Reported the incident to upper management and legal authorities, if required, to comply with regulatory obligations. |
| **Recover**           | - Restored access to network services to a normal functioning state. - Established measures to block external ICMP flood attacks at the firewall. - Stopped non-critical network services temporarily to reduce internal network traffic. - Prioritized the restoration of critical network services. - Once the ICMP packet flood subsided, non-critical network systems and services were brought back online. |

## Conclusion

This incident report analysis demonstrates the effective application of the NIST Cybersecurity Framework (NIST CSF) to address and recover from a Distributed Denial of Service (DDoS) attack initiated through an ICMP flood. By taking appropriate steps to identify, protect, detect, respond, and recover from the incident, our organization was able to mitigate the disruption and secure critical network resources.

