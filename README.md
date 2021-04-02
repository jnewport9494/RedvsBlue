# RedvsBlue 
Full Red vs Blue activity performing both penetraition testing and security monitoring. 

The activities here are meant to replicate a Red vs Blue engagement. As small group we initally played the role of a blackhat hacker gaining unauthorized access to a company web server and utilizing a PHP reverse shell to establish a Meterpreter session allowing for exfiltration of company data. We then performed the rolle of a Blue Team analyzing the Kibana logs summarize the incident before making system hardening recommendations. By performing all of the roles, this exercise gave us good insight into both offensive and defensive roles. 


This document contains the following:
  
  **Network Topology**
  
  **Network Reconnaissance**
  
  **Vulnerability Assessment**
  
  **Exploit summary**
  
  **Incident Analysis**
  
  **Mitigation Strategies**
  
  An overview of the Network Topology can be found here:
 
https://github.com/jnewport9494/RedvsBlue/blob/main/images/Network%20Topology.png

The configuration details of each machine can be found below:

| Name      | Function  | IP Address   |  Operating System|
|---------- |---------- |------------  | ---------------- |
| Hypervisor| Hypervisor|192.168.1.1   | Windows          |
| Kali      | Attack VM | 192.168.1.90 | Kali Linux       |
| Capstone  |Target VM  | 192.168.1.105| Ubuntu Linux     |
| Elk       |   Logging | 191.168.1.100| Ubuntu Linux     |


