# AWS EC2 Web Deployment

This is a small DevOps practice project where I deployed a static website on an AWS EC2
instance using Ubuntu and Nginx.  
I built this project to understand how real server deployment works instead of just
learning theory.

## What this project does
- Hosts a simple static website
- Runs on an AWS EC2 Ubuntu server
- Uses Nginx as the web server

## What I actually worked on
- Launched an EC2 instance (free tier)
- Connected to the server using SSH keys from WSL Ubuntu
- Configured security group rules for SSH and HTTP
- Installed and started Nginx
- Placed the website files in the server directory
- Faced SSH permission issues and fixed them by correcting user access
- Used Git to push the project to GitHub

## Tools used
- AWS EC2
- Ubuntu Linux
- Nginx
- Git and GitHub
- SSH
