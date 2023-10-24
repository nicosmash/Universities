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

For a better understanding, here is a network diagram:
![nat_network_sheme](https://github.com/nicosmash/Universities/assets/5543119/415b1e20-6f2b-42b9-81d5-fc1e56846a4f)

### Setup your environment ###
* **Create a NAT Network using VirtualBox GUI**

**1. Open VirtualBox Preferences (File -> Preferences) and go to Network Tab. <br> 
On some versions of virtualbox you must have to go to File -> Tools -> Network Manager**
![image](https://user-images.githubusercontent.com/5543119/164250582-571514ea-03b7-4854-8cb7-d7181ba461b4.png)

**2. Click on the + icon on right side (Adds new NAT network). It will create a new NAT Network without asking any questions.**
![image](https://user-images.githubusercontent.com/5543119/164250638-2b6537ec-66c0-4c2d-8d5c-1b727825588e.png)

**3. You can modify the Network Name, Network CIDR etc by clicking modify button (or double click the NAT Network).**
![image](https://user-images.githubusercontent.com/5543119/164250690-11ac866e-3d0d-49ee-947a-4dcb37ec46b7.png)

* **Use NAT Network for Virtual Machines**

**1. Once you have created NAT Network, assign the same for the VM Network.**
![image](https://user-images.githubusercontent.com/5543119/164250865-b3733244-6b80-441c-b52f-ae3e1b4b27a4.png)
