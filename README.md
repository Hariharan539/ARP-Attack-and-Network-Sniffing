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


<img width="859" height="543" alt="image" src="https://github.com/user-attachments/assets/b9ffe5aa-0a5a-43a1-bcab-48c190d2771c" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="837" height="501" alt="image" src="https://github.com/user-attachments/assets/ba7a6528-f104-457b-99d9-0de5b67b3cef" />

<img width="811" height="486" alt="image" src="https://github.com/user-attachments/assets/e00302c6-6e68-4173-a54d-801667c4034f" />




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="849" height="586" alt="image" src="https://github.com/user-attachments/assets/20e90008-dc91-4187-b429-126139efcdda" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="1634" height="684" alt="image" src="https://github.com/user-attachments/assets/e3914606-2bef-4606-bb7e-42a5162e32d2" />


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
