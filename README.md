# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

#### NAME: RAMESH KRISHNAN
#### REG NO: 212224220076

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


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
dsnifff
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
In Kali issue the following commands:
sudo dsnifff

### Step1: Open the ettercap-pkexec in Kali
<img width="1920" height="944" alt="exp4-1" src="https://github.com/user-attachments/assets/fc6dcaf0-3d25-45a2-bc54-d3dec8c48b27" />

### Step2: Add Target 1 Host
<img width="1920" height="945" alt="exp4-2" src="https://github.com/user-attachments/assets/2e13f1c0-f44a-4903-aa0d-01143852bf09" />

### Step3: Add Target 2 Host
<img width="1920" height="943" alt="exp4-3" src="https://github.com/user-attachments/assets/b1a1ea24-75cd-49c0-8792-df8ed7dde24e" />

### Step4: Select ARP poisoning...
<img width="1920" height="945" alt="exp4-4" src="https://github.com/user-attachments/assets/40c40345-d599-446e-bb8a-2b402e17d08c" />

### Step5: Click OK on ARP poisoning... confirmation message
<img width="1920" height="942" alt="exp4-5" src="https://github.com/user-attachments/assets/a84d7e70-c5f0-49b9-9117-5798f332925e" />

### Step6: ARP poisoning victims
<img width="1920" height="939" alt="exp4-6" src="https://github.com/user-attachments/assets/4ecc21fe-58cd-42df-bb53-6ce83419df03" />

Invoke the wireshark and examine the various menus  and controls of the tool:

### Step7: Open Wireshark and click ethO
<img width="1920" height="937" alt="exp4-7" src="https://github.com/user-attachments/assets/a7b79486-c742-4af8-a8d9-ed42a4dbdd15" />

### Step8: Duplicate use is detected
<img width="1920" height="868" alt="exp4-8" src="https://github.com/user-attachments/assets/f1d42242-6efb-433d-a32e-8ef3d77ed5e9" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
