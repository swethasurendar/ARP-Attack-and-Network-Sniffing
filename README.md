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
![image](https://github.com/sachinezhilmaran/ARP-Attack-and-Network-Sniffing/assets/128135351/968d6dd7-1455-4312-9b00-e4db6e39a129)
From kali linux issue the command : sudo arpspoof -i eth0 -t
# OUTPUT:
![image](https://github.com/sachinezhilmaran/ARP-Attack-and-Network-Sniffing/assets/128135351/ee3dc26a-438a-4d83-b7c2-0e27fe1c51e0)
dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

# OUTPUT:
![image](https://github.com/sachinezhilmaran/ARP-Attack-and-Network-Sniffing/assets/128135351/56999a83-03fd-4cb0-8d75-c606a8cc0588)
In Kali issue the following commands: sudo dsnifff

# OUTPUT:
![image](https://github.com/sachinezhilmaran/ARP-Attack-and-Network-Sniffing/assets/128135351/8318dd2f-b75a-4a53-a54a-9047485aa2ba)
Invoke the wireshark and examine the various menus and controls of the tool:
![image](https://github.com/sachinezhilmaran/ARP-Attack-and-Network-Sniffing/assets/128135351/b4d2d011-1200-4852-89ca-2819394a0a21)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
