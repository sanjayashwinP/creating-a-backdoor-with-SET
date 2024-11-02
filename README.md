# EX 7: creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course
### NAME:SANJAY ASHWIN P
### REG NO:212223040181

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/user-attachments/assets/e947091b-0ca1-4223-a81b-79bed178f798)


sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![WhatsApp Image 2024-11-01 at 21 25 51_3d06b3b6](https://github.com/user-attachments/assets/5ec3ea80-a2b0-43bf-932d-61a1868be299)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/db748449-152f-4541-b0ba-df66a2500e4d)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/user-attachments/assets/aa0588fe-8745-4571-b381-28f1ec95a87e)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/user-attachments/assets/9e8f2b36-27ea-4611-928a-db45b1104338)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/user-attachments/assets/ac2c3291-2a88-4943-91f2-5216ab9661de)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![WhatsApp Image 2024-11-01 at 21 33 46_14b747de](https://github.com/user-attachments/assets/88afe2e6-66dd-4060-8c29-4d8b946ad21c)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![WhatsApp Image 2024-11-01 at 21 50 40_67b13330](https://github.com/user-attachments/assets/ec5328e8-6166-438b-8c20-2fb269c798b7)

SET logs the information regarding the Google credentials:

![WhatsApp Image 2024-11-01 at 21 54 08_138956ac](https://github.com/user-attachments/assets/e2338264-b947-464b-9d54-9adcb144db67)


SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/9db44d5c-d0e6-4e7a-9393-b1b066c7ea55)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
