# AWS Linux Persistence Analysis Lab

## Overview
This lab demonstrates persistence analysis techniques on an AWS EC2 instance.

## What I Did
- Launched EC2 instance (Amazon Linux 2023)
- Connected using EC2 Instance Connect
- Investigated cron jobs and scheduled tasks
- Checked system service status (crond)

## Commands Used
Bash

crontab -l  
sudo ls -la /etc/cron*  
sudo systemctl status crond  

## Findings
- No user crontab entries found
- System cron directories exist
- crond service was installed but inactive

## Screenshots
See uploaded images in this repository.

## Skills Demonstrated
- AWS EC2
- Linux command line
- Basic persistence detection
