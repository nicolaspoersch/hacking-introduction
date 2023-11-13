<p align="center">
  <a href="https://github.com/nicolaspoersch/hacking-introduction">
    <img src="https://pngimg.com/uploads/wings/wings_PNG21.png">
  </a>
</p>

<p align="center">"<i>Explore the World of Hacking!</i>"</p>

<h4 align="center">A guide for hacking beginners to develop solid knowledge.</h4>

<div align="center">
  <sub>Created by
  <a href="https://github.com/nicolaspoersch">Nicolas Poersch</a>
</div>

<hr>

# Hacking Fundamentals: Getting Started

**Important Notice**  
If you've found this documentation, consider yourself fortunate. There are many fraudulent courses and promises of becoming a "Professional Hacker" in a short period, typically in 15 to 30 hours of study. However, it's essential to understand that cybersecurity and ethical hacking are not skills that can be mastered in such a short time.

Ethical hacking and cybersecurity are complex and ever-evolving fields that require a serious commitment to continuous learning. There is no magic formula for becoming a cybersecurity expert overnight.

The goal of this documentation is to provide a solid foundation of knowledge and guidance for those who wish to explore the world of cybersecurity and ethical hacking. If you follow this guide, study deeply, and understand the concepts presented here, you will be building a strong foundation to develop your skills in this field.

Remember that the learning journey in cybersecurity is challenging but rewarding. Patience, practice, and dedication are essential to becoming a competent professional in the field. Good luck on your learning journey!

## Introduction to Hacking

### Understanding Hacker Ethics

**Difference between ethical hackers and cybercriminals:**  
Ethical hackers operate with permission and legitimate objectives, while cybercriminals act illegally.

**Ethical responsibility:**  
The importance of following an ethical code, obtaining permission, and responsibly disclosing vulnerabilities.

## Learning Programming

### Essential Programming Languages (Python, C++, Shell/Bash Script, etc.):

- **Python:** As an essential programming language, Python is valued for its simplicity, extensive library support, and versatility. Learn to write scripts for automating tasks and create custom tools for security testing.

- **C++:** C++ is crucial for understanding low-level vulnerabilities and exploring complex systems. Focus on low-level programming, such as memory manipulation and fault analysis.

- **Java:** To comprehend Java-based applications, study the language and its associated security. This will be beneficial when dealing with corporate systems that use Java.

## Operating Systems

**Importance of Linux for Hackers:**  
Linux is preferred due to its open-source nature, flexibility, and the availability of security tools.

**Linux Distributions for Security:**  
- Kali Linux: A specialized security distribution that includes various useful tools. You can learn basic Kali Linux commands at [kali.org](https://www.kali.org/).
- Parrot Security OS: Besides Kali Linux, Parrot Security OS is another popular Linux distribution for ethical hackers. It offers a variety of penetration testing tools and is suitable for security testing and audits.
- BlackArch Linux: Known for its extensive collection of security and hacking tools, based on Arch Linux.
- BackBox: A Linux distribution designed for security assessment and penetration testing with a user-friendly interface.
- Pentoo: Suitable for penetration testing and security analysis tasks, based on Gentoo Linux.
- Security Onion: Focused on security incident detection and response, including network traffic analysis tools.

**Setting Up the Linux Environment:**  
Learn to install and configure Linux distributions in virtual environments using software like VirtualBox or VMware. This will allow you to create test environments for your cybersecurity activities.

## Networking Knowledge

### TCP/IP Protocols and Their Functionality:

- TCP/IP is essential for communication on the Internet. Understand how data is packaged, addressed, and transmitted.

- **Wireshark:** Learn to use tools like Wireshark to capture and analyze network traffic. This helps you comprehend how protocols work in practice.

### IP Addressing, Subnets, and Routing:

- Learn to configure networks, including creating subnets and setting up routers.

- **Virtual Network Practice:** Set up virtual networks to practice IP addressing and routing concepts in a secure environment.

## Information Security

### Security Principles, including Confidentiality, Integrity, and Availability:

- Protect data by keeping it confidential, intact, and available when necessary.

- **Layered Security:** Understand the importance of security in multiple layers, from the network to the application. Explore technologies like firewalls, IDS/IPS, antivirus, and encryption.

- **Encryption and Authentication:** Learn how encryption safeguards confidential information and how authentication verifies identity.

- **PGP (Pretty Good Privacy):** Learn to use PGP for encrypting and digitally signing messages and files. It's a valuable tool for secure communications.

- **Two-Factor Authentication (2FA):** Implement two-factor authentication in your online accounts and systems for an additional layer of security.

## What to Learn Initially

**What is a Network and How It Works**

### What is a Network:

A computer network is a set of interconnected devices that share resources and information. This can include computers, servers, network devices, and even the Internet. Networks allow data exchange and efficient communication between devices.

### Understanding Network Operation:

- **Network Topology:** Networks can assume various topologies, such as star, bus, and mesh, each outlining how devices interconnect. The chosen topology directly influences network redundancy, scalability, and resilience.

- **Switching and Routing:** Switches and routers play crucial roles in guiding traffic across the network, ensuring that data reaches its destination efficiently. Switching occurs at the data link layer, while routing operates at the network layer, enabling communication between different subnets.

- **Network Protocols:** Fundamental protocols, such as TCP/IP, establish guidelines for network communication. This includes specifications for data packet format and routing paths, forming the backbone of interconnection. In addition to TCP/IP, other protocols like UDP (User Datagram Protocol) and ICMP (Internet Control Message Protocol) perform specific functions in data transmission and monitoring.

- **Network Security:** In the context of ethical hacking, understanding security measures is crucial. This involves firewalls, encryption, intrusion detection, and access policies. The ethical hacking professional must not only comprehend how networks operate but also be aware of vulnerabilities and security practices to safeguard data integrity and confidentiality.

## What is the Internet

**What is the Internet:**
The Internet is a global network of interconnected networks. It enables worldwide communication and information sharing. The Internet is based on the TCP/IP protocol and operates as a decentralized network.

### How the Internet Works:

- **Services and Protocols:** The Internet offers various services, such as the World Wide Web (WWW), email, file transfer, among others, each with its own protocol.
- **Internet Service Providers (ISPs):** ISPs connect users to the Internet, providing access to the global network.
- **IP Addresses:** Every device connected to the Internet has a unique IP address that identifies it on the network.
- **Difference between HTTP and HTTPS:**
  - **HTTP (Hypertext Transfer Protocol):** It is a transfer protocol that allows viewing web pages. However, data transmitted via HTTP is not encrypted, making it vulnerable to interception by third parties.
  - **HTTPS (Hypertext Transfer Protocol Secure):** It is a secure version of HTTP that uses encryption to protect data during transmission. It is widely used on sites handling confidential information, such as passwords and financial data.

## Services and Ports

**What are Services:**
Services are programs running on computing systems that offer specific functionalities, such as web servers, email servers, databases, etc. They interact with other systems through network ports.

### Ports and Their Functions:

Ports are identification numbers used to direct network traffic to specific services on a system. Below are some common ports and the services that typically run on them:

- Port 80 (HTTP): Used for web servers that serve web pages.
- Port 443 (HTTPS): Used for web servers offering a secure (HTTPS) connection with encryption.
- Port 25 (SMTP): Used for sending and receiving emails.
- Port 22 (SSH): Provides secure access to servers for administration.
- Port 3306 (MySQL): Used for MySQL databases.
- Port 21 (FTP): Used for file transfer via FTP.
- Port 53 (DNS): Used for domain name resolution queries.
- Port 3389 (RDP): Used for Microsoft Remote Desktop Protocol (RDP).
- Port 67/68 (DHCP): Used for automatic IP address assignment (DHCP).

## Honeypots:

- Honeypots are trap systems designed to lure attackers and study their behavior, serving as valuable tools in the detection and research of cybersecurity threats.

- **Setting up a Honeypot:** Learn how to set up a honeypot in your network to monitor suspicious activities and understand attackers' tactics.

    - **Examples of Tools:**
        - **Honeyd:** A tool that allows simulating multiple operating systems and services to attract attackers.
        - **Snort:** Besides being an IDS/IPS, Snort can be configured to function as a honeypot, identifying and recording malicious activities.
        - **Cowrie:** An SSH honeypot that records interactions with attackers attempting unauthorized access.

    - **Varieties of Honeypots:**
        - **Low-Interaction Honeypots:** Emulate services or operating systems in a limited manner, providing security without exposing the environment to significant risks.
        - **High-Interaction Honeypots:** Are more complex, allowing a more realistic interaction, but also pose a higher risk as attackers may access a system closer to a production environment.

    - **Honeypots by Configuration (Examples)**
        - **Subdomain Honeypots:** Can be configured to simulate vulnerable subdomains, attracting attackers seeking to exploit these weaknesses.
        - **Port-based Honeypots:** By focusing on specific ports, these honeypots can attract attackers targeting specific services.

    - **Benefits:**
        - Proactive Identification: Allows the identification of threats before they reach critical systems.
        - Tactic Research: Offers insights into attackers' tactics, techniques, and procedures (TTPs).
        - Continuous Learning: Contributes to the constant improvement of security posture based on identified threats.

When implementing honeypots, it is crucial to tailor the strategy to the specific needs of your network, choosing the appropriate variety and configuration to meet security objectives.

## Subdomains:

- Subdomains are extensions of a primary domain, such as "blog.example.com." It's essential to secure subdomains as they can be used to bypass the root domain's firewall.

- **Subdomain Enumeration:** Use subdomain enumeration tools to identify and assess subdomains within a primary domain. This helps ensure the security of the entire infrastructure.

## MITM (Man-in-the-Middle):

- MITM attack involves an attacker intercepting communication between two parties, allowing the capture of sensitive data. Using HTTPS helps protect against this type of attack as information is encrypted in HTTPS, but not in HTTP.

- **Conducting a Controlled MITM Attack:** Practice conducting a MITM attack in a controlled environment to understand vulnerabilities and learn how to defend against them.

## Why Some Ports Remain Open:

- Ports are left open to facilitate communication between systems. For example, port 80 (HTTP) must be open for web browsers to connect to a web server, and port 443 (HTTPS) is used for secure connections. However, keeping unused ports open can be risky. It's important to close or restrict unnecessary ports to reduce the risk of exploitation by hackers.

- **Port Scanning:** Learn how to use port scanning tools to identify open ports on a system and assess their security.

# Firewall

**What is a Firewall:**

A firewall is a device or software that monitors and controls network traffic based on security rules. It acts as a barrier between networks, deciding which data can enter or exit. There are two main types of firewalls:

- **Hardware Firewall:** Physical devices that filter traffic before entering the network.
- **Software Firewall:** Applications installed on systems to control traffic.

## How a Firewall Works:

A firewall operates based on rules that determine which data packets are allowed or blocked. These rules are configured by network administrators and can vary according to the organization's security needs and policies. Here is an overview of how a firewall works:

1. **Packet Inspection:** The firewall examines each data packet entering or leaving the network. It checks information such as the source address, destination address, service type, and port.

2. **Rule Matching:** Based on the configured rules, the firewall determines whether the packet meets the allowed criteria. If it matches an allow rule, the packet is released. Otherwise, it is blocked.

3. **Network Address Translation (NAT):** In addition to packet filtering, the firewall can use Network Address Translation (NAT) to translate IP addresses and ports used by internal devices. This allows devices on a private network to share a single public IP address for internet access, saving public IP addresses and protecting internal devices from external threats.

4. **Types of Firewalls:**
   - **Packet Filtering Firewall:** This type of firewall examines individual packets and makes decisions based on information in the packet headers. It is effective but doesn't consider the connection state.
   - **Stateful Firewall:** A stateful firewall tracks the state of connections. It can recognize established connections and allow packets associated with those connections. This improves security by preventing unauthorized connections.
   - **Proxy Firewall:** A proxy firewall acts as an intermediary between the internal network and the external network. It receives requests from the internal network, forwards those requests to the external network, and returns responses. This helps hide information about the internal network and enhances security.

5. **DHCP Service and Firewall:** The Dynamic Host Configuration Protocol (DHCP) service is commonly run on firewalls to automatically assign IP addresses to devices on a network. The firewall can manage the DHCP service to ensure that only authorized devices receive IP addresses.

6. **Intrusion Detection System (IDS):** In addition to firewall rules, intrusion detection systems (IDS) monitor the network for suspicious activities or abnormal behavior. When the IDS detects a potential intrusion, it generates alerts so that the security team can take appropriate actions.

7. **Intrusion Prevention System (IPS):** The intrusion prevention system (IPS) operates more proactively than a traditional firewall. It can automatically block traffic identified as a threat, preventing intrusions from occurring.

The firewall plays a critical role in protecting the network from cyber threats by allowing legitimate traffic, blocking unwanted traffic, and, in some cases, using NAT to manage internet access from internal devices.

# Antivirus Operation

An antivirus is an essential tool to protect systems against malware threats, including viruses, worms, trojans, and other types of malicious software. Let's explore in detail how an antivirus operates to ensure system security.

## Internal Database

### Definition
The antivirus maintains an internal database containing information about known viruses and malware. This database is continually updated by antivirus developers to include the latest identified threats.

### Signatures
Each known malware is associated with a unique "signature," which is a specific sequence of bytes representing a distinctive part of the malicious code. Signatures are essential for identifying and tracking the presence of malware in the system.

## Verification Process

### 1. Signature Verification
When a file is accessed or executed, the antivirus checks the file's signatures against the internal database. If there is a match, the antivirus identifies the file as a known threat and takes appropriate measures.

### 2. Heuristic Analysis
In addition to known signatures, antiviruses use heuristic analysis techniques to identify suspicious behaviors. This involves evaluating the behavior of the running program to determine if its actions resemble common characteristics of malware, even if there is no exact match with existing signatures.

### 3. Pattern Matching
Antiviruses examine the code for specific patterns associated with common malicious programming techniques. This may include sequences of instructions typical of known attacks.

### 4. Header and Tail Verification
Verification of the file's header and tail is performed to identify suspicious changes in these areas. Some malware infections may modify these parts of the files to evade traditional signature-based detection.

### 5. Continuous Updates
To remain effective against constantly evolving threats, antiviruses require regular updates. These updates include new signatures, improvements in heuristic analysis, and other adaptations to address emerging threats.

## Challenges and Limitations

Despite advanced detection mechanisms, malicious actors can create malware with unknown and unique patterns. These malwares avoid detection by conventional methods, leveraging techniques such as polymorphism, where the malicious code continuously modifies itself to evade matching known signatures. This constant challenge underscores the need for more advanced and adaptable approaches in cybersecurity to ensure effective defense against evolving threats.

## Reinforcing Knowledge: The Importance of Practice Exercises

To solidify your understanding and enhance your learning in cybersecurity and ethical hacking, it's highly recommended to perform practice exercises. These exercises can help you reinforce the concepts learned and develop practical skills. Here are some effective ways to engage in practice exercises:

- **Questions and Answers:** Formulate questions about the topics you've studied, and then try to answer them. This can help verify your knowledge and identify areas that require additional review.
- **Virtual Labs:** Set up virtual labs to practice your skills. You can use virtual environments such as virtual machines (VMs) to simulate cybersecurity scenarios and test your capabilities.
- **Problem Solving:** Challenge yourself to solve cybersecurity-related problems. This may involve identifying and addressing vulnerabilities in simulated systems.
- **Project Creation:** Start personal projects related to cybersecurity. For example, you can develop your intrusion detection system or set up a secure web server.
- **Participation in Communities:** Join online cybersecurity forums and communities to discuss topics, ask questions, and share your knowledge.
- **Capture The Flag (CTF) Challenges:** Participate in Capture The Flag (CTF) competitions, which involve solving cybersecurity puzzles and challenges. These challenges are excellent for enhancing your practical skills.

By regularly engaging in practice exercises, you not only reinforce your theoretical understanding but also build the practical experience necessary to become a competent ethical hacker. Remember that consistent practice is essential for success in cybersecurity.
