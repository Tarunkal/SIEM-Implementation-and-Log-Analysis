# SIEM-Implementation-and-Log-Analysis

# Topology
![Image](https://github.com/user-attachments/assets/a417d525-28ee-4d45-8b5b-0362a4427019)
                                         
## Objective

To showcase the deployment and configuration of an Elastic Stack SIEM integrated with a Kali Linux virtual machine, focusing on real-time threat detection and enhanced incident response capabilities. This project highlights the implementation of Elastic Defend agents and custom alerting mechanisms for detecting network scans, particularly Nmap, along with the development of interactive Kibana dashboards for improved monitoring, threat detection, and vulnerability assessment. The goal is to demonstrate proficiency in SIEM setup, advanced monitoring techniques, and security event analysis through visualizations and tailored alerts.

### Skills Learned

- Expertise in deploying and configuring the Elastic Stack SIEM for comprehensive security monitoring.
- Proficiency in integrating Elastic Defend agents and developing custom alerts for real-time threat detection, including Nmap scans.
- Advanced skills in designing and creating interactive Kibana dashboards and visualizations for enhanced security event analysis.
- In-depth understanding of incident response workflows and techniques for improving detection and mitigation efficiency.
- Ability to analyze and interpret security data to identify potential vulnerabilities and enhance overall system defenses.

### Step-by-Step Methodology

1. Environment Setup

1.1 Install and Configure Virtual Machines

Elastic Stack Setup: Deployed Elasticsearch, Logstash, and Kibana on a virtualized environment to serve as the core SIEM system.

Kali Linux Setup: Installed and configured a Kali Linux virtual machine to perform controlled network scans and security tests.

1.2 Install Elastic Defend Agent

Installed the Elastic Defend agent on the monitored endpoint to collect security event logs and system activity.

Configured the agent to send data to Elasticsearch for indexing and analysis.

2. SIEM Configuration

2.1 Configuring Elasticsearch and Logstash

Installed and configured Elasticsearch as the central data store for security event logs.

Set up Logstash pipelines to ingest and process logs from Elastic Defend agents.

Created filters to normalize log formats and enhance data usability.

2.2 Setting Up Kibana for Log Analysis

Configured Kibana dashboards to visualize security data in real time.

Developed search queries and filters to refine security event monitoring.

Created custom security visualizations and alerts for threat detection.

3. Threat Simulation and Log Collection

3.1 Conducting Network Scans with Nmap

Performed controlled Nmap scans from the Kali Linux VM targeting the monitored environment.

Captured network scan activities through Elastic Defend agent logs.

Verified log ingestion into Elasticsearch and Logstash.

3.2 Extracting and Analyzing Logs

Queried Elasticsearch to retrieve logs related to network scanning activities.

Used Kibana to analyze patterns, detect anomalies, and correlate security events.

4. Custom Alert Implementation

4.1 Creating Custom Security Alerts

Defined detection rules in Kibana for identifying unauthorized Nmap scans.

Configured threshold-based alerts to trigger notifications upon detecting malicious activity.

Integrated alerts with email notifications for real-time security incident awareness.

4.2 Testing Alert Effectiveness

Repeated network scanning tests to validate alert generation and response efficiency.

Tuned alerting thresholds to minimize false positives and enhance detection accuracy.

5. Dashboard Development

5.1 Designing Kibana Dashboards

Created interactive dashboards to display key security metrics and threat detections.

Implemented visual representations of attack attempts, scan frequencies, and affected endpoints.

Configured real-time monitoring panels for continuous security event tracking.

5.2 Optimizing Data Interpretation

Applied data aggregation techniques to improve log analysis efficiency.

Developed query-based dashboards for advanced security investigations.

### Tools Used

- Elastic Stack (Elasticsearch, Logstash, Kibana) for SIEM deployment, log ingestion, and analysis.
- Elastic Defend agents for endpoint monitoring and custom alert creation.
- Kali Linux VM for network scanning and testing in a controlled environment.
- Nmap for generating network scan traffic and testing detection capabilities.
- Kibana for designing interactive dashboards and visualizations for real-time security monitoring..

## Steps
![image](https://github.com/user-attachments/assets/f34d4f56-4c3b-4e98-acb0-3eb99d2b2ee7)

  Fg 1. Dashboard

![image](https://github.com/user-attachments/assets/ff24bf87-9c0a-4f73-9d73-cd0272484ccc)

  Fg 2. Endpoint Logs 

  ![image](https://github.com/user-attachments/assets/6f7a5acd-9079-4003-bf03-049b5279ecd4)

  Fg 3. Raw Logs 

