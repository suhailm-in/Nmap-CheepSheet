# Nmap-CheepSheet

---
<h1>Basic Nmap Scans:

### Basic Scans:
```
nmap target_ip
```
### Scan specific ports:
```
nmap -p port_number target_ip
```
### Scan multiple hosts:
```
nmap target1 target2 target3
```
### Scan a range of IP addresses:
```
nmap target_ip_range
```
### Scan a subnet:
```
nmap target_subnet/mask
```  

---
<h1>Scan Techniques:

### TCP SYN scan (default):
```
nmap -sS target_ip
```  
### TCP Connect scan:
```
nmap -sT target_ip
```  
### UDP scan:
```
nmap -sU target_ip
```  
### TCP ACK scan:
```
nmap -sA target_ip
```  
### TCP Window scan:
```
nmap -sW target_ip
```  
### IP protocol scan:
```
nmap -sO target_ip
```  

---
<h1>Advanced Scans:
  
### Operating System detection:
```
nmap -O target_ip
```  
### Service version detection:
```
nmap -sV target_ip
```  
### Aggressive mode:
```
nmap -A target_ip
```  
### Common vulnerabilities:
```
nmap --script vuln target_ip
```  
### Script scan:
```
nmap --script script_name target_ip
```  
### Script category scan:
```
nmap --script category_name target_ip
```  
### Script scan with arguments: 
```
nmap --script script_name --script-args argument_name=argument_value target_ip
```  
### Script category scan with arguments:
```
nmap --script category_name --script-args argument_name=argument_value target_ip
```  
### UDP DNS amplification scan:
```
nmap --script dns-recursion target_ip
```  
  
---
<h1>Additional Options:
  
### Skip host discovery:
```
nmap -Pn target_ip
```  
### Save output to a file:
```
nmap -oN output.txt target_ip
```  
### Specific network interface:
```
nmap -e interface_name target_ip
```  
### Show packet traces:
```
nmap --packet-trace target_ip
```  
### Disable DNS resolution:
```
nmap -n target_ip
```  
### Verbose output:
```
nmap -v target_ip
```  
### Proxy:
```
nmap --proxy socks4://proxy_host:port target_ip
```  
 
- Remember to replace target_ip, port_number, target_ip_range, target_subnet/mask, script_name, category_name, interface_name, argument_name, and argument_value with the appropriate values for your specific use case.  
   

 
