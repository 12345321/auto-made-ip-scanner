# auto-made-ip-scanner
#!/bin/bash

read -p 'tell the ip   '  ip
echo "scanning $ip  " 
nmap $ip 

