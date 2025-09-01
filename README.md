# Cybersecurity-notes
What is Nmap?

Nmap (Network Mapper) is a free and open-source tool used for network discovery and security auditing. It can find active hosts, detect open ports, and identify running services. Security professionals use it to assess systems, while attackers may try to exploit the same information.

🔑 Key Scanning Techniques
1. TCP Connect Scan (-sT)

Performs a full TCP handshake.

Reliable but noisy (easy to detect in logs).
Here’s a screenshot of my Nmap scan command for TCP Connect Snan and its results.

![Nmap Scan Screenshot](https://github.com/user-attachments/assets/ff76f8f8-e175-43e7-bb73-e003751ba25a)

2. SYN Scan (-sS)

The SYN scan is also called a half-open scan because it doesn’t complete the full TCP handshake. Instead, it sends a SYN packet, waits for a SYN/ACK, and then sends a RST to close the connection before it’s fully established.

✅ Advantages: Fast and stealthy; harder to detect in logs.

❌ Disadvantage: Requires root or administrator privileges.

Here’s a screenshot of my Nmap scan command and its result:

![Nmap Scan Screenshot](https://github.com/user-attachments/assets/5ab97f34-d4ab-43ca-b3d4-9194dbdcd314)





