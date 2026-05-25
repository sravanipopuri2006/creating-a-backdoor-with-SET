# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

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
## OUTPUT
<img width="782" height="714" alt="image" src="https://github.com/user-attachments/assets/95de6771-fafb-4f3e-b815-c1baa8608813" />




The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="504" height="412" alt="image" src="https://github.com/user-attachments/assets/ef4eb4c6-d23c-49d7-8141-d6a51e94acbb" />




It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="468" height="277" alt="image" src="https://github.com/user-attachments/assets/e0714e3d-73fa-4f23-a785-5ea4c3232317" />




The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="767" height="417" alt="image" src="https://github.com/user-attachments/assets/508d5993-d178-4ea6-943e-e88a6f9b4946" />





It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="781" height="155" alt="image" src="https://github.com/user-attachments/assets/0fc299b6-879f-4790-9112-b3d33cbefaff" />






SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="783" height="154" alt="image" src="https://github.com/user-attachments/assets/7cbc4baa-682b-41fb-8d85-1df7681ba7ea" />





In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="798" height="397" alt="image" src="https://github.com/user-attachments/assets/4062b298-5bf0-441b-aba0-9952911d3992" />



SET logs the information regarding the Google credentials:
## OUTPUT
<img width="779" height="690" alt="image" src="https://github.com/user-attachments/assets/76d457d6-e42a-46c3-8ecb-6839e22411c1" />




SET logs the information in the xml file under /root/.set directory:
## OUTPUT
<img width="785" height="188" alt="image" src="https://github.com/user-attachments/assets/cdb9ebcd-36fc-42d8-87ca-de2d3ba1cdc1" />













## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
