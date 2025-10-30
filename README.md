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
![377026627-8e3bb125-d21f-441c-937d-35c0527cfd8b](https://github.com/user-attachments/assets/ee679d71-2886-46ac-8dae-52083609353e)
It displays the following menu and select 2 for Website Attack Vectors:
![377026890-c5c6b2dd-5d2f-465b-ad26-679adde44069](https://github.com/user-attachments/assets/0bb03474-7886-4629-be74-a6f27df461f5)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![377027061-ba03ce43-7b42-40e0-9778-c1c5c6a342e5](https://github.com/user-attachments/assets/6658a70f-2af0-4152-b7bd-684ca16be22f)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![377027188-27e63d5b-13d5-4f20-948e-eb9358598607](https://github.com/user-attachments/assets/dc9e7c40-7a26-4850-a4ee-46ac3e49afaf)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![377027371-9f178493-578a-47df-9d15-feac3665fca2](https://github.com/user-attachments/assets/8946bf3d-040a-48e4-b6fc-1714180de3e2)
It shows the following screen in which the option Google can be selected
![377027544-0f1748e3-9d60-49de-8069-24be0e225bd3](https://github.com/user-attachments/assets/bb3dbaa3-df25-449b-93a2-951057a78a95)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![377027788-9255140d-5ed5-404e-bbdc-d561c251f3cf](https://github.com/user-attachments/assets/5f9c0681-a2eb-4f37-95c8-bd2128c6d57d)
In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password
![377028011-889b0361-824d-4016-aa22-0f35a89eed29](https://github.com/user-attachments/assets/b8ec99e6-838c-4bf2-b2d5-554f70d2a95e)
SET logs the information regarding the Google credentials:
![377028153-6593b6e1-2e2e-44db-9319-cddb52748c39](https://github.com/user-attachments/assets/fce7cc24-85aa-4022-afd6-5370f6a1db13)
SET logs the information in the xml file under /root/.set directory:
![377028273-f1779572-cb0f-40ed-a1fe-2c2c4898117e](https://github.com/user-attachments/assets/2e76b733-87f0-47bf-93b6-934a33488cd4)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
