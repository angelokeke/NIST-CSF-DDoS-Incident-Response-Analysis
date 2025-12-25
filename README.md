# NIST-CSF-DDoS-Incident-Response-Analysis
This project analyzes a simulated Distributed Denial of Service (DDoS) attack and applies the NIST Cybersecurity Framework to investigate the incident, identify root causes, and strengthen network security controls. The attack targeted the organization’s network with a flood of ICMP packets, exploiting an unconﬁgured firewall and resulting in a temporary network outage and service disruption. This project documents the incident lifecycle across Identify, Protect, Detect, Respond, and Recover functions, and outlines the security improvements implemented afterward.
Project Objectives

Apply the NIST CSF to a real-world style security incident
Analyze network misconfigurations and security control gaps
Strengthen defensive measures and response planning
Improve firewall, monitoring, and detection practices
Develop incident response communication and recovery steps

Tools and Concepts

NIST Cybersecurity Framework (CSF)
Firewall configuration and network hardening
ICMP traffic filtering and rate-limiting
IP spoofing prevention and source verification
IDS and IPS monitoring and alerting
Incident response and post-incident review

Incident Summary

A DDoS ICMP flood caused a full network outage for ~2 hours
The perimeter firewall allowed unrestricted ICMP traffic
Lack of rate-limiting and monitoring delayed detection
Attackers spoofed IP addresses to escalate traffic volume
Core network services became unavailable to users

Key Security Improvements

-Firewall Hardening

Implemented ICMP rate-limiting

Enabled IP source verification

Restricted external ICMP traffic

-Monitoring and Detection

Deployed network monitoring tools


Configured IDS / IPS rules

Added abnormal traffic alerting

Reduced response time for future events

-Operational Response

Blocked ICMP traffic during incident

Shut down non-critical services to stabilize load

Communicated incident status to stakeholders

Updated response playbook and training procedures

-Recovery Actions

Restored services and validated system integrity

Confirmed no data loss occurred

Scheduled recurring firewall and IDS/IPS testing

What I Learned

How network misconfigurations can increase attack impact

The importance of monitoring, alerts, and visibility

How ICMP flooding can overwhelm infrastructure

Why proactive security controls reduce downtime

How structured frameworks guide better incident handling

Project Reflection

This project strengthened my understanding of incident response, network defense strategy, and practical application of the NIST CSF in real-world scenarios. It improved my ability to analyze security events, design remediation actions, and document findings in a professional security context.
