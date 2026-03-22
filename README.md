# SOAR Automation

## Objective
The goal of the SOAR Automation project was to create a SOC environment and optimize incident response by automatically detecting threats. The primary focus was to ingest and analyze logs within Wazuh, generating test telemetry to mimic real world attack scenarios. This experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned
- Using Wazuh to write custom queries
- Integrating APIs and multiple security platforms
- Creating a SOAR workflow with Shuffle

### Tools Used
- Microsoft Azure as the cloud platform to deploy Windows virtual machines
- Wazuh as the SIEM 
- TheHive to connect to Wazuh and create notifications
- Email for alerting the analyst
- VirusTotal to lookup IP addresses and reputation scores
- Shuffle as the SOAR platform to automate the response

## Steps
1. Setup Wazuh and TheHive
<br> </br>
2. Create a Wazuh Agent
<br> </br>
3. Run Malware on the Windows Machine
<br> </br>
4. Configure Detection Rules
<br> </br>
5. Create an automated response with Shuffle to alert the analyst 
