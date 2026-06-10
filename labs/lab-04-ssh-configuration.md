# Lab 04 - SSH Configuration

## Objective

Practice working with the Secure Shell (SSH) service used for secure remote Linux administration.

## Environment

- Host Operating System: Windows
- Virtualization Platform: Oracle VirtualBox
- Guest Operating System: Red Hat Enterprise Linux

## Tasks Completed

- Checked SSH service status
- Verified SSH was running
- Identified SSH network listening ports
- Tested SSH access locally
- Practiced basic Linux service management

## Commands Practiced

```bash
systemctl status sshd
ss -tulpn | grep ssh
ssh localhost
```

## Skills Demonstrated

- SSH Configuration
- Remote Administration
- Linux Service Management
- Network Service Verification
- Command-Line Troubleshooting
- Security Fundamentals

## Reflection

This lab introduced SSH, which is used to securely access and administer Linux systems remotely. Practicing SSH helped strengthen my understanding of Linux services, remote access, and network-based system administration.
