# Recon Scripts

This repository contains Bash scripts for reconnaissance and automating purposes.

## 1. pingsweep.sh
   - This script performs a ping sweep on the provided IP address range to identify active hosts. It sends ICMP echo requests to each IP address in the range and captures responses to determine which hosts are reachable.

**Usage:**
```bash
./pingsweep.sh <IP_Address>
```

## 2. recon.sh
   - This script automates various reconnaissance tasks for a specified domain. It performs the following actions:
   - Retrieves WHOIS information for the domain.
   - Utilizes subdomain enumeration tools such as Subfinder and Assetfinder to discover subdomains.
   - Checks the availability of discovered subdomains using httprobe.
   - Takes screenshots of live subdomains using Gowitness.

**Usage:**
```bash
./recon.sh <Domain_Name>
```

## Instructions for Use:

1. Clone the repository:
```bash
git clone <repository_url>
```
2. Make the scripts executable:
```bash
chmod +x *.sh
```
3. Execute the desired script with appropriate arguments.

## Disclaimer:

These scripts are provided for educational and informational purposes only. Use them responsibly and ensure compliance with applicable laws and regulations.

