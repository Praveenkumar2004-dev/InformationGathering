# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/e7c05092-eb40-42d1-816d-8f5642469b9e)
## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```

## Output:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/4a301fe9-ed60-4dfe-9417-cba5549793c4)

## Finding Hosting Company:
get further detail by using ip2location.com website.
## output:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/d9bd2d30-4032-48f2-8496-039da0f3d7d8)

## History of the website:
## Output:

https://web.archive.org/

![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/4918dd3d-707a-400e-8eec-a59dc82c121e)
## Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/9ca3229a-b27e-4b0b-9cdf-0877f78f4b0d)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/1d2052d2-4d81-4ea3-b360-da9502e6df1d)
## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/e4b8e62e-2e83-4183-8a54-03d3e401a616)
## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/09012147-0f51-415b-8d52-2117d1d06dfa)
## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/074f675c-6849-4925-931f-1fc8ba9a3c70)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/46e58b45-6500-4b50-8497-3095dc40a698)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/InformationGathering/assets/119644432/9027287e-dac6-436e-8cf4-9c520cfdb346)
















## RESULT:
The information gathering techniques tools/procedure were  identified successfully
