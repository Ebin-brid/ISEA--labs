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
<img width="1282" height="878" alt="image" src="https://github.com/user-attachments/assets/210d989c-1fe2-4a63-a016-5ac238185316" />
<img width="890" height="109" alt="image" src="https://github.com/user-attachments/assets/6ab7ea60-e131-414d-94a8-8084e7bae515" />
<img width="685" height="59" alt="image" src="https://github.com/user-attachments/assets/357bb3aa-0834-44b6-98b4-4576e9f1bdb8" />




### 3. Virtual Machine Configuration
<img width="764" height="879" alt="image" src="https://github.com/user-attachments/assets/69df9370-cc0b-41a7-a783-ea4705713602" />

##4.Familiarity with Ubuntu Linux – Basic command line navigation and utilities
<img width="826" height="403" alt="image" src="https://github.com/user-attachments/assets/6c6eb51e-5c18-4222-81aa-f574b660ffb1" />

Understand directory structure (`/etc`, `/var`, `/home`).
<img width="1082" height="588" alt="image" src="https://github.com/user-attachments/assets/a80dc237-f316-40fc-845c-34c5cfa8d450" />

 Use `man` to explore Linux manual pages.
 ![Uploading image.png…]()
 

