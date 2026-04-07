# BRG-ISEA LABS - Server Environments & Architecture
# Introduction
This project demonstrates the setup and configuration of a Linux server environment using cloud infrastructure. 
The lab covers virtual machine deployment, server management, scripting, automation and additional services.

## Session 1a: Setting up LINUX
### Ubuntu Installation
-Installed Ubuntu using virtual machine and explored basic Linux commands
### Basic Commands Practice
-pwd
-ls
-cd
-mkdir
-touch
Also explored Linux directory structure and manual pages.
### Screenshots
-Ubuntu
<img width="1512" height="982" alt="Screenshot 2026-04-08 at 2 48 10 AM" src="https://github.com/user-attachments/assets/9ee9da6b-3e88-4296-83c2-935bc83e4409" />
-Ubuntu Terminal
<img width="1512" height="982" alt="Screenshot 2026-04-08 at 2 48 32 AM" src="https://github.com/user-attachments/assets/101c5316-fd74-4d13-b7d1-0e79514a2deb" />
-Basic commands
<img width="1512" height="982" alt="screenshot1" src="https://github.com/user-attachments/assets/7c3c84ad-338d-40e4-a030-750a0231d422" />

## Session 2A - Total Cost of Ownership [TCO]
A comparison was conducted between on-premise infrastructure and cloud-based solutions. The analysis included hardware, maintenance, and operational costs over a 3-year period.
Results had showed that cloud computing is more cost-effective due to lower upfront costs and scalability.
### Screenshots
<img width="460" height="493" alt="Screenshot 2026-04-08 at 3 01 02 AM" src="https://github.com/user-attachments/assets/83a3417c-6995-4aba-9827-bb06bf79cdee" />
<img width="704" height="647" alt="Screenshot 2026-04-08 at 3 01 37 AM" src="https://github.com/user-attachments/assets/c3b0663e-4a2c-46bf-aab2-bea0f2d40b00" />

## Session 2B - Amazon Web Services EC2
An EC2 instance was launched using the Ubuntu Server. SSH access was configured using a key pair, allowing serure remote access to the server.
The server was updated and configured successfully.
### Screenshots
-EC2 running
<img width="1512" height="982" alt="Screenshot 2026-04-07 at 7 40 21 PM" src="https://github.com/user-attachments/assets/a7706065-c3a0-486c-b255-29a705622f1d" />
-SSH Terminal
<img width="1512" height="982" alt="Screenshot 2026-04-07 at 8 10 57 PM" src="https://github.com/user-attachments/assets/0a7d73c0-8983-46ac-bb29-ba35072bcd3d" />
-apt update
<img width="1512" height="982" alt="Screenshot 2026-04-08 at 3 26 17 AM" src="https://github.com/user-attachments/assets/8700e957-3f7e-459b-b67c-eb1b551d1cd7" />

## Bash Scripting
Multiple shell scripts to automate tasks were created and executed.
-Basic script to display system message and date
-Loop script to iterate through values
-Conditional script to check file existence
### Screenshots
-Script Output
-Loop Output
-If condition output
<img width="1512" height="982" alt="Screenshot 2026-04-07 at 8 15 29 PM" src="https://github.com/user-attachments/assets/e3e91405-3530-46d0-bab4-3d0d43dffbfd" />

## Automation with Cron
A cron job was configured to automate system updates daily. This demonstrates basic server automation capabilities.
### Screenshots
-crontab -e
-crontab -l
<img width="1512" height="982" alt="Screenshot 2026-04-08 at 2 11 03 AM" src="https://github.com/user-attachments/assets/fc09f3b7-44cb-40c5-9782-ced96176f73e" />

## DNS Configuration
DNS functionality was tested usingdig and nslookup commands. The server successfully resolved domain names, confirming proper DNS configuration.
-dig output
-nslookup output
<img width="1512" height="982" alt="Screenshot 2026-04-08 at 2 12 45 AM" src="https://github.com/user-attachments/assets/347577dd-482c-47c5-bde2-23ab89b01bcf" />

## Digital Certificates
Certbot was installed to manage SSL certificates. The installation was verified successfully.
### Screenshots
-certbot version
<img width="1512" height="982" alt="Screenshot 2026-04-08 at 2 14 40 AM" src="https://github.com/user-attachments/assets/0b86f6ce-8f4d-4cf3-9400-f036108aa9bb" />

## Docker
Docker was installed and tested by running a sample container. This demonstrates containerization capabilities in server environments.
### Screenshots
-docker version
<img width="1512" height="982" alt="Screenshot 2026-04-08 at 2 15 38 AM" src="https://github.com/user-attachments/assets/708a365a-97a7-4d38-bee5-1e9df8dae0c3" />
-hello-world output
<img width="1512" height="982" alt="Screenshot 2026-04-08 at 2 17 30 AM" src="https://github.com/user-attachments/assets/82055518-f5a0-4414-bc36-46573b77da92" />

## Reflection
This lab provided practical experience in server deployment and management.
Key challenges included SSH authentication issues, and permission errors, which were resolved through troubleshooting and correct configuration.
Through this lab, I gained hands-on experience in cloud computing, Linux administration, and automation.
These skills are highly relevantfor roles such as System Administrator and DevOps Engineers.
