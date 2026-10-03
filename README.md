# Wazuh-Successful-Logon-Detection
Hands-on SOC analyst labs using Wazuh SIEM, Windows, and Kali Linux.


<h2>Environemnt</h2>
<p align="center">
OS: Windows 10 (VirtualBox VM)
<p align="center">
OS: Kali Linux
<p align="center">
Tool: Wazuh SIEM
<p align="center">
Tool: Event Viewer (eventvwr.msc)

<h2>Program Walk-Through</h2>
<p align="center">
1️⃣ Wazuh Agent Connected:
<br/>
Wazuh Endpoints dashboard confirming that the Windows VM is connected as an agent and is actively running. 
<br/>
<img width="1379" height="539" alt="1 - Wazuh - Windows 2022 Agent Active" src="https://github.com/user-attachments/assets/4770fd95-eedf-4916-9681-7bb1262e9550" />


<p align="center">
2️⃣ Windows Logon Success Alerts in Wazuh Threat Hunting
<br/>
Wazuh Threat Hunting view for the Windows agent, showing 881 events over the last 24 hours.
<br/>
<img width="1758" height="757" alt="2 - Wazuh Threat Hunting" src="https://github.com/user-attachments/assets/f5d27dac-773d-47b4-a8b3-b38e1145df1b" />


<p align="center">
3️⃣ Successful Logon Alert Details (1/2)
<br/>
Expanded view of a Wazuh alert from the Windows agent.
<br/>
<img width="1914" height="797" alt="2 - Wazuh Alert" src="https://github.com/user-attachments/assets/5e015de0-f422-4a4f-98d8-a4e4c94ee4d9" />


<p align="center">
4️⃣ Successful Logon Alert Details (2/2)
<br/>
Expanded view of a Wazuh alert from the Windows agent. 
<br/>
<img width="1752" height="780" alt="3 - Wazuh Alert" src="https://github.com/user-attachments/assets/e831afd3-7de3-46ae-bd95-ddc7aaba8abc" />



<h2>Findings</h2>
Wazuh successfully detected and surfaced successful Windows logons, in which I reviewed the alerts, and they showed no signs of malicious behavior.   

<h2>Skills Demonstrated</h2>
<br/>
Deploying and verifying a SIEM agent
<br/>
Searching and filtering alerts in Wazuh Threat Hunting
