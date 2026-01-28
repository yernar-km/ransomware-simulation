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
[Dashboard] [Timeline] [Encrypted Files] [Ransom Note]

## Skills Demonstrated
- SIEM Configuration & Tuning
- Log Analysis & Correlation
- Incident Detection & Response
- Threat Hunting
- Python Scripting
- Network Security Monitoring
