# 🔓 4-ZERO-3 - Advanced 403/401 Bypass Tool

> One tool to rule all 403s.  
> Automated bypass techniques for forbidden directories and restricted paths.  
> Made for **Bug Bounty Hunters**, **Pentesters**, and **Security Researchers**.

---

## 🚀 Features

✅ Header Injection Bypass  
✅ HTTP Method Override  
✅ Protocol Smuggling Tricks  
✅ Port Number Obfuscation  
✅ URL Encoding & Obfuscation  
✅ WAF Bypass using SQLi Signatures  
✅ Complete All-in-One Scan Mode (`--exploit`)

> 🎯 No fancy dependencies. Pure Bash. Pure Power.

---

## ⚙️ Installation

git clone https://github.com/azza0x1a/4-ZERO-3.git
cd 4-ZERO-3
chmod +x 403-bypass.sh

##  Usage

./403-bypass.sh -u https://target.com/admin --exploit

---

## Help Menu

403-bypass [URL]

-u, --url URL Target URL (https://domain.tld/path)

Bypass Modes:
--header Header Injection Bypass
--protocol Protocol Smuggling
--port Alternate Port Bypass
--HTTPmethod HTTP Method Override
--encode URL Encode Tricks
--SQLi WAF Bypass via SQLi
--exploit Run ALL modes

Response Color Legend:
🟩 2xx = Bypass Success  
 🟨 3xx = Redirection  
 🟥 4xx = Forbidden  
 🔵 5xx = Server Error

---

👤 Author
Azza Tegar Naufal Ataullah (@azza0x1a)

🧑‍🎓 Student

🐞 Bug Bounty Hunter | Security Researcher

🔧 Tools Developer | Open Source Contributor

---

☕ Support & Collaboration
If you like this tool, give it a ⭐
