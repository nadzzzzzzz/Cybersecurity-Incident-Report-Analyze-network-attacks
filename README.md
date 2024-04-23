DDoS Attack Analysis - Travel Agency Website
This repository contains the analysis of a Distributed Denial-of-Service (DDoS) attack on a travel agency website. This work is a part of the Google Cybersecurity Professional Certificate Program course "Analyze Network Attacks".

Scenario:

The travel agency website experiences a connection timeout error. Investigation reveals a large number of TCP SYN requests originating from an unfamiliar IP address. This overload of connection requests overwhelms the web server, preventing legitimate users from accessing the website.

Analysis:

The symptoms and log data indicate a DDoS attack, specifically a SYN flood attack.
The attacker sends a massive number of SYN packets, disrupting the normal three-way handshake process used by TCP to establish connections.
The server becomes overloaded with half-opened connections, exhausting resources and preventing it from responding to legitimate requests.
Findings:

This DDoS attack disrupts the travel agency's business operations by making the website inaccessible to customers and employees.
Simple IP blocking is a temporary solution as attackers can spoof IP addresses.
Recommended Next Steps:

Implement a DDoS protection service to filter malicious traffic before it reaches the server.
Configure a Web Application Firewall (WAF) to identify and block suspicious traffic patterns.
Set up rate limiting rules on the firewall to restrict the number of incoming connections per IP address.
Develop an incident response plan to efficiently handle future security incidents.
Further Investigation:

Investigate the source of the attack and potential reasons behind it.
Research industry best practices for DDoS prevention and mitigation strategies.
Disclaimer:

This repository is for educational purposes only and does not contain any sensitive information from the actual scenario.
