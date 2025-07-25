---
tags:
  - network
  - important
references:
  - "[[NMAP Network Scanning]]"
---
1. **Port 80 (HTTP)** — If you don't even know this service, you're reading the wrong book. This accounted for more than 14% of the open ports we discovered.
2. **Port 23 (Telnet)** — Telnet lives on (particularly as an administration port on devices such as routers and smart switches) even though it is insecure (unencrypted).
3. **Port 443 (HTTPS)** — SSL-encrypted web servers use this port by default.
4. **Port 21 (FTP)** — FTP, like Telnet, is another insecure protocol which should die. Even with anonymous FTP (avoiding the authentication sniffing worry), data transfer is still subject to tampering
5. **Port 22 (SSH)** — Secure Shell, an encrypted replacement for Telnet (and, in some cases, FTP).
6. **Port 25 (SMTP)** — Simple Mail Transfer Protocol (also insecure).
7. **Port 3389 (ms-term-server)** — Microsoft Terminal Services administration port.
8. **Port 110 (POP3)** — Post Office Protocol version 3 for email retrieval (insecure).
9. **Port 445 (Microsoft-DS)** — For SMB communication over IP with MS Windows services (such as file/printer sharing).
10. **Port 139 (NetBIOS-SSN)** — NetBIOS Session Service for communication with MS Windows services (such as file/printer sharing). This has been supported on Windows machines longer than 445 has.
11. **Port 143 (IMAP)** — Internet Message Access Protocol version 2. An insecure email retrieval protocol.
12. **Port 53 (Domain)** — Domain Name System (DNS), an insecure system for conversion between host/domain names and IP addresses.
13. **Port 135 (MSRPC)** — Another common port for MS Windows services.
14. **Port 3306 (MySQL)** — For communication with MySQL databases.
15. **Port 8080 (HTTP-Proxy)** — Commonly used for HTTP proxies or as an alternate port for normal web servers (e.g. when another server is already listening on port 80, or when run by unprivileged UNIX users who can only bind to high ports).
16. **Port 1723 (PPTP)** — Point-to-point tunneling protocol (a method of implementing VPNs which is often required for broadband connections to ISPs).
17. **Port 111 (RPCBind)** — Maps SunRPC program numbers to their current TCP or UDP port numbers.
18. **Port 995 (POP3S)** — POP3 with SSL added for security.
19. **Port 993 (IMAPS)** — **IMAPv2 with SSL added for security.   
20. **Port 5900 (VNC)** — A graphical desktop sharing system (insecure).