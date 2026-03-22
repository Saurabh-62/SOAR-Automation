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
<img width="1910" height="1086" alt="Screenshot 2026-02-07 185004" src="https://github.com/user-attachments/assets/30357291-4a59-45f1-9d72-8a373148fcdb" />
Ref 1: Wazuh Setup
<br> </br>
<img width="1919" height="1087" alt="Screenshot 2026-02-07 185020" src="https://github.com/user-attachments/assets/37e3596b-5fa4-4e6c-81ae-724632442a01" />
Ref 2: TheHive Setup
<br> </br>
3. Run Malware on the Windows Machine
<img width="1060" height="262" alt="Screenshot 2026-03-22 114921" src="https://github.com/user-attachments/assets/173e5fc8-76cf-4532-9213-262ab131907f" />
Ref 3: Mimikatz installation
<br> </br>
4. Configure Detection Rules
<img width="1269" height="480" alt="Screenshot 2026-03-22 115625" src="https://github.com/user-attachments/assets/2ec484fa-ae67-4275-bbb5-eb43997eedc7" />
Ref 4: Detection Rules
<br> </br>
5. Create an automated response with Shuffle to alert the analyst 
<img width="1919" height="1008" alt="Screenshot 2026-02-07 225714" src="https://github.com/user-attachments/assets/9e4c8cdf-d7a4-4e3e-8264-96e2c634607b" />
Ref 5: Automation
<br> </br>
<img width="1510" height="553" alt="Screenshot 2026-03-22 115220" src="https://github.com/user-attachments/assets/423a7265-5fca-48ff-8f25-cfcd994c86a0" />
Ref 6: Email notification 



