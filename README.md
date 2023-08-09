# DNS-attacks
Sends 15,000 DNS QPS for 30 seconds to the host using the following syntax
```bash
dnsperf -s 10.1.10.6 -d example.com -b 8192000 -c 20 -t 30 -T 20 -l 30 -q 1000000 -Q 15000
```
