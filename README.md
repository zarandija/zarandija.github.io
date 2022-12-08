<!DOCTYPE html>
<html>
<body>
<h1>

Espacico Directorio
sudo du -sh /var

Reputacion

https://emailrep.io/
https://github.com/wahlflo/eml_analyzer
  
Analisis Virus

https://www.virustotal.com/

Analisis hash
https://labs.inquest.net/

Sandbox
https://www.joesandbox.com
https://app.any.run
https://cuckoosandbox.org


!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
Red Team Fundamentals
APT
Advanced Persistent Threat

TTPS
Tactic, Techniques and Procedures

Red Team
Evading: Firewalls, Antivirus, EDR, IPS, etc...

Broken Red Team Three Cells:

Red Cell
Blue Cell
White Cell

Red Team Lead
Red Team Assistant Lead
Red Team Operator

Red Team Engagement

1.	Plannning the Engagement
	Red and White Teams define the goal of the exercise: Access the transactional DB of the Bank
		White and red teams will define goals that align with the business' risk scenarios.
		Blue team is usually not informed at this stage about the excercise, as we want to analyze their natural response against an attacker.
2.	Intelligence Gathering
	The red team gathers as much information as they can about the bank, including:
		Technologies in use
		List of employees
		Information on social media
		Photos
		Any other usable information...

3. Emulating TTP: Phishing campaign
		The red team starts the engagement by emulating a phishing campaign against a list of emails they made, based on employees' names found on LinkedIn and a detected pattern in their email addresses.

		julie.smith@bank.example.com
		john.watson@bank.example.com

4. Emulating TTP: Privilege Escalation and Persistence
		The red team found missing Windows patches on BOB-PC. One of them allowed for PrintNightmare exploitation.

		While the available public exploit was detected by many AV solutions, some AV evasion techniques were successfuly applied to avoid triggering any alarms, obtaining SYSTEM privileges.
		The red team was able to upload and run a modified mimikatz to extract local password hashes, including the local administrator account "Backups".

5. Emulating TTP: Lateral Movement
		The red team used a Pass-the-Hash attack against all hosts on the network to check if the "Backups" user could login to other hosts. No direct connection could be made to the DB server, as firewall policies were in place to prevent it.

6. Reporting and Analysis

ROE=Rules of Engagemen

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!</h1>

</body>
</html>
