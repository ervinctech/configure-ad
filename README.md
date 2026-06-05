<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

# Configuring On-Premises Active Directory within Azure VMs

## Overview

This project demonstrates the deployment and configuration of an Active Directory environment using Microsoft Azure Virtual Machines. The lab includes creating a Domain Controller, configuring Active Directory Domain Services (AD DS), joining a client machine to the domain, and managing users and organizational units.

## Technologies Used

- Microsoft Azure
- Active Directory Domain Services (AD DS)
- Windows Server
- Windows 10
- Remote Desktop Protocol (RDP)

## Operating Systems Used

- Windows Server 2022
- Windows 10 Pro

## Skills Demonstrated

- Active Directory Administration
- User and Group Management
- Organizational Unit (OU) Configuration
- Domain Management
- DNS Configuration
- Azure Virtual Machines
- Remote Desktop Administration

## Lab Objectives

- Create Azure Virtual Machines
- Install Active Directory Domain Services
- Promote Server to Domain Controller
- Configure DNS
- Join Client Computer to Domain
- Create Users and Organizational Units
- Verify Domain Functionality

## Deployment Steps

### Step 1: Create Azure Virtual Machines

Created a Windows Server VM to function as the Domain Controller and a Windows 10 VM to function as a client workstation.

![image](INSERT_SCREENSHOT_HERE)

### Step 2: Install Active Directory Domain Services

Installed the AD DS role and promoted the server to a Domain Controller.

![image](INSERT_SCREENSHOT_HERE)

### Step 3: Configure DNS

Verified DNS settings and ensured the client machine could locate the Domain Controller.

![image](INSERT_SCREENSHOT_HERE)

### Step 4: Join Client Computer to Domain

Joined the Windows 10 client machine to the newly created domain.

![image](INSERT_SCREENSHOT_HERE)

### Step 5: Create Organizational Units

Created Organizational Units to organize users and administrative resources.

![image](INSERT_SCREENSHOT_HERE)

### Step 6: Create User Accounts

Created test users and assigned them to appropriate Organizational Units.

![image](INSERT_SCREENSHOT_HERE)

### Step 7: Verify Authentication

Verified domain login functionality using newly created user accounts.

![image](INSERT_SCREENSHOT_HERE)

## What I Learned

- How Active Directory manages users and resources within a domain environment.
- The role DNS plays in Active Directory functionality.
- How to create and manage Organizational Units and user accounts.
- Basic Windows Server administration within Azure.
