# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system

## OUTPUT:

<img width="984" height="603" alt="image" src="https://github.com/user-attachments/assets/4bd6df20-5be7-4bf1-92f4-836c8accd0bf" />


## Invoke msfconsole

## OUTPUT:

<img width="946" height="824" alt="image" src="https://github.com/user-attachments/assets/013661cf-ec9f-44cb-bde4-db09eb93e4e2" />

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.

<img width="880" height="794" alt="image" src="https://github.com/user-attachments/assets/6ffb10cb-202b-4a23-b24b-b405f210a1eb" />

## Port scanning:

### msf > nmap -sT 192.168.1810/24-p1-1000

<img width="879" height="613" alt="image" src="https://github.com/user-attachments/assets/9def5485-7264-4e20-8f42-71304713830e" />


### msf > db_nmap 192.168.181.0/24

<img width="940" height="497" alt="image" src="https://github.com/user-attachments/assets/15403370-8c1e-4a8e-83e9-78762f29834d" />

### kali > ls-l

<img width="784" height="148" alt="image" src="https://github.com/user-attachments/assets/9f6fe497-d2a6-48a0-bea0-b3ff77c6932e" />

### msf >search name:Microsoft type:exploit

<img width="1484" height="801" alt="image" src="https://github.com/user-attachments/assets/979466e1-cdd4-4677-85bd-bc4e8b76690b" />

## MYSQL ENUMERATION

### db_nmap -sV -sC -p 3306 <metasploitable_ip_address>

<img width="940" height="497" alt="image" src="https://github.com/user-attachments/assets/348300d5-529c-454e-8d72-c7c6ff85a042" />

### search type:auxiliary mysql

<img width="1663" height="600" alt="image" src="https://github.com/user-attachments/assets/66ad62b7-2ccc-43dc-80d4-de8824922cd1" />

###  use 11 Or: use auxiliary/scanner/mysql/mysql_version

<img width="1465" height="449" alt="image" src="https://github.com/user-attachments/assets/22ddf3e4-deb4-49f9-8b57-453247b216f1" />

### Use the set rhosts command to set the parameter and run the module, as follows:

<img width="712" height="109" alt="image" src="https://github.com/user-attachments/assets/2925b554-7417-4820-9a8c-689e0e6bff70" />

### After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.

<img width="1640" height="624" alt="image" src="https://github.com/user-attachments/assets/6f75cd86-786e-4cc3-bcef-7d1f5b9e2ad9" />

### /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt 
<img width="874" height="268" alt="image" src="https://github.com/user-attachments/assets/8cbcaffa-d5bb-445a-9604-ae3a3ab67310" />


## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
