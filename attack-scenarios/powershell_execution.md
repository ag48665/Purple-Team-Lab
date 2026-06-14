\# PowerShell Execution Scenario



\## Objective



Simulate PowerShell execution and validate security monitoring coverage.



\## Attack Simulation



```powershell

powershell.exe

```



\## Expected Telemetry



\* Sysmon Event ID 1

\* Process Creation Events



\## MITRE ATT\&CK



| Technique ID | Technique  |

| ------------ | ---------- |

| T1059.001    | PowerShell |



\## Detection Validation



The activity should be detected by monitoring PowerShell process execution in Splunk.



