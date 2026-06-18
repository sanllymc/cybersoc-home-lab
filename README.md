# CyberSOC Home Lab

## Project Overview

This project documents the creation of a cybersecurity laboratory using PNETLab, Kali Linux and Ubuntu Server.

The purpose of the lab is to practice network reconnaissance, service enumeration, security analysis and documentation techniques commonly used by cybersecurity analysts.

## Lab Architecture

### Attacker

* Kali Linux
* IP Address: 192.168.100.10

### Target

* Ubuntu Server 18.04
* IP Address: 192.168.100.20

## Tools Used

* PNETLab
* Kali Linux
* Ubuntu Server
* Nmap

## Activities Completed

### Network Configuration

Static IP addresses were manually assigned to establish connectivity between hosts.

### Service Discovery

Command:

nmap -sV 192.168.100.20

Results:

* SSH (22/tcp)
* XRDP (3389/tcp)

### Advanced Reconnaissance

Command:

nmap -A 192.168.100.20

Information gathered:

* Operating System Detection
* Service Versions
* SSH Host Keys
* Traceroute Information

## Lessons Learned

* Building a cybersecurity lab
* Troubleshooting network connectivity
* Service enumeration using Nmap
* Security documentation practices

## Author

Sanlly Mora
Cybersecurity Student

