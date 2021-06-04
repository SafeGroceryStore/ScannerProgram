# ScannerProgram
Use
```
Usage: Scanner [-h Help] [-i IP/CIDR] [-f IpsFile] [-p Ports] [-n Threads] [-o Output] [-t Timeout] [-m ScanType] [-v ShowInfo]
Tscan Default Port -> 80,81,82,88,89,1080,4430,4433,7001,7002,8000,8001,8002,8009,8182,8161,8080,8081,8082,8090,8443,8880,8888,9000,9090,9043,9060,9200,9080,9875,9999
Pscan Default Port -> 22,80,81,82,88,89,135,137,138,139,389,443,445,1024,1080,1433,1521,3128,3306,3308,3389,4430,4433,4560,5432,5800,5900,5985,5986,6379,6588,6868,7001,7002,8000,8001,8002,8009,8182,8161,8080,8081,8082,8090,8443,8880,8888,9000,9090,9043,9060,9200,9080,9875,9999

Options:
  -h    Print the help page.
  -i    Targets, Single IP or CIDR or RangeIP. Ex: 192.168.2.1 or 192.168.2.0/24 or 192.168.1.1-192.168.1.100
  -f    Targets   , Single IP or CIDR or RangeIP
  -p    Port ranges. Ex: 1-65535 or 80,443 or 80,443,100-110
  -n    The Number of Goroutine, too large value is not recommended. (Default is 30)
  -o    Output file path. Ex: /tmp/result.txt or C:\Windows\Temp\result.txt
  -m    Scan Type. Ex: pscan or tscan or nbscan or 17scan
  -t    Scan Timeout. (Default is 5s)
  -v    Show Runlog. (Default is false)
```
# Referer
```
https://github.com/loong716/PortScan
```
