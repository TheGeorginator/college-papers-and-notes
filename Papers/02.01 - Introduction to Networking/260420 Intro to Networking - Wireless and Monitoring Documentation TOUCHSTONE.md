### Overview

**What You Will Learn:** In this Touchstone Task, you will document GreenLeaf’s wireless infrastructure, performance baselines, logging configuration, and monitoring environment using real network artifacts. You will analyze SSIDs, wireless standards, channel plans, security controls, monitoring dashboards, and baseline reports to build the wireless and monitoring section of your final Touchstone portfolio. GreenLeaf Organic Foods has provided the following artifacts:

- [Wireless Site Survey Report](https://app.sophia.org/download/attachment/63644-Wireless_Site_Survey.txt) [Wireless_Site_Survey.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%203/Wireless_Site_Survey.txt.md)
- [Portland Wireless AP Configuration Export](https://app.sophia.org/download/attachment/63645-AP_Configuration_Portland.txt) [AP_Configuration_Portland.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%203/AP_Configuration_Portland.txt.md)
- [Eugene Wireless AP Configuration Export](https://app.sophia.org/download/attachment/63646-AP_Configuration_Eugene.txt) [AP_Configuration_Eugene.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%203/AP_Configuration_Eugene.txt.md)
- [Syslog Server Configuration](https://app.sophia.org/download/attachment/63647-Syslog_Configuration.txt) [Syslog_Configuration.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%203/Syslog_Configuration.txt.md)
- [Sample Log File – Normal Operations](https://app.sophia.org/download/attachment/63648-Sample_Logs_Normal.txt) [Sample_Logs_Normal.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%203/Sample_Logs_Normal.txt.md)
- [Sample Log File – Anomalous Events](https://app.sophia.org/download/attachment/63649-Sample_Logs_Anomalous.txt) [Sample_Logs_Anomalous.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%203/Sample_Logs_Anomalous.txt.md)
- [QoS Policy Configuration](https://app.sophia.org/download/attachment/63650-QoS_Policy_Config.txt) [QoS_Policy_Config.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%203/QoS_Policy_Config.txt.md)
- [Network Performance Baseline Report](https://app.sophia.org/download/attachment/63651-Performance_Baseline_Report.txt) [Performance_Baseline_Report.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%203/Performance_Baseline_Report.txt.md)
- [Network Monitoring Dashboards](https://app.sophia.org/download/attachment/63652-Network_Monitoring_Dashboards.txt) [Network_Monitoring_Dashboards.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%203/Network_Monitoring_Dashboards.txt.md)

**Why It Matters:** Wireless networks and monitoring tools reveal the day-to-day health of an environment. Understanding baselines, logs, alerts, and performance trends helps identify issues before they become outages. This Touchstone strengthens your ability to interpret monitoring artifacts and communicate findings clearly. **What You Will Hand In:** A single 2–3 page doc or docx that includes:

- An SSID table with security settings and VLAN mappings
- A wireless design summary supported by survey and AP configs
- A monitoring baseline snapshot and written analysis
- A short log analysis comparing normal and anomalous events

**Keys to Success:**

- Develop and submit original work
- Connect AP placement, channels, and coverage to survey data
- Define baseline metrics with units, thresholds, and time windows
- Support log interpretations with specific entries from the samples
- Label any tables or figures clearly

**Helpful Links:**

- Academic Integrity Guidelines
- Ethical Standards and Appropriate Use of AI

[Share your feedback on Touchstones](https://app.sophia.org/spcc/introduction-to-networking-2-touchstone-task-3-1#)

### Instructions

**Step 1: Review the Materials**  
Use the [Unit 3 Documentation Worksheet](https://app.sophia.org/download/attachment/65813-ITN%20Unit%203%20Touchstone%20Task%20Student%20Template.docx) and the GreenLeaf Wireless and Monitoring Resources.  
Review the artifacts to document:

- Wireless SSIDs, channels, standards, and security
- AP placement and coverage characteristics
- Monitoring dashboards and baseline performance reports
- Syslog configuration, logging behavior, and alert definitions
- Normal and anomalous log patterns
- QoS classifications and monitored impact

---

**Step 2: Wireless Network Design**  
Document the wireless design by summarizing:

- All wireless networks (SSIDs) and their purposes
- Wireless standards used (802.11n/ac, channel widths, MIMO)
- Channel selection and AP placement strategy from the site survey
- Wireless security implementation (WPA2/WPA3, authentication type, client isolation)

Use evidence from the site survey, heat maps, and AP configs.

---

**Step 3: Network Performance Monitoring**  
Based on the monitoring dashboards and baseline report:

- Identify the monitoring tools/platforms (for example, PRTG)
- Document key performance metrics (bandwidth, latency, device status, VoIP MOS)
- Establish baseline values for critical segments (WAN, VPN, servers, switches)
- Summarize any QoS classifications shaping performance

---

**Step 4: Logging and Alerts**  
Using the syslog configuration and log samples:

- Document where logs are collected and how devices send logs
- List critical alert types configured in Graylog or PRTG
- Summarize normal log patterns
- Identify at least two anomalous events and explain why they matter
- Recommend improvements to logging coverage or alert thresholds

---

**Step 5: Review and Submit**  
Export your completed worksheet to a single doc or docx. Ensure all tables and figures are labeled and readable.

### Self Assessment

![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) My SSID table reflects channel, security, and VLAN data accurately.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) Baselines include metrics, thresholds, intervals, and sources.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) Logs and alerts reference actual entries from the provided artifacts.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) Wireless explanation uses survey and AP configuration evidence.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) Monitoring summary includes tools and major tracked metrics.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) Document is clear, concise, and well-organized.