# ScannerProgram
Use
```
Usage: Scanner [-h Help] [-i IP/CIDR] [-p Ports] [-n Threads] [-o Output] [-t Timeout] [-m ScanType] [-v ShowInfo]
Tscan Default Port -> 80-89,443,7001,7002,8000-9999,18000-19999
Pscan Default Port -> 21,22,23,25,53,80,389,443,445,873,1025,1080,1099,1433,1521,3306,3389,5432,5800,5900,6379,7001,7002,8000,8001,8080,8081,8888,9200,9300,9080,9090,11211,27017,27018

Options:
  -h    Print the help page.
  -i    Targets, Single IP or CIDR or RangeIP. Ex: 192.168.2.1 or 192.168.2.0/24 or 192.168.1.1-10
  -p    Port ranges. Ex: 1-65535 or 80,443 or 80,443,100-110
  -n    The Number of Goroutine, too large value is not recommended. (Default is 200)
  -o    Output file path. Ex: /tmp/result.txt or C:\Windows\Temp\result.txt
  -m    Scan Type. Ex: pscan or tscan or nbscan or 17scan
  -t    Scan Timeout. (Default is 3s)
  -v    Show Runlog. (Default is false)


```
# Referer
```
https://github.com/loong716/PortScan
```
