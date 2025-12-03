
# 🔒 Network Security Labs - HIT Course

> A comprehensive collection of practical network security attack demonstrations and analysis

[![Course](https://img.shields.io/badge/Course-Network%20Security-blue)]()
[![Institution](https://img.shields.io/badge/Institution-HIT-orange)]()


## 📚 Overview

This repository contains three comprehensive lab assignments exploring fundamental network security concepts and attack vectors. Each lab includes detailed documentation, practical demonstrations, and analysis of various network-based attacks.

**Authors:** Guy Katz & Abraham Dvoreh  
**Course:** Network Security  
**Institution:** Holon Institute of Technology (HIT)

---

## 🎯 Labs Included

### 1. 🌐 Local DNS Attack Lab
**File:** `Local_DNS_Attack_Lab.docx`

Exploration of local DNS attacks and DNS cache poisoning techniques.

**Topics Covered:**
- DNS Server Configuration
- Local DNS Cache Poisoning
- DNS Spoofing Techniques
- Client-Server DNS Architecture
- Attack Scenarios and Mitigation

**Key Concepts:**
- DNS Resolution Process
- Cache Manipulation
- Network Traffic Analysis
- Server Configuration

---

### 2. 💣 Remote DNS Attack (Kaminsky Attack) Lab
**File:** `Remote_DNS_Attack__Kaminsky_Attack__Lab.docx`

Deep dive into the famous Kaminsky DNS cache poisoning attack, one of the most significant vulnerabilities discovered in the DNS protocol.

**Topics Covered:**
- Dan Kaminsky's DNS Vulnerability
- Remote DNS Cache Poisoning
- Transaction ID Prediction
- Race Condition Exploitation
- Port Randomization Bypass

**Key Concepts:**
- DNS Query/Response Mechanism
- Birthday Attack Principles
- Network-Level Race Conditions
- Large-Scale DNS Exploitation

---

### 3. 🔨 IP and ICMP Attacks Lab
**File:** `IP_and_ICMP_Attacks_Lab.docx`

Practical exploration of IP fragmentation vulnerabilities and ICMP-based attacks.

**Topics Covered:**
- IP Fragmentation Process
- Tear Attack Implementation
- Bonk Attack Demonstration
- Ping of Death (PoD) Attack
- Modern OS Protections

**Key Concepts:**
- IP Packet Fragmentation
- Fragment Reassembly Vulnerabilities
- ICMP Protocol Exploitation
- Operating System Security Mechanisms

**Expected Results:**
- Understanding of fragmentation attacks
- Recognition of modern OS protections
- Analysis of why Ping of Death no longer works on modern systems

---

## 🛠️ Technical Environment

### Network Topology
Each lab utilizes a controlled network environment with:
- **Client Machine:** User endpoint for conducting attacks
- **DNS Server:** Target/Victim server
- **Attacker Machine:** System performing the attacks
- **Network Configuration:** Isolated lab environment

### Tools & Technologies
- **Scapy:** Packet manipulation and crafting
- **Wireshark:** Network traffic analysis
- **Python:** Attack scripting and automation
- **Docker/VMs:** Isolated testing environment
- **tcpdump:** Packet capture and analysis

---

## 📖 Lab Structure

Each lab document includes:

1. **Introduction (מבוא)**
   - Background and context
   - Objectives and expected outcomes

2. **Network Topology (שרטוט הרשת)**
   - Visual representation of the lab environment
   - Component descriptions

3. **Task Implementation**
   - Step-by-step procedures
   - Command examples
   - Configuration files

4. **Results & Analysis**
   - Screenshots and output
   - Traffic analysis
   - Success/failure discussion

5. **Conclusions**
   - Key findings
   - Security implications
   - Mitigation strategies

---



### Running the Labs
1. Read the respective lab document thoroughly
2. Set up the network topology as described
3. Configure the machines according to the instructions
4. Execute the attacks in the controlled environment
5. Analyze the results

---

## ⚠️ Ethical Considerations

**IMPORTANT:** These labs are for **educational purposes only**.

- ✅ Use only in controlled, isolated lab environments
- ✅ Obtain proper authorization before any testing
- ✅ Never perform these attacks on production systems
- ✅ Respect computer security laws and regulations
- ❌ Do NOT use for malicious purposes

**Unauthorized access to computer systems is illegal and unethical.**

---

## 📊 Learning Outcomes

Upon completing these labs, you will understand:

- How DNS vulnerabilities can be exploited
- The mechanics of cache poisoning attacks
- IP fragmentation and its security implications
- ICMP protocol vulnerabilities
- Modern security protections and their effectiveness
- Network traffic analysis techniques
- Ethical hacking methodologies



## 📝 Documentation

All labs are documented  with:
- Detailed theoretical background
- Step-by-step procedures
- Screenshots and network diagrams
- Traffic analysis and packet captures
- Results interpretation

---



## 📧 Contact

**Guy Katz**
- Institution: Holon Institute of Technology

**Abraham Dvoreh**
- Institution: Holon Institute of Technology

---

## 📜 License

This project is created for educational purposes as part of the Network Security course at HIT.

---

## 🙏 Acknowledgments

- HIT Network Security Course Instructors
- SEED Labs Project (for inspiration)

---

## 📚 References

- [RFC 1035 - Domain Names Implementation](https://tools.ietf.org/html/rfc1035)
- [CVE-2008-1447 - Kaminsky DNS Vulnerability](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2008-1447)
- [IP Fragmentation Attacks](https://en.wikipedia.org/wiki/IP_fragmentation_attack)
- [DNSSEC - DNS Security Extensions](https://www.dnssec.net/)

---

<div align="center">

**🎓 Made with ❤️ for Learning Network Security**

*Remember: With great power comes great responsibility*

</div>
