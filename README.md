⚠ WARNING: ***This is for educational purposes only and I am not responsible for any misuse.*** ⚠

<h1 align="center">DDoS Attack Script With 36 Method</h1>

## Features And Method

 * Layer7
   * GET | GET Flood
   * POST | POST Flood
   * OVH | Bypass OVH
   * STRESS | Send HTTP Packet With High Byte 
   * OSTRESS | STRESS Without Proxy
   * DYN | A New Method With Random SubDomain
   * SLOW | Slowloris Old Method of DDoS
   * HEAD | https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/HEAD
   * HIT | POST Without PROXY
   * NULL | Null UserAgent and ...
   * COOKIE | Random Cookie PHP 'if (isset($_COOKIE))'
   * BRUST | A Method with more header
   * PPS |  Only 'GET / HTTP/1.1\r\n\r\n'
   * EVEN | GET Method with more header
   * GSB | Google Project Shield Bypass
   * DGB | DDoS Guard Bypass
   * AVB | Arvan Cloud Bypass
   * CFB | CloudFlare Bypass
   * BYPASS |  Bypass Normal AntiDDoS


* Layer4: 
  * TCP | TCP Flood Bypass
  * UDP | UDP Flood Bypass
  * SYN | SYN Flood
  * VSE | VSE Flood Only Connection
  * MEM | Memcached Flood
  * NTP | NTP Flood OLD Method Of Layer4

* Layer3
  * ICMP | Flood ICMP Request
  * POD | Ping Of Death OLD Method Of DDoS

* Tools - Run With 'python3 start.py tools'
  * CFIP | Find Real IP address of Website Powered by Cloudflare
  * DNS | Show Site DNS Records
  * PING | PING server
  * CHECK | Check Website Die or no
  * DSTAT | a Method show Receive And Send Bytes Size

* Other
  * STOP | STOP All Attacks
  * TOOLS | Tools Console
  * HELP | Show Usge Script

**Requirements**

* Python3
* requests
* PySocks
* cfscrape
* icmplib
* scapy
---

**Clone and Install Script**

```console
git clone 
cd DDoS-beast
pip3 install -r requirements.txt
```

---

**Launch Script**

```console
python3 start.py
python3 start.py bypass https://example.com 5 1000 socks5.txt 100 100
```
