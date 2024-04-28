# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode
- `Step 2:` Investigate on the various categories of tools as follows.
-  `Step 3:` Open terminal and try execute some kali linux commands

### DEVELOPED BY : MOHAMED AZEEM N
### REGISTER NO : 212222110026
## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.

In windows 7 give the command:
```
arp -a
```
## OUTPUT:

![4 1](https://github.com/SaiPraneeth04/ARP-Attack-and-Network-Sniffing/assets/119390353/7ddd1bd0-9540-4ada-8ece-f7001d66aa80)



From kali linux issue the command :
```
sudo arpspoof -i eth0 -t <target system> <gateway>
```
## OUTPUT:

![4 2](https://github.com/SaiPraneeth04/ARP-Attack-and-Network-Sniffing/assets/119390353/2cfa0b8f-08b4-4bd6-b83b-f54e23e9916b)



 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
 
## OUTPUT:

![4 3](https://github.com/SaiPraneeth04/ARP-Attack-and-Network-Sniffing/assets/119390353/e5cf16b9-e847-4299-9ec2-c34ff46b563d)


In Kali issue the following commands:
```
sudo dsnifff
```
## OUTPUT:

![4 4](https://github.com/SaiPraneeth04/ARP-Attack-and-Network-Sniffing/assets/119390353/78cd5f5c-0c18-47f4-8d92-c6896215380d)


Invoke the wireshark and examine the various menus  and controls of the tool:

![4 5](https://github.com/SaiPraneeth04/ARP-Attack-and-Network-Sniffing/assets/119390353/cbbdfbe5-9cb9-4e33-a3e3-46d79cf78062)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
