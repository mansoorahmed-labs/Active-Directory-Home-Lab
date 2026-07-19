# Troubleshooting Guide

This document contains issues encountered during the Active Directory Home Lab and the steps taken to resolve them.

---

## Issue 1

Windows 10 could not join the domain.

### Cause

Incorrect DNS configuration.

### Resolution

Verified the network configuration.

Configured the correct DNS server and retried joining the domain.

The Windows client successfully joined the domain.

---

## Issue 2

Unable to log in with the newly created domain user.

### Cause

The user account had not been created correctly.

### Resolution

Verified the user inside Active Directory Users and Computers.

Recreated the user and successfully logged in.

---

## Issue 3

Network connectivity issues.

### Cause

Incorrect IP configuration.

### Resolution

Verified:

- IP Address
- Subnet Mask
- Gateway
- DNS

Confirmed connectivity using:

ping 8.8.8.8

---

## Issue 4

Active Directory objects not appearing.

### Cause

The Organizational Unit or user was created in the wrong container.

### Resolution

Verified the correct Organizational Unit.

Moved the objects to the appropriate OU.

---

## Issue 5

Linux User Management (Kali Linux)

While working in the lab, I attempted to create and delete Linux users.

Errors encountered:

- adduser syntax error
- user does not exist

Resolution:

Reviewed the command syntax and successfully managed Linux user accounts.

This issue was unrelated to Active Directory but improved my Linux administration skills.

---

## Lessons Learned

- Active Directory deployment
- Windows Server administration
- DNS configuration
- DHCP configuration
- User management
- Organizational Units
- Domain joining
- Network troubleshooting
- VMware virtualization
- Basic Linux administration
