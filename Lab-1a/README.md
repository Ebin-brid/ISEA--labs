# Lab 1a – Virtualisation and Linux Setup

## Objective

The objective of this lab was to set up Ubuntu Linux using VirtualBox and become familiar with running Linux in a virtual machine.

## Activities Completed

### 1. Installed VirtualBox
Installed Oracle VirtualBox on the host Windows computer.

### 2. Downloaded Ubuntu ISO
Downloaded the Ubuntu ISO image for installation.

### 3. Created Ubuntu Virtual Machine
Created a new Ubuntu virtual machine in VirtualBox and configured the virtual machine resources.

### 4. Installed Ubuntu
Booted the virtual machine using the Ubuntu ISO and completed the Ubuntu installation.

### 5. Configured Network
Configured the virtual machine network using NAT mode.

### 6. Verified Ubuntu
Started Ubuntu successfully and verified that the Ubuntu desktop and Terminal were working.

### 7. Installed Guest Additions
Installed the VirtualBox Guest Additions packages inside Ubuntu.

Command used:

sudo apt install virtualbox-guest-utils virtualbox-guest-x11

### 8. Enabled SSH
Installed and enabled the SSH server.

Command used:

sudo apt install openssh-server

Checked the SSH service using:

systemctl status ssh

## What I Learned

I learned how virtualization allows an operating system such as Ubuntu Linux to run inside a virtual machine. I also learned how to configure a VM, install Ubuntu, configure networking and use the Linux Terminal.

## Reflection

The main part of the lab was setting up the Ubuntu virtual machine and making sure the network and required services were working. This gave me a basic environment for completing the other Linux server labs.

## Evidence / Screenshots

### 1. VirtualBox Installation
<img width="1919" height="1070" alt="image" src="https://github.com/user-attachments/assets/35d084be-1e50-4374-87bd-d98f23e8d67c" />


### 2. Ubuntu ISO
![Ubuntu ISO](02-ubuntu-iso.png)

### 3. Virtual Machine Configuration
![VM Configuration](03-vm-configuration.png)

### 4. Ubuntu Running
![Ubuntu](04-ubuntu-running.png)

### 5. Network Configuration
![NAT Network](05-network-nat.png)

### 6. Guest Additions
![Guest Additions](06-guest-additions.png)

### 7. SSH Installation
![SSH Installation](07-ssh-installation.png)

### 8. SSH Status
![SSH Status](08-ssh-status.png)
