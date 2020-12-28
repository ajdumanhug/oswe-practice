# oswe-practice
OSWE-like machines

| Machine Name | Source | Language | Authentication Bypass | RCE | Is Source Code Review required? |
| --- | --- | --- | --- | --- | --- |
| Harder | [TryHackMe](https://tryhackme.com/room/harder) | PHP | Exposed Git Repository + Bypassing of hash_hmac | Regular Command Injection | Yes |
| Spring | [TryHackMe](https://tryhackme.com/room/spring) | Java | Exposed Git Repository + Bypassing IP restriction | Exploitation of Spring Boot Actuators | Yes |
| All in One | [TryHackMe](https://www.tryhackme.com/room/allinonemj) | PHP | Local File Inclusion | Malicious File Upload/Modification | No |
| Misguided Ghosts | [TryHackMe](https://tryhackme.com/room/misguidedghosts) | PHP | Cross-Site Scripting | Command Injection | No |
| Cache | [HackTheBox](https://www.hackthebox.eu/home/machines/profile/251) | PHP | SQL Injection + Cracking Bcrypt | Malicious File Upload/Modification | Yes |
| Magic | [HackTheBox](https://www.hackthebox.eu/home/machines/profile/241) | PHP | Basic SQL Injection | Bypass File Upload | No |
| Book | [HackTheBox](https://www.hackthebox.eu/home/machines/profile/230) | PHP | SQL Truncation | Cross-Site Scripting to RCE | No |
| Wall | [HackTheBox](https://www.hackthebox.eu/home/machines/profile/208) | PHP | Verb Tampering + Bruteforcing | Command Injection | No |

Authentication Bypass Only
| Machine Name | Source | Language | Authentication Bypass |
| --- | --- | --- | --- |
| Mango | [HackTheBox](https://www.hackthebox.eu/home/machines/profile/214) | PHP | NoSQL Injection |

RCE Only
| Machine Name | Source | Language | RCE |
| --- | --- | --- | --- |
| Json | [HackTheBox](https://www.hackthebox.eu/home/machines/profile/210) | .Net | Deserialization |
| Jarvis | [HackTheBox](https://www.hackthebox.eu/home/machines/profile/194) | PHP | File writes through SQL injection | 
| Unattended | [HackTheBox](https://www.hackthebox.eu/home/machines/profile/184) | PHP | Directory Traversal + Union-Based SQL Injection + Local File Inclusion + Log File Poisoning + Bypassing of IP Tables |
| Arkham | [HackTheBox](https://www.hackthebox.eu/home/machines/profile/179) | Java | Deserialization |
