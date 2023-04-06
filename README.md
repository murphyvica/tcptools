# tcptools

## PING Questions:

### What were the min/avg/max/stddev statistics for each?

Amazon Mins: 3, 1, 2
Amazon Maxs: 5, 24, 5
Amazon Avgs: 4, 10, 5

Google Mins: 2, 2, 3
Google Maxs: 16, 7, 11
Google Avgs: 5, 3, 6

Microsoft Mins: 3, 2, 2
Microsoft Maxs: 33, 15, 54
Microsoft Avgs: 11, 4, 12

### Was there any packet loss on any of the pings?

There was no loss of packets for any of the pings

### Did the IP address change for a given website between pings?

For some of the pings the IP did change, specifically for the Amazon one. The other addresses had not changed. Additionally, for the Amazon pings, the name sometimes changed but the IP address remained the same.

## TRACERT Questions:

### What was the target server's IP address?

Amazon: 18.172.169.208
Google: 142.250.217.68
Microsoft: 23.216.81.152

### How many hops were needed to reach the target?

Amazon: 14
Google: 10
Microsoft: 11

### Can you identify your ISP from the intermediate server DNS names?

Yes, from the lines such as: irb--2523.uwir-ads-1.infra.washington.edu [10.18.0.2], I know that my ISP is coming from UW. This appears in every Tracert command.

### Identify the "class" of IP address for each major step in the trip

UW Network:
10: Class A

PNW Gigapop:
209: Class C

Amazon Network:
18: Class A

Google Network:
142: Class B

Akamai Technologies (Microsoft Network):
23: Class A
