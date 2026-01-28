# Ransomware Attack Simulation & Detection Lab

## Overview
Educational ransomware simulation demonstrating multi-phase attack and SIEM detection capabilities using Security Onion.

## Tech Stack
- **Attack Platform:** Kali Linux, Python 3
- **SIEM:** Security Onion (ELK Stack)
- **Tools:** Syslog-ng, Logstash, Elasticsearch, Kibana
- **Encryption:** Fernet (AES-128 CBC)

## Attack Phases
1. **Reconnaissance** - System enumeration (whoami, id, uname, ps)
2. **C2 Communication** - Beaconing to ports 31337, 8888
3. **File Encryption** - 6 files encrypted with ransom note
4. **Data Exfiltration** - Attempted data theft (blocked)

## Key Results
- ✅ 100% Detection Rate (21/21 events)
- ✅ Complete IoC Extraction (Network, File, Behavioral)
- ✅ MITRE ATT&CK Mapping (T1082, T1071, T1486, T1041)
- ✅ Kibana Dashboards for Analysis
- ✅ Incident Response Plan

## Screenshots
<img width="923" height="651" alt="изображение" src="https://github.com/user-attachments/assets/2b340600-b0b6-4cd4-8462-9d05fcd0be5c" />

<img width="937" height="111" alt="изображение" src="https://github.com/user-attachments/assets/ef14c926-9c68-4763-a519-fd7917f9fb37" />

<img width="942" height="990" alt="изображение" src="https://github.com/user-attachments/assets/9b712635-b276-4035-b664-a092dec2a5d0" />




## Skills Demonstrated
- SIEM Configuration & Tuning
- Log Analysis & Correlation
- Incident Detection & Response
- Threat Hunting
- Python Scripting
- Network Security Monitoring
