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
![image](https://github.com/subalakshmivenkat/ARP-Attack-and-Network-Sniffing/assets/119393477/51f118c7-982a-4349-a643-a803bec75f96)
From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:
![image](https://github.com/subalakshmivenkat/ARP-Attack-and-Network-Sniffing/assets/119393477/618312f0-1bcd-4a66-82ce-07d1bef15e4a)

## dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![image](https://github.com/subalakshmivenkat/ARP-Attack-and-Network-Sniffing/assets/119393477/51ef1fc4-123f-42b6-9b1f-170266d0f263)
In Kali issue the following commands:
sudo dsnifff

## OUTPUT:
![image](https://github.com/subalakshmivenkat/ARP-Attack-and-Network-Sniffing/assets/119393477/26a29b28-d71a-41de-bfd4-82df0c5fe308)
Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/subalakshmivenkat/ARP-Attack-and-Network-Sniffing/assets/119393477/3d6841a5-a076-4be0-8dea-f6450ea30def)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
