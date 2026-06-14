\---



\## Detection Scenarios



\### 1. PowerShell Execution



\*\*Objective:\*\* Detect PowerShell execution activity and validate process creation monitoring.



\*\*MITRE ATT\&CK:\*\* T1059.001 – PowerShell



\*\*Evidence:\*\*



!\[PowerShell Execution](screenshots/powershell\_execution.png)



\---



\### 2. Command Shell Execution



\*\*Objective:\*\* Detect execution of Windows Command Prompt.



\*\*MITRE ATT\&CK:\*\* T1059.003 – Windows Command Shell



\*\*Evidence:\*\*



!\[Command Shell](screenshots/command\_shell.png)



\---



\### 3. Account Discovery



\*\*Objective:\*\* Detect account enumeration activity using native Windows commands.



\*\*MITRE ATT\&CK:\*\* T1087 – Account Discovery



\*\*Evidence:\*\*



!\[Account Discovery](screenshots/account\_discovery.png)



\---



\### 4. File Creation Activity



\*\*Objective:\*\* Detect file creation events using Sysmon Event ID 11.



\*\*MITRE ATT\&CK:\*\* T1074 – Data Staged



\*\*Evidence:\*\*



!\[File Creation](screenshots/file\_creation.png)



\---



\## MITRE ATT\&CK Coverage



| Technique ID | Technique             |

| ------------ | --------------------- |

| T1059.001    | PowerShell            |

| T1059.003    | Windows Command Shell |

| T1087        | Account Discovery     |

| T1074        | Data Staged           |



\---



\## Repository Structure



```text

Purple-Team-Lab

│

├── README.md

│

├── attack-scenarios

│   └── powershell\_execution.md

│

├── detections

│

└── screenshots

&#x20;   ├── powershell\_execution.png

&#x20;   ├── command\_shell.png

&#x20;   ├── account\_discovery.png

&#x20;   └── file\_creation.png

```



\---



\## Key Takeaways



\* Purple Team exercises improve detection coverage by validating security monitoring against simulated attacker activity.

\* Sysmon provides detailed visibility into process creation, file activity, and command execution.

\* Splunk enables rapid detection development and validation.

\* MITRE ATT\&CK mapping helps measure defensive coverage against known adversary techniques.

\* Detection engineering and threat hunting are closely aligned within Purple Team operations.



