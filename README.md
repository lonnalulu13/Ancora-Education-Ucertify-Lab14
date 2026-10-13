# Ancora-Education-Ucertify-Lab14
# Creating a VLAM and Viewing its Assignment to Port Mapping

> **Original Lab Source**
> This lab was available through:
[https://ancoraeducation.ucertify.com/app/func=navigate_items&item_sequence=5]

## Objective of the Lab
In this lab, you will learn to create a VLAN (Virtual Local Area Networks) and view its assignment to port mapping. VLANs are logical subdivisions of a switch that segregate ports from one another as if they were in different LANs. VLANs offer another way to add a layer of separation between sensitive devices and the rest of the network.

## Instructions
### STEP 1
From the left sidebar, click the PuTTY SSH Client icon.

### Note
PuTTY is a software terminal emulator that provides a text user interface to remote computers running any of its supported protocols, including SSH and Telnet.

### STEP 2
In the PuTTY Configuration dialog box, perform the following steps: 

a. Type Host Name (or IP address) as 192.168.116.128 

b. Type Port as 5016 

c. Under Connection type, select the Other radio button. 

d. Click Open to connect

### STEP 3
If you don't get a command line prompt in the terminal window, then press Enter.

### STEP 4
In the IOU1 terminal window, execute the following commands to enter into configuration mode and configure a VLAN (Note: Execute one command at a time.):
```bash
configure terminal
```
```bash
vlan 10
```
```bash
name ucertify
```
```bash
vlan 20
```
```bash
name phone
```
```bash
end
```

### STEP 5
In the IOU1 terminal window, execute the following command into enable mode to view VLAN assignment to port mapping:
```bash
show vlan
```
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
