## DNS Lookup

### Dig tool Website Version

Google Tool on Website       →          https://toolbox.googleapps.com/apps/dig/

Google DNS Record Search     →          https://dns.google/query

                  ViewDNS    →          https://viewdns.info/dnsreport/

                             →          https://hexillion.com/co/

                             →          http://en.dnstools.ch/dns-nameserver.html

                             →          http://www.ultratools.com/tools/dnsLookup

---

**See the ISP of the target IP to know and have an idea about the hosting wither it is self hosting or other hosting (VPS/Shared, etc.)**

                             →          https://www.iplocation.net/

---

### ASN Number

An **ASN (Autonomous System Number)** is a unique identifier assigned to an **Autonomous System (AS)**, which is a collection of IP networks under the control of a single organization or entity that follows a unified routing policy. ASNs are used in Border Gateway Protocol (BGP) to facilitate routing decisions between different autonomous systems on the internet.

**→ ANS Number gives the range of IPs of ISP**

### ASN Lookup

→         https://hackertarget.com/as-ip-lookup/

→         https://mxtoolbox.com/asn.aspx

→         https://dnschecker.org/asn-whois-lookup.php

---

# IP Address Traceroute

## # traceroute

The traceroute command is used to track the path that packets take from your computer to a target destination

‘ * ’ in the output means the server has got the request for asking the nodes but not replied to the request.

```bash
# traceroute 150.129.144.226
```

For IPv6

```bash
# traceroute6 2404:6800:4009:807::200e
```

## # tracepath

```bash
# apt update
```

```bash
# apt install iputils-tracepath
```

```bash
# tracepath 8.8.8.8
```

---

**For checking notes between Client and the Server in Windows.**

**# tracert**

---

### Traceroute Website Service

View-DNS          →          https://viewdns.info/traceroute/

CentralOps        →          https://centralops.net/co/

---

# IP History

**This is used to know on how many servers this Domain has been configured in the past.**

View-DNS           →         https://viewdns.info/iphistory/

Security Trails    →          https://securitytrails.com/

---

# DNS Records Lookup

### **mx record Lookup (** Mail Exchange Record )

```bash
# dig mx facebook.com
```

Then search the mail server domain to the website below for knowing who else are using the same mail server as the target.

View-DNS          →          https://viewdns.info/reversemx/

---

### **NS Record Lookup (Name Server Record)**

```bash
# nslookup -type=ns facebook.com
```

```bash
# dig ns facebook.com
```

**If there are multiple name server records then use SOA Records:**

View-DNS           →          https://viewdns.info/reversens/

---

## Open Ports Check

This is done by Nmap, this is not recommended.

View-DNS           →          https://viewdns.info/portscan/

YouGetSignal       →          https://www.yougetsignal.com/tools/open-ports/

DnsChecker         →          https://dnschecker.org/port-scanner.php

PortChecker        →          https://portchecker.co/

---
