# Lab Report: UNION Attack

##  TL;DR
- Perform UNION attack to a demo website contains SQLi vulnerability in "category" filter 

##  Objective
- Learn how UNION attack works by inject a payload and reveal how many colmuns the data has.

##  Findings
### Vulnerability: [SQLi]
- **Description:** Malicious UNION payload reveales number of colmuns of the data.  
- **Impact:** By injecting payload, result shows how may colmuns the data has.

## Proof of Concept 
Commands, requests, or screenshots (redacted if sensitive).  
![Payload executed successfully](https://github.com/itr-a/SQLi/blob/main/Assets/UNION.png)  
*figure 1 - Website showing data

##  Remediation
- Use Prepared Statements

##  Reflection
- Understood how UNION attack works in hands-on lab