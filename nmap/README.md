## Objective
Host discovery,port scaning,service enumeration.

## Commands Used
nmap -sS -Pn -A 10.40.93.78 : SYN-half,host discovery,port discovery.

## Discovery
SSH - Port 22
rtsp - Port 5000
Apple MacOS 11 - OS

## Analysis
Early enumeration and aim for direcrt connection and find potencial 
entrypoint.
for this session we got the ssh,but we need more credential,so with that 
try to pivot and search http (port 80).
