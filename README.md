# Cisco ASA FIREWALL PROJECT

Cisco Packet Tracer Network Project Overview

![Screenshot 2025-02-28 at 10 46 37 PM](https://github.com/user-attachments/assets/1b58e841-c174-405a-bad4-ec298ca3928d)

This project showcases the design and implementation of a secure and fully functional enterprise network using Cisco Packet Tracer. The network is built with OSPF routing, static default routing, DHCP, SSH security, and firewall policies, ensuring efficient connectivity and security across multiple segments.

Key Configurations:

🔹 Routing & Network Configuration: The topology includes an inside router, an outside router, and a firewall, with OSPF and default static routes ensuring proper data flow.
🔹 DHCP Implementation: Configuring dynamic IP addressing for internal hosts, along with DNS setup and DHCP relay through the firewall.
🔹 SSH Security: Securing remote access using AAA authentication, RSA key generation, and IP-based SSH access control.
🔹 Firewall Policies & NAT: Setting up Network Address Translation (NAT) for internal hosts and Access Control Lists (ACLs) to regulate traffic between inside, DMZ, and external networks.
🔹 DMZ Services: Deploying DHCP, DNS, and Web Servers within a DMZ to support internal and external connectivity, tested through domain-based access and ping verification.

This project demonstrates practical networking skills in configuring a scalable, secure, and well-documented network. 🚀

-------- Config + OSPF + DEFAULT STATIC ROUTING CONFIGS--------

1. Draw necessary topology, decorate and comment
2. ﻿﻿﻿Configure hostname, enable passwords, username and password, and clock and date.
3. ﻿﻿﻿Configure IP addresses, names, and security level to the interfaces.
4. ﻿﻿﻿Configure OSPF on the inside router and the firewall
5. ﻿﻿﻿Configure default static routing on the outside router and the firewall

-------- DHCP CONFIGS --------

6. Configure address ranges to be issued
7. ﻿﻿﻿Configure DNS server
8. ﻿﻿﻿Enable DHCP on the firewall interface.
9. ﻿﻿﻿Enable DHCP on the computers

------- SSH CONFIGS --------

9. Ensure steps 283 under basic configs are completed.
10. ﻿﻿﻿Ensure inside hosts can ping firewall.
11. ﻿﻿﻿Enable LOCAL aaa authentication for username to SSH onto ASA
12. ﻿﻿﻿Generate RSA key pair
13. ﻿﻿﻿Define the subnets or IPs which are allowed to SSH onto ASA.
14. ﻿﻿﻿Specify SSH tmeout---try out

---------- BASIC FIREWALL POLICIES CONFIGS ----------

15. Draw necessary topology, decorate and comment
16. Ensure to complete the last stage above (of routing configs).
17. Configure NAT to translate both INSIDE and DMZ IP when they access internet.
18. Configure firewall policies using ACL to allow every communication in the network.
19. Configure DHCP, DNS and WEB servers on the DMZ
20. Go to inside PC and request IP, try to access web server using the domain name.
21. Ping from outside to inside and vice-versa.
