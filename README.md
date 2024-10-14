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
![Screenshot 2024-04-07 184651](https://github.com/Rajeshanbu/ARP-Attack-and-Network-Sniffing/assets/118924713/f79b008f-1b89-40aa-b777-d99f2a10446e)
From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:

![4 2](https://github.com/Rajeshanbu/ARP-Attack-and-Network-Sniffing/assets/118924713/ba1076ae-2855-43f6-a1bc-01db536f9c15)

 dsniff:
 
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

![4 3](https://github.com/Rajeshanbu/ARP-Attack-and-Network-Sniffing/assets/118924713/48c0b4bd-6b2d-4a8e-8f8b-ea6f1609896d)

In Kali issue the following commands:

sudo dsnifff

## OUTPUT:

![4 4](https://github.com/Rajeshanbu/ARP-Attack-and-Network-Sniffing/assets/118924713/73b6ab84-8381-4dd1-b387-e6c9221f866c)

Invoke the wireshark and examine the various menus  and controls of the tool:

![4 5](https://github.com/Rajeshanbu/ARP-Attack-and-Network-Sniffing/assets/118924713/50f6ef76-2e81-457e-84c1-00bce85fb69a)


## RESULT:

The kali linux tools for ARP Attack and Network Sniffing were identified successfully
