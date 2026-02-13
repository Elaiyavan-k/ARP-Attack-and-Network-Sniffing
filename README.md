# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
<img width="734" height="543" alt="Screenshot 2026-02-13 081410" src="https://github.com/user-attachments/assets/676f1723-d58e-439e-a1d9-31192e2046fd" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="669" height="613" alt="image" src="https://github.com/user-attachments/assets/1fa24f07-9722-4fe2-a6c4-22d9c7606b29" />


 dsniff:
<img width="1119" height="252" alt="546276371-66c8b168-85f8-4481-8646-a44970307be7" src="https://github.com/user-attachments/assets/2ab2726e-aef1-4d9c-944b-a643f7adda08" />


Invoke the wireshark and examine the various menus  and controls of the tool:
## Output
<img width="1684" height="636" alt="546288369-89b21e77-6dd4-4e10-adf8-45f04dd91f87" src="https://github.com/user-attachments/assets/1e4bb194-53bd-4023-812a-9677e468e2a9" />
<img width="1532" height="763" alt="546288458-a9f7dfcb-5382-4ccc-a39d-0a8ef492895c" src="https://github.com/user-attachments/assets/5a9c50ba-c054-4032-aa83-ffc5b7e6390b" />

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
