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
<img width="962" height="1151" alt="Windows Exp 4" src="https://github.com/user-attachments/assets/88130975-ab49-4a64-b5a8-6bb1308378e0" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="772" height="373" alt="kali Linux Exp 4" src="https://github.com/user-attachments/assets/ee241c20-6107-4e0f-9490-3fe022580ded" />

 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="1036" height="435" alt="Metasploit Dsniff Exp 4" src="https://github.com/user-attachments/assets/35202362-b55f-4fc0-9b88-8985de5b778b" />

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="955" height="152" alt="Dsniff Exp 4" src="https://github.com/user-attachments/assets/43324230-4243-47d5-840a-32f5de1705b9" />

Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1032" height="430" alt="Wireshark Exp 4" src="https://github.com/user-attachments/assets/ccbb2e1a-56f9-468a-a259-f7982daf3e5e" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
