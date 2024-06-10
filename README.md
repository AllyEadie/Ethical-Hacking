# Ethical-Hacking

## Objective
For this project, I aim to conduct a comprehensive and complex penetration test within a controlled environment, based on a given scenario. The objective is to demonstrate the entire process of planning and executing a penetration test, including:

- Planning Phase:
- Defining the Scope: Clearly outlining the scope of the penetration test, ensuring it is well-defined and agreed upon before any testing begins.
- Reconnaissance Techniques: Utilizing various reconnaissance techniques such as port scanning, identifying active machines, and, if appropriate, incorporating social engineering tactics. These techniques will be discussed and agreed upon during the planning phase.
- Documentation: Keeping meticulous documentation of the planning phase for assessment and reference purposes.

This project will showcase my skills in penetration testing, from initial planning to execution, and will highlight my ability to methodically approach security testing in a structured and controlled manner.

### Skills Learned


Through this project, I have developed and demonstrated the following skills:

- Penetration Testing: Comprehensive understanding and application of penetration testing methodologies.
- Reconnaissance Techniques: Proficiency in using various reconnaissance techniques including port scanning, identifying active machines, and social engineering.
- Planning and Organization: Skills in planning and organizing a penetration test, ensuring all necessary steps are meticulously planned and documented.
- Documentation: Competence in maintaining thorough documentation of the planning and execution phases, crucial for assessment and future reference.
- Security Assessment: Ability to methodically approach security testing, identifying vulnerabilities, and assessing security measures.
- Problem-Solving: Enhanced problem-solving skills through identifying and addressing security issues in a structured manner.
- Attention to Detail: Increased attention to detail through careful planning, execution, and documentation of each step of the penetration test.
- Communication: Improved communication skills by discussing and agreeing on techniques and scope with relevant stakeholders.

### Tools Used
[Bullet Points - Remove this afterwards]

Throughout this penetration test project, I have utilized:

- Nmap: For network discovery and security auditing, including port scanning and identifying active machines.
- Metasploit: For exploitation and vulnerability validation.
- Kali Linux: As the primary platform for penetration testing, offering a comprehensive suite of tools.

By leveraging these tools, I have been able to perform thorough and effective penetration testing, ensuring a comprehensive assessment of the given scenario's security posture.

## Steps
### The Reconnaissance Phase
![image](https://github.com/AllyEadie/Ethical-Hacking/assets/172256085/d99e3cf0-8f95-4646-affe-71c0e4f0ac4c)

- **<u>CEO</u>** Wael Sawan.
- **<u>Company</u>** Shell UK.
- **<u>Address</u>** 91 Treadord Lane, Birmingham, England, B82UE.
- **<u>IP Address</u>** 65.52.64.201.
- **<u>Company Web</u>** www.shell.co.uk.
- **<u>Contact Details Mob</u>** +97455571621.
- **<u>Email Adressess</u>** wael.sawan@shell.com, wsawan@hotmail.com.
- **<u>Place Of Birth</u>** Beirut, Lebanon.
- **<u>Education</u>** McGill University “Masters In Engineering” 1992-1997, Harvard Business School 2001-2003.
- **<u>Wife </u>** Nicole Sawan.
- **<u>Social</u>** Pintrest.co.uk User Name @cocole64

### Laws That Where Observed
- UK Computer Misuse Act 1990.
- UK Data Protection Act 1998.
- Human Rights Act 1998.
- Police and Justice Act 2006.

### Summary of Reconnaissance
- I started of by googling Shell .co.uk once I found the web page I then did a nslookup in Command prompt to find the IP Address of the web page as seen in screen shot.
![image](https://github.com/AllyEadie/Ethical-Hacking/assets/172256085/04ba34b5-f842-444a-8df5-d4a2ccd189db)
- I then focust on Who the CEO was. I then searched LinkedIn, Wikipedia, RocketReach, CEOmail to gather information on him and his family and any Co workers.

 ### Host Descovery
 - I used Fping to see what hosts where on the network and saved them in a file called host.txt I then used the command cat host.txt to see the available host ip addresses.
![image](https://github.com/AllyEadie/Ethical-Hacking/assets/172256085/05a1303d-75e1-43e4-a524-69edfbb35ced)

### Vulnerability Scan
- I Conducted a vulnerability scan and after doing my research on them I have decided to try smb-vuln-ms17-010.
![image](https://github.com/AllyEadie/Ethical-Hacking/assets/172256085/5774f7f7-30cd-43fa-91f6-1c3c3f1a22aa)

### Deploying Exploit
- I set the remote port and host and I did the same for the local host and port from there I set the payload command then run it once it was complete I gain meterpreter privilege. 
![image](https://github.com/AllyEadie/Ethical-Hacking/assets/172256085/e32fdbf6-904b-4523-b840-769a935ac81c)
![image](https://github.com/AllyEadie/Ethical-Hacking/assets/172256085/d8bb1c7a-5dd3-4909-9dba-824fe3d2174d)

### Create A Persistence
- Now that I have gained access I need to set up a payload to deliver so that I keep access even if the host shuts his pc of when he logs back in it will ping back to my and ill have full access to his system.
![image](https://github.com/AllyEadie/Ethical-Hacking/assets/172256085/5f8f8c90-74fc-4cee-a41f-6b64d575e469)

### Persistence Delivered
- I inserted a script to to create a back door so that even if the target turns off it will automatically log me back in every time. 
![image](https://github.com/AllyEadie/Ethical-Hacking/assets/172256085/ed775ddf-e0c7-4fac-bee6-a3cb3064b18a)

### Clearing Logs
- Once I inserted the back door and seen that it worked I then worked on clearing my tracks I did this by clearing the logs to hide my activity.
![image](https://github.com/AllyEadie/Ethical-Hacking/assets/172256085/b5494da4-9d85-48df-a295-04c143c54150)

























