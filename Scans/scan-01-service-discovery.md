# Service Discovery Scan

## Objective

Identify active services running on the Ubuntu Server.

## Command Used

nmap -sV 192.168.100.20

## Parameter Explanation

-sV

Service Version Detection.

This option attempts to determine the version of services running on open ports.

## Results

22/tcp open ssh

3389/tcp open ms-wbt-server

## Findings

SSH service detected.

XRDP service detected.

## Security Analysis
<img width="1117" height="262" alt="image" src="https://github.com/user-attachments/assets/3a86ed0c-1e55-481c-82c1-6a168cb34192" />


The server exposes remote administration services.

These services should be protected with strong authentication and updated software versions.

## Recommendation

Disable unnecessary services.

Use strong passwords.

Apply security updates regularly.
