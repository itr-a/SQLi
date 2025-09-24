# Lab Report: [SQL injection UNION attack, finding a column containing text]


##  Objective
- Retrieve required columns and find out if the data is string format.  

##  Findings
### Vulnerability: [UNION attack]
- **Description:** This vulnerability allows attacker to find how many columns the data has and its data type.  
- **Impact:** If credential data was stoled, it would let unauthorized access available.   

## Proof of Concept   
<img src="<img src="https://github.com/itr-a/SQLi/blob/main/Assets/UNION.png" alt="figure1" width="500"/>   
*figure 1 - Lab home page after payload executed    

<img src="<img src="https://github.com/itr-a/SQLi/blob/main/Assets/find_string_data_payload.png" alt="figure2" width="500"/>   
*figure 2 - Payload

##  Remediation
- Recommended fix or mitigation (e.g., input validation, least privilege).  

##  Reflection
- Noticed to solve the lab by display specific letters in the database, I needed to replace random letters in payload to the letters.  

## Tools
- BurpSuit