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
![Screenshot 2025-05-02 131546](https://github.com/user-attachments/assets/ff37bf92-ca3e-48f8-85f7-487d590e1c9a)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2025-05-02 132553](https://github.com/user-attachments/assets/ba53c0be-9973-4942-afd7-14edfd24a742)



 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![WhatsApp Image 2025-05-02 at 14 07 11_714db38b](https://github.com/user-attachments/assets/b3b8ff13-422a-46ea-928b-5b0c377f3710)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2025-05-02 133427](https://github.com/user-attachments/assets/c75477d6-82a8-49fa-9813-582bfde03069)


Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2025-05-02 133639](https://github.com/user-attachments/assets/eb36eb6c-386b-4fc1-8cd2-2ff860179f91)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
