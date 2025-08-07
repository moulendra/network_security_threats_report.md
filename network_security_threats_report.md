# 📄 Network Security Threats – Research Report

**Internship:** Oasis Infobyte Security Analyst Internship  
**Batch:** July-P1  
**Task 4:** Research Report on Common Network Security Threats  
**Author:** [Your Name]  

---

## 🔐 Introduction

Network security is critical in protecting sensitive data and ensuring the integrity of computer systems. This report explores common network security threats, their working mechanisms, impacts, real-world examples, and preventive measures.

---

## 🚫 1. Denial of Service (DoS) Attacks

### ▶️ How it Works:
A DoS attack overwhelms a network, server, or website with excessive traffic or requests, causing it to crash or become inaccessible.

### 🔥 Impact:
- Service downtime
- Customer dissatisfaction
- Loss of revenue

### 🌍 Real-World Example:
In 2016, Dyn DNS provider was hit by a massive Distributed DoS (DDoS) attack, which disrupted major services like Twitter, Reddit, GitHub, and Netflix.

### 🛡️ Prevention & Mitigation:
- Implement firewalls and rate-limiting
- Use DDoS protection services (e.g., Cloudflare, AWS Shield)
- Monitor unusual traffic patterns and apply automated blocking

---

## 🕵️ 2. Man-in-the-Middle (MITM) Attacks

### ▶️ How it Works:
In MITM attacks, a third party secretly intercepts and possibly alters the communication between two systems, often without their knowledge.

### 🔥 Impact:
- Theft of sensitive information (e.g., passwords, credit card numbers)
- Session hijacking
- Data manipulation

### 🌍 Real-World Example:
Attackers often set up fake public Wi-Fi hotspots to intercept communications and steal credentials.

### 🛡️ Prevention & Mitigation:
- Use HTTPS and SSL/TLS encryption
- Enable VPN when using public networks
- Use multi-factor authentication (MFA)

---

## 🎭 3. Spoofing Attacks

### ▶️ How it Works:
Spoofing involves impersonating a trusted entity by falsifying data, such as IP addresses or email headers, to gain unauthorized access.

### 🔥 Types:
- **IP Spoofing**
- **Email Spoofing**
- **ARP Spoofing**
- **DNS Spoofing**

### 🌍 Real-World Example:
Phishing emails that appear to come from a legitimate bank asking users to “verify” credentials.

### 🛡️ Prevention & Mitigation:
- Enable SPF, DKIM, and DMARC in email servers
- Use intrusion detection systems (IDS)
- Validate all communication sources and use secure protocols

---

## 📌 Summary Table

| Threat Type      | Impact                         | Prevention Measures                         |
|------------------|--------------------------------|---------------------------------------------|
| DoS Attack       | Service unavailability         | Rate limiting, DDoS protection              |
| MITM Attack      | Data theft & session hijacking | SSL/TLS, VPN, MFA                           |
| Spoofing Attack  | Unauthorized access            | Email verification protocols, IDS, firewalls |

---

## ✅ Conclusion

Understanding and mitigating network security threats is essential in today’s digital world. DoS, MITM, and Spoofing are among the most common and dangerous threats. By implementing proper security protocols, using secure communication channels, and adopting layered security approaches, organizations and individuals can defend against these attacks effectively.

---

## 📚 References

- [OWASP Network Security Basics](https://owasp.org/)
- [Kaspersky – Types of Network Attacks](https://www.kaspersky.com/resource-center/threats)
- [Cloudflare DDoS Protection](https://www.cloudflare.com/ddos/)