# Installation Guide

## Project Overview

This project demonstrates the deployment of a Windows Active Directory Home Lab using VMware Workstation.

## Lab Environment

- VMware Workstation
- Windows Server 2022
- Windows 10 x64
- Kali Linux
- Splunk
- Metasploitable2 Linux

## Software Used

- VMware Workstation
- Windows Server 2022 Evaluation
- Windows 10
- Active Directory Domain Services (AD DS)
- DNS Server
- DHCP Server
- Splunk Universal Forwarder

## Installation Steps

### Step 1

Created a Windows Server 2022 virtual machine in VMware.

### Step 2

Installed Windows Server 2022 Standard Evaluation.

### Step 3

Configured networking.

### Step 4

Assigned a static IP address to the Domain Controller.

Example:

IP Address:
192.168.10.7

Subnet Mask:
255.255.255.0

Gateway:
192.168.10.1

DNS:
8.8.8.8 (initial setup)

### Step 5

Installed the following Windows Server Roles:

- Active Directory Domain Services
- DNS Server
- DHCP Server

### Step 6

Promoted the server to a Domain Controller.

Domain Name:

ezio.local

### Step 7

Restarted the server after promotion.

### Step 8

Verified Active Directory installation using Server Manager.
