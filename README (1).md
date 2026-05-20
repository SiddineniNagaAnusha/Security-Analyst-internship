# Basic Network Scanning with Nmap

## Objective
Perform a basic network scan using Nmap to identify open ports and services.

## Tool Used
- Nmap

## Commands Used
nmap 127.0.0.1  
nmap -sV 127.0.0.1  

## Results

- Port 135 → MSRPC (Windows RPC service)
- Port 445 → SMB (File sharing service)
- Port 3306 → MySQL (Database service)

## Conclusion
The scan successfully identified active services running on the local system.