# Red-Team-vs-Blue-Team

For this project, I worked on a Red Team vs. Blue Team scenario in which I played the role of both pentester and SOC analyst.
As the Red Team, I attacked a vulnerable Virtual Machine within my environment, and ultimately gained root access to the machine. As Blue Team, I used Kibana to review logs taken from when I attacked the vulernable machine. I then used the logs to extract hard data and visualizations for their report.
I created mitigation measures for each exploit that I've successfully performed.

## Red Team


-	I ran the command ifconfig to find the IP address of the capstone machine, which was the machine we were attacking.

-	I then ran a Nmap command nmap -sV 192.168.1.105 to find the open ports

-	I then went into the website to see to find any important directories. I was able to find a hidden directory at 192.168.1.105/company_folders/secret_folder that you need to login into as Ashton.
-	Bullet list
-	    Nest


 
