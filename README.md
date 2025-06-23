# cyber-interntasks
 Scan Summary
 Device 1: Router – 192.168.29.1 (Shenzhen Skyworth Digital Technology)
Open Ports:

80/tcp – HTTP

443/tcp – HTTPS

1900/tcp – UPnP

7443/tcp – OracleAS-HTTPS

8080/tcp – HTTP Proxy

8443/tcp – HTTPS-ALT

Closed Ports:

2869/tcp, 8002/tcp, 8200/tcp

Risk Analysis:

Multiple open HTTP/HTTPS ports may expose web interfaces.

UPnP (1900) can be risky if not restricted; it has known vulnerabilities.

Router firmware should be kept updated and access restricted.

 Device 2: My System – 192.168.29.156
Open Ports:

135/tcp – Microsoft RPC

139/tcp – NetBIOS-SSN

445/tcp – Microsoft-DS (SMB)

902/tcp – ISS RealSecure

912/tcp – Apex Mesh

Risk Analysis:

SMB-related ports (139, 445) are known vectors for ransomware (e.g., WannaCry).

These should be blocked via firewall in public networks.

If unused, ISS/Apex Mesh services should be disabled.
 Key Takeaways
Identified 2 active hosts on my local network.

Discovered several open ports that could pose risks if not secured.

Gained hands-on experience using nmap for real-world network reconnaissance.

