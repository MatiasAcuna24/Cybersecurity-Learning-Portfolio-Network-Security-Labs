## MITRE ATT&CK Mapping

| Attack Activity | Tactic | Technique | ID |
|----------------|--------|----------|----|
| Network Port Scan | Reconnaissance | Active Scanning | T1595 |
| SMB Brute Force | Credential Access | Brute Force | T1110 |
| Failed Logon Attempts | Credential Access | Valid Accounts | T1078 |
| Domain User Enumeration | Discovery | Account Discovery | T1087 |

The simulated attacks align with several techniques defined in the MITRE ATT&CK framework.

The attacker performed network reconnaissance using port scanning, followed by authentication attacks against SMB services.  
After authentication attempts, the attacker tried to enumerate domain users in the Active Directory environment.

These behaviors correspond to common attacker activities observed during the early stages of an intrusion.

| Attack Activity | Technique | MITRE Link |
|----------------|----------|-----------|
| Network Port Scan | Active Scanning | https://attack.mitre.org/techniques/T1595 |
| SMB Brute Force | Brute Force | https://attack.mitre.org/techniques/T1110 |
| Domain User Enumeration | Account Discovery | https://attack.mitre.org/techniques/T1087 |