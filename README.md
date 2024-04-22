## Scenario
You are working as a network engineer for an IT company and you have been assigned to design and implement a new enterprise network infrastructure based on traditional technologies and IPv4 addressing for the company.
The company consists of four departments – Finance/HR, Engineering, Sales, and Administration – and provides wired LAN access and PC desktop workstations for office-based users.
The network requires five servers – Web, Email, DNS, Authorisation, and a File/Print server – and access to all servers must be provided for all office-based users. External users can access the company’s external website only.
It is company policy to allow staff to use a wireless network with their own devices, such as smartphones, to access the internet, although these devices should be able to access the servers but not be permitted to access the departmental networks. In addition, the company would like to trial the use of IoT devices to monitor the server room.
The distribution of workstations is shown in Table 1, which describes the high-level network requirements for each department.
### Department	Workstations	Network Requirements
![image](https://github.com/Nastasiia21/Network-Design/assets/97028880/b76494a8-a634-4ea0-a811-987c4ff6c8d3)

Finance /HR 	120 computers 	Each department has a dedicated wired LAN network that cannot access workstations in any other department.
Engineering 	50 computers  	
Sales 	200 computers  	
Administration 	25 computers  	
Wireless devices 	Staff-owned devices 	Cannot access any internal departmental networks and requires a separate logical network to access the company servers. 
Authorisation server	1 server machine	Authorises users to logon to the internal company resources (servers and workstations)
Email, DNS & file/ print server 	3 server machines	Accessible by all company computers and authorised wireless devices, providing shared services to authorised users.
Web server	1 server machine	Server hosting an externally facing website accessible to any users.
IoT devices	IoT devices	A new requirement for IoT devices to monitor the server room temperature and door.
Table 1: workstation and server distribution and requirements
III.	Assessment Tasks
This assessment is broken down into the following tasks:
Task 1
Analyse the requirements given in the scenario and design a suitable network model, IP address design and network components that meet the requirements of the stakeholders. Based on your analysis and evaluation apply the chosen design to the scenario.
