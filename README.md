<div align="center">

# Awesome Cybersecurity Tools

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
![GitHub Stars](https://img.shields.io/github/stars/ykrishhh/awesome-cybersecurity-tools?style=flat-square&color=yellow)
![GitHub Forks](https://img.shields.io/github/forks/ykrishhh/awesome-cybersecurity-tools?style=flat-square)
![License](https://img.shields.io/github/license/ykrishhh/awesome-cybersecurity-tools?style=flat-square)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)

A curated list of **60+** security tools, frameworks, and resources for penetration testers, bug bounty hunters, and security researchers.

[Contribute](#contributing) · [Request Tool](https://github.com/ykrishhh/awesome-cybersecurity-tools/issues)

</div>

---

## Contents

- [Network Analysis](#network-analysis)
- [Web Application Security](#web-application-security)
- [Wireless & RF](#wireless--rf)
- [Reverse Engineering](#reverse-engineering)
- [Digital Forensics](#digital-forensics)
- [Password Attacks](#password-attacks)
- [Exploitation](#exploitation)
- [OSINT](#osint)
- [Container & Cloud Security](#container--cloud-security)
- [Security Automation](#security-automation)
- [Social Engineering](#social-engineering)
- [Contributing](#contributing)

---

## Network Analysis

> Tools for network reconnaissance, scanning, and traffic analysis.

| Tool | Description | Stars |
|------|-------------|-------|
| [Nmap](https://github.com/nmap/nmap) | Network discovery and security auditing utility | ![Stars](https://img.shields.io/github/stars/nmap/nmap?style=social) |
| [Wireshark](https://github.com/wireshark/wireshark) | Network protocol analyzer for deep packet inspection | ![Stars](https://img.shields.io/github/stars/wireshark/wireshark?style=social) |
| [tcpdump](https://github.com/the-tcpdump-group/tcpdump) | Powerful command-line packet analyzer | ![Stars](https://img.shields.io/github/stars/the-tcpdump-group/tcpdump?style=social) |
| [Netcat](https://github.com/diegocr/netcat) | TCP/UDP Swiss army knife for network debugging | ![Stars](https://img.shields.io/github/stars/diegocr/netcat?style=social) |
| [Masscan](https://github.com/robertdavidgraham/masscan) | TCP port scanner — fastest on the internet | ![Stars](https://img.shields.io/github/stars/robertdavidgraham/masscan?style=social) |
| [Zeek](https://github.com/zeek/zeek) | Network security monitoring framework | ![Stars](https://img.shields.io/github/stars/zeek/zeek?style=social) |

## Web Application Security

> Tools for finding and exploiting web vulnerabilities.

| Tool | Description | Stars |
|------|-------------|-------|
| [Burp Suite](https://github.com/PortSwigger/burp-extensions) | Leading web vulnerability scanner (extensions) | ![Stars](https://img.shields.io/github/stars/PortSwigger/burp-extensions?style=social) |
| [OWASP ZAP](https://github.com/zaproxy/zaproxy) | Free, open-source web application security scanner | ![Stars](https://img.shields.io/github/stars/zaproxy/zaproxy?style=social) |
| [SQLMap](https://github.com/sqlmapproject/sqlmap) | Automatic SQL injection and database takeover tool | ![Stars](https://img.shields.io/github/stars/sqlmapproject/sqlmap?style=social) |
| [Nikto](https://github.com/sullo/nikto) | Web server scanner for dangerous files/CGIs | ![Stars](https://img.shields.io/github/stars/sullo/nikto?style=social) |
| [Dirb](https://github.com/v0re/dirb) | Web content scanner for brute-force directory discovery | ![Stars](https://img.shields.io/github/stars/v0re/dirb?style=social) |
| [Wapiti](https://github.com/wapiti-scanner/wapiti) | Web application vulnerability scanner | ![Stars](https://img.shields.io/github/stars/wapiti-scanner/wapiti?style=social) |
| [XSStrike](https://github.com/s0md3v/XSStrike) | Most advanced XSS scanner | ![Stars](https://img.shields.io/github/stars/s0md3v/XSStrike?style=social) |

## Wireless & RF

> Tools for WiFi, Bluetooth, and radio frequency security research.

| Tool | Description | Stars |
|------|-------------|-------|
| [Aircrack-ng](https://github.com/aircrack-ng/aircrack-ng) | Complete suite for WiFi security assessment | ![Stars](https://img.shields.io/github/stars/aircrack-ng/aircrack-ng?style=social) |
| [HackRF One](https://github.com/mossmann/hackrf) | SDR platform for RF experimentation | ![Stars](https://img.shields.io/github/stars/mossmann/hackrf?style=social) |
| [ESP32 Marauder](https://github.com/justcallmekoko/ESP32Marauder) | ESP32 WiFi/BLE attack tool | ![Stars](https://img.shields.io/github/stars/justcallmekoko/ESP32Marauder?style=social) |
| [Kalibrate-RTL](https://github.com/steve-m/kalibrate-rtl) | Calibrate RTL-SDR dongles | ![Stars](https://img.shields.io/github/stars/steve-m/kalibrate-rtl?style=social) |
| [Kismet](https://github.com/kismetwireless/kismet) | Wireless network and device detector/sniffer | ![Stars](https://img.shields.io/github/stars/kismetwireless/kismet?style=social) |

## Reverse Engineering

> Tools for binary analysis, decompilation, and reverse engineering.

| Tool | Description | Stars |
|------|-------------|-------|
| [Ghidra](https://github.com/NationalSecurityAgency/ghidra) | Software reverse engineering framework by NSA | ![Stars](https://img.shields.io/github/stars/NationalSecurityAgency/ghidra?style=social) |
| [Radare2](https://github.com/radareorg/radare2) | UNIX-like reverse engineering framework | ![Stars](https://img.shields.io/github/stars/radareorg/radare2?style=social) |
| [Binary Ninja](https://github.com/Vector35/binaryninja-api) | Binary analysis platform API | ![Stars](https://img.shields.io/github/stars/Vector35/binaryninja-api?style=social) |
| [Binwalk](https://github.com/ReFirmLabs/binwalk) | Firmware analysis tool | ![Stars](https://img.shields.io/github/stars/ReFirmLabs/binwalk?style=social) |
| [pwntools](https://github.com/Gallopsled/pwntools) | CTF framework and exploit development library | ![Stars](https://img.shields.io/github/stars/Gallopsled/pwntools?style=social) |
| [ROPgadget](https://github.com/JonathanSalwan/ROPgadget) | Search gadgets for ROP exploitation | ![Stars](https://img.shields.io/github/stars/JonathanSalwan/ROPgadget?style=social) |

## Digital Forensics

> Tools for incident response, memory forensics, and disk analysis.

| Tool | Description | Stars |
|------|-------------|-------|
| [Autopsy](https://github.com/sleuthkit/autopsy) | Digital forensics platform and GUI for TSK | ![Stars](https://img.shields.io/github/stars/sleuthkit/autopsy?style=social) |
| [Volatility](https://github.com/volatilityfoundation/volatility3) | Advanced memory forensics framework | ![Stars](https://img.shields.io/github/stars/volatilityfoundation/volatility3?style=social) |
| [Sleuth Kit](https://github.com/sleuthkit/sleuthkit) | File and volume system forensic analysis | ![Stars](https://img.shields.io/github/stars/sleuthkit/sleuthkit?style=social) |
| [Plaso](https://github.com/log2timeline/plaso) | Super timeline creation tool | ![Stars](https://img.shields.io/github/stars/log2timeline/plaso?style=social) |

## Password Attacks

> Tools for password cracking, brute-forcing, and hash analysis.

| Tool | Description | Stars |
|------|-------------|-------|
| [Hashcat](https://github.com/hashcat/hashcat) | World's fastest password recovery utility | ![Stars](https://img.shields.io/github/stars/hashcat/hashcat?style=social) |
| [John the Ripper](https://github.com/openwall/john) | Password cracker for multiple hash types | ![Stars](https://img.shields.io/github/stars/openwall/john?style=social) |
| [Hydra](https://github.com/vanhauser-thc/thc-hydra) | Fast network login cracker | ![Stars](https://img.shields.io/github/stars/vanhauser-thc/thc-hydra?style=social) |
| [CeWL](https://github.com/digininja/CeWL) | Custom wordlist generator from target websites | ![Stars](https://img.shields.io/github/stars/digininja/CeWL?style=social) |

## Exploitation

> Frameworks and tools for developing and delivering exploits.

| Tool | Description | Stars |
|------|-------------|-------|
| [Metasploit](https://github.com/rapid7/metasploit-framework) | The world's most used penetration testing framework | ![Stars](https://img.shields.io/github/stars/rapid7/metasploit-framework?style=social) |
| [SearchSploit](https://github.com/offensive-security/exploitdb) | Exploit-DB archive and search tool | ![Stars](https://img.shields.io/github/stars/offensive-security/exploitdb?style=social) |
| [BeEF](https://github.com/beefproject/beef) | Browser Exploitation Framework | ![Stars](https://img.shields.io/github/stars/beefproject/beef?style=social) |
| [Responder](https://github.com/lgandx/Responder) | LLMNR/NBT-NS/MDNS poisoner | ![Stars](https://img.shields.io/github/stars/lgandx/Responder?style=social) |

## OSINT

> Open source intelligence gathering and reconnaissance tools.

| Tool | Description | Stars |
|------|-------------|-------|
| [Maltego](https://github.com/MaltegoTech/maltego) | Interactive data mining and link analysis | ![Stars](https://img.shields.io/github/stars/MaltegoTech/maltego?style=social) |
| [Sherlock](https://github.com/sherlock-project/sherlock) | Find usernames across social networks | ![Stars](https://img.shields.io/github/stars/sherlock-project/sherlock?style=social) |
| [theHarvester](https://github.com/laramies/theHarvester) | Email, subdomain, and name harvester | ![Stars](https://img.shields.io/github/stars/laramies/theHarvester?style=social) |
| [SpiderFoot](https://github.com/smicallef/spiderfoot) | OSINT automation tool | ![Stars](https://img.shields.io/github/stars/smicallef/spiderfoot?style=social) |
| [Recon-ng](https://github.com/lanmaster53/recon-ng) | Full-featured web reconnaissance framework | ![Stars](https://img.shields.io/github/stars/lanmaster53/recon-ng?style=social) |

## Container & Cloud Security

> Tools for securing containers, Kubernetes, and cloud infrastructure.

| Tool | Description | Stars |
|------|-------------|-------|
| [Trivy](https://github.com/aquasecurity/trivy) | Comprehensive vulnerability scanner for containers | ![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social) |
| [Grype](https://github.com/anchore/grype) | Vulnerability scanner for container images | ![Stars](https://img.shields.io/github/stars/anchore/grype?style=social) |
| [Scout](https://github.com/aquasecurity/scout) | Container image analysis | ![Stars](https://img.shields.io/github/stars/aquasecurity/scout?style=social) |
| [Kube-Hunter](https://github.com/aquasecurity/kube-hunter) | Hunt for security weaknesses in Kubernetes clusters | ![Stars](https://img.shields.io/github/stars/aquasecurity/kube-hunter?style=social) |

## Security Automation

> Tools for automating security workflows, scanning, and CI/CD integration.

| Tool | Description | Stars |
|------|-------------|-------|
| [Nuclei](https://github.com/projectdiscovery/nuclei) | Fast vulnerability scanner based on templates | ![Stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social) |
| [Subfinder](https://github.com/projectdiscovery/subfinder) | Fast passive subdomain enumeration tool | ![Stars](https://img.shields.io/github/stars/projectdiscovery/subfinder?style=social) |
| [httpx](https://github.com/projectdiscovery/httpx) | Fast and multi-purpose HTTP toolkit | ![Stars](https://img.shields.io/github/stars/projectdiscovery/httpx?style=social) |
| [Amass](https://github.com/owasp-amass/amass) | In-depth attack surface mapping and asset discovery | ![Stars](https://img.shields.io/github/stars/owasp-amass/amass?style=social) |
| [Gitleaks](https://github.com/gitleaks/gitleaks) | Secret scanner for git repos | ![Stars](https://img.shields.io/github/stars/gitleaks/gitleaks?style=social) |

## Social Engineering

> Tools for phishing simulation and social engineering testing.

| Tool | Description | Stars |
|------|-------------|-------|
| [SET](https://github.com/trustedsec/social-engineer-toolkit) | Social Engineering Toolkit by TrustedSec | ![Stars](https://img.shields.io/github/stars/trustedsec/social-engineer-toolkit?style=social) |
| [Gophish](https://github.com/gophish/gophish) | Open-source phishing framework | ![Stars](https://img.shields.io/github/stars/gophish/gophish?style=social) |

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/add-tool`)
3. Commit your changes (`git commit -m 'Add awesome-tool'`)
4. Push to the branch (`git push origin feature/add-tool`)
5. Open a Pull Request

### Adding a Tool

Add a new row to the appropriate category table:

```markdown
| [Tool Name](https://github.com/org/repo) | Short description | ![Stars](https://img.shields.io/github/stars/org/repo?style=social) |
```

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [ykrishhh](https://github.com/ykrishhh) has waived all copyright and related rights to this work.

---

<div align="center">

**If you find this list useful, give it a star ⭐**

*Last updated: July 2026*

</div>

<!-- SEO Keywords: cybersecurity, security tools, penetration testing, bug bounty, ethical hacking, infosec, vulnerability scanning, OSINT, exploit development, network security, web security, forensics, reverse engineering, awesome list, security resources -->
