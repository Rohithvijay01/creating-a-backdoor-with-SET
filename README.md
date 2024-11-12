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

![image](https://github.com/user-attachments/assets/b1be6db7-13bc-444f-97de-1fd85d4b3e6f)
## It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/user-attachments/assets/59d99e36-3e69-4b36-aa30-ddb8213e4df7)
## The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/7fbea1e5-e3a8-46cf-bac5-64d36b63563c)
## The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/user-attachments/assets/d56e2408-21d2-4fcd-bfc7-ab8db30e4090)
## It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/user-attachments/assets/c3cd57f2-9b04-4280-9b0b-e62c4a98aa90)
## It shows the following screen in which the option Google can be selected
![image](https://github.com/user-attachments/assets/6e9c192f-4f0e-4931-97fc-43142085bc69)
## SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/user-attachments/assets/0094236a-8455-4d34-84fd-14777442692a)
## In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/c145818c-ddc5-4fb7-bc57-7f580855d922)
## SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/1787b618-1600-4938-aa22-9eb1c312abea)
## SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/5ecc8a7f-f5f5-47b9-8a3c-98bf4952eea6)















## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
