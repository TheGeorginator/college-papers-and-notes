### Overview

**What You Will Learn:** In this Touchstone Task you will analyze GreenLeaf’s security controls across firewalling, VPN configuration, authentication systems, device hardening, and vulnerability management. Using real security artifacts, you will document security zones, rule sets, encryption methods, access control systems, and risks identified by scanning and auditing tools. This work becomes the security section of your final Touchstone portfolio. GreenLeaf Organic Foods has provided the following artifacts:

- [Vulnerability Assessment Report](https://app.sophia.org/download/attachment/63655-Vulnerability_Scan_Report.txt)
- [VPN Configuration Details](https://app.sophia.org/download/attachment/63656-VPN_Configuration_Details.txt)
- [Security Architecture Diagram Set](https://app.sophia.org/download/attachment/63657-Security_Architecture_Diagram.txt)
- [Authentication Server Configuration](https://app.sophia.org/download/attachment/63658-Security_Architecture_Diagram.txt)
- [Radius Server Configuration](https://app.sophia.org/download/attachment/63662-RADIUS_Server_Config.txt)
- [Firewall Rule Set](https://app.sophia.org/download/attachment/63659-Firewall_Rule_Set.txt)
- [Device Hardening Assessment Report](https://app.sophia.org/download/attachment/63660-Device_Hardening_Report.txt)
- [802.1X Wireless Authentication Implementation Guide](https://app.sophia.org/download/attachment/63661-802.1X_Implementation.txt)

**Why It Matters:** Security documentation enables clear communication during audits, incident response, and change management. Understanding how firewall rules, authentication methods, and encryption techniques work together strengthens your ability to protect real networks. **What You Will Hand In:** Submit a single document (doc or docx) (2–3 pages) that includes:

- A labeled diagram of GreenLeaf security zones
- A summary of firewall rules with business justification
- Documentation of VPN encryption/authentication settings
- A brief authentication and hardening overview
- Identified vulnerabilities and recommended mitigations

**Keys to Success:**

- Tie each firewall rule to a specific business requirement
- Verify VPN and encryption settings using evidence from configuration files
- Clearly describe authentication flows (RADIUS, 802.1X)
- Explain hardening findings using provided assessment data
- Support risk statements with evidence from vulnerability scan results

[Share your feedback on Touchstones](https://app.sophia.org/spcc/introduction-to-networking-2-touchstone-task-4-1#)

### Instructions

**Step 1: Review the Materials**  
Use the [Unit 4 Documentation Worksheet](https://app.sophia.org/download/attachment/63663-ITN%20Unit%204%20Touchstone%20Task%20Student%20Template.docx) and the GreenLeaf Security Resources.  
Review all artifacts to identify:

- Network security zones and segmentation
- Firewall rules and allowed/blocked traffic
- VPN settings, encryption, and authentication
- Authentication systems (RADIUS, AD, 802.1X)
- Device hardening measures and gaps
- Key vulnerabilities and risks

---

**Step 2: Network Security Architecture**  
Document GreenLeaf’s security architecture by summarizing:

- The security zones: Outside, Inside, VPN, Guest (use the provided diagrams)
- Firewall placement and traffic flow between zones
- Segmentation of user, server, wireless, and guest networks
- At least three vulnerabilities identified in the Vulnerability Assessment Report

---

**Step 3: Firewall and Access Control**  
Using the Firewall Rule Set:

- Document the primary inbound and outbound firewall rules
- Provide a business justification for each permitted service
- Identify any weaknesses or overly permissive rules
- Describe how guest traffic is isolated

---

**Step 4: Remote Access & Encryption**  
Using the VPN Configuration Details:

- Describe the site-to-site VPN, including Phase 1 and Phase 2 settings
- Document encryption (AES-256), integrity, DH group, and PFS
- Explain authentication (pre-shared key) and any concerns noted
- List other encryption protocols used across the network (TLS, SSH, SMB3, PEAP)

---

**Step 5: Authentication & Hardening**  
Using the RADIUS configuration, 802.1X guide, and hardening report:

- Document how RADIUS and Active Directory control wireless access
- Summarize the 802.1X authentication flow
- Identify at least three device hardening strengths
- Identify at least two gaps or missing controls (for example SNMPv2c, Telnet, DHCP Snooping)

---

**Step 6: Review and Submit**  
Export your completed worksheet to a single document (doc or docx). Ensure your tables and diagrams are clearly labeled.

### Self Assessment

![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) VPN and encryption details match the configuration files.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) Vulnerability findings are accurate.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) Authentication flow is clearly summarized.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) My document is clear, labeled, and 2–3 pages.