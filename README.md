# Cisco Configuration Backup to FTP Server

## Overview

This project demonstrates how to back up Cisco network device configurations to a centralized FTP server using Cisco Packet Tracer.

The objective was to ensure configuration availability and facilitate disaster recovery by storing device configurations on a dedicated FTP server.

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- FTP Server
- TCP/IP

## Features

- FTP server deployment
- FTP user creation
- Connectivity testing
- Router configuration backup
- Centralized storage of configuration files

## Skills Demonstrated

- Network Administration
- Cisco IOS Configuration
- FTP Service Management
- Backup and Recovery
- Network Troubleshooting

## Project Architecture

```text
Cisco Router
      │
      │ FTP Transfer
      ▼
FTP Server
      │
      ▼
Configuration Backups
```

## Configuration Process

### Step 1 - Configure FTP Server

Create an FTP user account and enable FTP services.

### Step 2 - Verify Connectivity

Test network communication between the router and the FTP server.

### Step 3 - Execute Backup

Save the running configuration to the FTP server.

## Backup Command

```bash
copy running-config ftp://ADMIN:Cisco@10.0.60.2/backup.cfg
```

## Screenshots

### FTP User Configuration

![FTP User Configuration](ftp-user-configuration.png)

### Connectivity Test

![Connectivity Test](connectivity-test.png)

### Configuration Backup

![Configuration Backup](configuration-backup.png)

## Project Outcome

Successfully implemented a centralized backup solution allowing Cisco device configurations to be stored and recovered from an FTP server.
