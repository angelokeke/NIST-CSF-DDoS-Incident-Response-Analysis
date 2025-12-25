# NIST-CSF-DDoS-Incident-Response-Analysis

This project analyzes a simulated Distributed Denial of Service (DDoS) attack and applies the NIST Cybersecurity Framework to investigate the incident, identify root causes, and strengthen network security controls. The attack targeted the organization’s network with a flood of ICMP packets, exploiting an unconfigured firewall and resulting in a temporary network outage and service disruption. This project documents the incident lifecycle across Identify, Protect, Detect, Respond, and Recover functions, and outlines the security improvements implemented afterward.

## Project Objectives

- Apply the NIST CSF to a real-world style security incident  
- Analyze network misconfigurations and security control gaps  
- Strengthen defensive measures and response planning  
- Improve firewall, monitoring, and detection practices  
- Develop incident response communication and recovery steps  

## Tools and Concepts

- NIST Cybersecurity Framework (CSF)  
- Firewall configuration and network hardening  
- ICMP traffic filtering and rate-limiting  
- IP spoofing prevention and source verification  
- IDS and IPS monitoring and alerting  
- Incident response and post-incident review  

## Incident Summary

- A DDoS ICMP flood caused a full network outage for ~2 hours  
- The perimeter firewall allowed unrestricted ICMP traffic  
- Lack of rate-limiting and monitoring delayed detection  
- Attackers spoofed IP addresses to increase packet volume  
- Core network services became unavailable to users  

## Key Security Improvements

### Firewall Hardening

- Implemented ICMP rate-limiting  
- Enabled IP source verification  
- Restricted external ICMP traffic  

### Monitoring & Detection

- Deployed new network monitoring tools  
- Configured IDS / IPS filtering and alerting  
- Added abnormal traffic detection rules  
- Reduced response time for future incidents  

### Incident Response Actions

- Blocked incoming ICMP traffic  
- Shut down non-essential services to stabilize load  
- Issued communication to stakeholders and staff  
- Updated incident response playbook  

### Recovery Efforts

- Restored core services  
- Verified network and system integrity  
- Confirmed no data loss  
- Scheduled recurring firewall and IDS/IPS testing  

## What I Learned

- How configuration gaps can increase attack impact  
- The importance of monitoring and event visibility  
- Practical ICMP flood mitigation strategies  
- Value of structured incident response processes  
- How post-incident review strengthens defense posture  

## Project Reflection

This project strengthened my understanding of incident response, network defense strategy, and the practical application of the NIST CSF in real-world style attack scenarios. It improved my ability to analyze security events, design remediation actions, and document findings in a professional cybersecurity context.
