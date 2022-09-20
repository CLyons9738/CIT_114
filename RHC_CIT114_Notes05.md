# Week 7 notes(Networking & Content Delivery)

### Definitions
* The internet is a global network of connected smaller networks
* The World Wide Web is a subset of the internet; Websites. Written in HTML
* Url means Uniform Resource Identifier basically the address of a website/page
* Ip addresses are numbers that make up devices on a network and devices communicate with them.
### The OSI(7-layer) Sending or receiving data
* **Layer Seven, Application Layer** Where applications can use network services
* **Layer Six, Presentation Layer** Encrypts the data and makes sure the format is readable
* **Layer Five, Session Layer** 
### IP addresses and DNS 
* All devices have a unique address.
* Traditional Ip addresses are 32 bits long. Each section is 8 bits.
* IPv6 uses 128 bits and its being used now because we need a longer Internet address.
* DNS services are divided into heiarchy and they bounce information off of eachother and help eachother out.
* DNS was originally created to be open communication protocol. Because of this its very vulnurable to cyber attacks. 
* DNS Spoofing is when a hacker changes the DNS server and changes it to match a domain name with the wrong IP address.  
### Basics of binary math
* A byte-Eight bits
**What is Binary 00000010 in decimal?**
128   64     32   16   8    4    2   1
0     0      0    0    0    0    1   0 = 2 decimal 
**Decimal to binary conversion**
* What is decimal 154 in binary? = 10011010
128 64  32 16  8  4  2  1 
1   0   0  1   1  0  1  0 
* *Binary is just 2 to the **X** power. Ie 2^2 4^2 8^2
* 10 = 2
* 11 = 3
* 10010 = 18
### Subnets
* A subnet is a network inside of a network
* Makes networks to work more efficiently
### Amazon VPC
* VPC is short for Virtual Private Cloud
* VPC is a creation of Subnets
* Configuration of routing tables and network gateways.
### Virtual Private Network(VPN)
* A connection from one private network to another private network using a secure virtual tunnel over the public internet.
* Used to acccess networks only accessible from onsite networks.
### AWS Transit gateways
* A network transit hub that we can use to interconnect our VPCs and onsite networks.
