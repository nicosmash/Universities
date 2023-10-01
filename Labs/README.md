## 📢 Virtual Lab :
### Labs ###

* **Instruction for your report**
    * Present each lab on your report with everything you did during the lab (with what worked and with what didn't work).
    * For each lab :
        - find target IP address;
        - list all open ports;
        - list all services and version;
        - explain everything you do.

| VM number  | Difficulty |  Licence |  Master |  Targets |  Tags |  Link |
| :---: | :---: | :---: | :---: | ------------- | ------------- | ------------- |
| 207  | Easy  | x  | x  |  find 8 vulnerabilities flags beginning by "FLAG{". <br> For each flag found, write on your report "FLAG_x :"  | NA  | https://www.vulnhub.com/entry/rickdiculouslyeasy-1,207/  |
| 710  | Medium  | -  | x  | gain access, root  | Reconnaissance, exploit, privilege escalation  | https://www.vulnhub.com/entry/vulncms-1,710/  |
| 216  | Medium  | x  | x  | webadmin, gain access, root  | Reconnaissance, brute force, exploit, web, privilege escalation  | https://www.vulnhub.com/entry/basic-pentesting-1,216/  |
| 80  | Medium  | -  | x  | gain access, root  | Reconnaissance, SQLi, exploit  | https://www.vulnhub.com/entry/pentester-lab-from-sql-injection-to-shell,80/  |
| 546  | Hard  | -  | x  | webadmin, gain access, root  | Reconnaissance, brute force, exploit, web, privilege escalation  | https://www.vulnhub.com/entry/funbox-ctf,546/  |

## 📢 VirtualBox
### Download and Install VirtualBox ###

* **Download the latest version of VirtualBox: https://www.virtualbox.org/wiki/Downloads**
    * If you want you can use other virtualization tools like VMware Fusion, VMware Player, VMware Workstation, etc. but without assurance that everything works. 
Many tests were carried out on VirtualBox.

* **Download the latest version of Kali: https://www.kali.org/get-kali/#kali-virtual-machines**
    * username: **kali**
    * password: **kali**
    * I recommand you a "NAT Network" for all VM labs and Kali machines with a specific name and a specific IP range. 
    * To change QWERTY in AZERTY you can use "setxkbmap fr" (volatile config) or "sudo dpkg-reconfigure keyboard-configuration" (non-volatile config).

### Setup your environment ###
* **Create a NAT Network using VirtualBox GUI**

**1. Open VirtualBox Preferences (File -> Preferences) and go to Network Tab.**
![image](https://user-images.githubusercontent.com/5543119/164250582-571514ea-03b7-4854-8cb7-d7181ba461b4.png)

**2. Click on the + icon on right side (Adds new NAT network). It will create a new NAT Network without asking any questions.**
![image](https://user-images.githubusercontent.com/5543119/164250638-2b6537ec-66c0-4c2d-8d5c-1b727825588e.png)

**3. You can modify the Network Name, Network CIDR etc by clicking modify button (or double click the NAT Network).**
![image](https://user-images.githubusercontent.com/5543119/164250690-11ac866e-3d0d-49ee-947a-4dcb37ec46b7.png)

* **Use NAT Network for Virtual Machines**

**1. Once you have created NAT Network, assign the same for the VM Network.**
![image](https://user-images.githubusercontent.com/5543119/164250865-b3733244-6b80-441c-b52f-ae3e1b4b27a4.png)

## 📢 Kali
### Download and Install Kali ###
* **Download the latest version of Kali: https://www.kali.org/get-kali/#kali-virtual-machines**
    * username: **kali**
    * password: **kali**
    * To change QWERTY in AZERTY you can use "setxkbmap fr" (volatile config) or "sudo dpkg-reconfigure keyboard-configuration" (non-volatile config).
