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

## OUTPUT:

![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/ebc4047d-00f2-414c-9f12-53cf84247a19)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/8c23253e-fe6c-4c00-96ae-199a86582a29)


It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/018d72f5-5e0d-46b0-a0b5-9aaec7619346)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/81ab6ae5-4c73-4237-955c-d5ebdf1b16ce)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/97d7f795-3f4a-406a-8c6c-2674b3da4a66)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/4d224c3d-e281-4d1c-b185-06a5f4bfcaab)


It shows the following screen in which the option Google can be selected:

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/e46e8fbe-d42d-44ad-b56c-bd3f8899fe9a)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/a68e0503-e85e-47ea-9b86-0fdd0e7d088d)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/0945fec4-5f81-420e-bd96-218a5dfaef9e)


SET logs the information regarding the Google credentials:

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/e4551573-bf7d-4e2c-aee3-41ea3cf92f21)


SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![image](https://github.com/JivanKarthick/creating-a-backdoor-with-SET/assets/121165867/93a64d89-6d55-4f56-bc9c-678916843279)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
