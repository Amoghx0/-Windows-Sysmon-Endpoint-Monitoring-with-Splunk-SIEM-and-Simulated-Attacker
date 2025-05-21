# Windows-Sysmon-Endpoint-Monitoring-with-Splunk-SIEM-and-Simulated-Attacker
## Objective

### To simulate a real-world security monitoring and threat detection environment using a Windows machine with Sysmon as the endpoint telemetry collector, Splunk as the centralized SIEM solution, and a Linux system as the attacking machine. The goal is to understand how endpoint events can be collected, analyzed, and used to detect malicious activity in a controlled lab setup.

![Screenshot (10)](https://github.com/user-attachments/assets/d1d35222-c282-46bb-ac6f-975b07e95dcb)

## Points learned

### Endpoint Telemetry Collection (Sysmon)
- Installed and configured Sysmon on a Windows machine to capture detailed system activity logs.

- Customized the Sysmon configuration to reduce noise and focus on high-fidelity security events.

### SIEM Integration with Splunk:
- Deployed and configured Splunk to receive and index Sysmon logs.

- Created dashboards and alerts in Splunk to visualize suspicious behaviors

### Simulated Attack Scenarios (Linux Attacker)
- Used a Kali Linux machine to perform reverse shell attack to simulate real-world attack patterns.

- Observed how these attacks are logged by Sysmon and how they appear in Splunk.

![Screenshot (9)](https://github.com/user-attachments/assets/f0a4e880-103a-424d-b094-fe2728344c5a)

##  Detecting suspicious alert
= Developed basic detection rules using Splunk to trigger alerts on suspicious events.

- Practiced threat hunting by tracing attacker actions through Sysmon logs.
![Screenshot (12)](https://github.com/user-attachments/assets/fdef6b5d-1a95-400c-ba25-c61f4c5c04fd)


## Conclusion


### This homelab provided practical, hands-on experience with endpoint monitoring, log collection, and SIEM-based threat detection.

- The value of endpoint visibility in early threat detection.

- Using Splunk to build detections and gain situational awareness.

- How attacker activities manifest in logs and how to trace them.

### Overall, this project strengthened my foundational knowledge in SOC operations, endpoint security, and adversary detection—critical skills for any role in cybersecurity, especially in threat detection and response.

