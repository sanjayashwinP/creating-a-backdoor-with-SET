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

![image](https://github.com/user-attachments/assets/8b1163f5-4886-4fed-b1ef-1420c1284a63)
sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/user-attachments/assets/951d4ecd-9b56-451f-bee9-034a13fd8c7d)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/d9ddb284-4273-480e-acd5-9f0db1721f68)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/user-attachments/assets/ed938469-4bf1-4b7c-92a9-a174b2d13812)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/user-attachments/assets/daba866a-e2dc-40d4-a2db-d5761b6dd7aa)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/user-attachments/assets/f9dfa4c7-41b4-408f-80a8-a721e3eb44c0)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/user-attachments/assets/e6030ecb-cc39-4b45-b2fd-d2d2b1f62de5)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/user-attachments/assets/c63824c8-d884-4fe5-802a-b0d772e063ac)

SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/6bc122bd-7651-437a-be18-a06b790eb797)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/eb860581-4b9f-4923-b762-13423fb56ee0)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
