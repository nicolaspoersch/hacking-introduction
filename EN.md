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

**Essential programming languages (Python, C++, etc.):**  
Python is versatile and widely used in cybersecurity. C++ is valuable for understanding low-level vulnerabilities. Java is important for understanding Java-based applications.

## Operating Systems

**The importance of Linux for hackers:**  
Linux is preferred due to its open-source nature, flexibility, and the availability of security tools.

**Linux distributions for security:**  
Kali Linux is a distribution specialized in security that includes various useful tools. You can learn basic Kali Linux commands in (kali.org).

## Networking Knowledge

**TCP/IP protocols and how they work:**  
TCP/IP is fundamental for communication on the Internet. Understand how data is packetized, addressed, and transmitted.

**IP addressing, subnets, and routing:**  
Learn how to configure networks, including creating subnets and configuring routers.

## Information Security

**Security principles, including confidentiality, integrity, and availability:**  
Protect data by keeping it confidential, integral, and available when needed.

**Encryption and authentication:**  
Understand how encryption protects confidential information and how authentication verifies identity.

## What to Learn Initially

**What is a Network and How It Works**

### What is a Network:

A computer network is a set of interconnected devices that share resources and information. This can include computers, servers, network devices, and even the Internet. Networks allow data exchange and efficient communication between devices.

### How a Network Works:

- **Network Topology:** Networks can have various topologies, such as star, bus, and mesh. Topology defines how devices are connected.
- **Switching and Routing:** Switches and routers direct traffic on the network, allowing data to reach its destination.
- **Network Protocols:** Protocols like TCP/IP define rules for communication on a network, including data packet format and routing.

### What is the Internet

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

### Honeypots:

Honeypots are trap systems designed to attract attackers and study their behavior. They are useful for the detection and research of cyber threats.

### Subdomains:

Subdomains are extensions of a primary domain, such as "blog.example.com." It's important to secure subdomains, as they can be used to bypass the root domain's firewall.

### MITM (Man-in-the-Middle):

The MITM (Man-in-the-Middle) attack involves an attacker intercepting communication between two parties, allowing the capture of sensitive data. Using HTTPS helps protect against this type of attack because in HTTPS, information is encrypted, while in HTTP, it's not.

### Why Some Ports Remain Open:

Ports are open to allow communication between systems. For example, port 80 (HTTP) must be open for web browsers to connect to web servers, and port 443 (HTTPS) is used for secure connections. However, keeping unused ports open can be risky. It's essential to close or restrict unnecessary ports to reduce the risk of exploitation by hackers.

## Firewall

**What is a Firewall:**

A firewall is a device or software that monitors and controls network traffic based on security rules. It acts as a barrier between networks, deciding which data can enter or exit. There are two main types of firewalls:

- **Hardware Firewall:** Physical devices that filter traffic before entering the network.
- **Software Firewall:** Applications installed on systems to control traffic.

### How a Firewall Works:

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

## Reinforcing Knowledge: The Importance of Practice Exercises

To solidify your understanding and enhance your learning in cybersecurity and ethical hacking, it's highly recommended to perform practice exercises. These exercises can help you reinforce the concepts learned and develop practical skills. Here are some effective ways to engage in practice exercises:

- **Questions and Answers:** Formulate questions about the topics you've studied, and then try to answer them. This can help verify your knowledge and identify areas that require additional review.
- **Virtual Labs:** Set up virtual labs to practice your skills. You can use virtual environments such as virtual machines (VMs) to simulate cybersecurity scenarios and test your capabilities.
- **Problem Solving:** Challenge yourself to solve cybersecurity-related problems. This may involve identifying and addressing vulnerabilities in simulated systems.
- **Project Creation:** Start personal projects related to cybersecurity. For example, you can develop your intrusion detection system or set up a secure web server.
- **Participation in Communities:** Join online cybersecurity forums and communities to discuss topics, ask questions, and share your knowledge.
- **Capture The Flag (CTF) Challenges:** Participate in Capture The Flag (CTF) competitions, which involve solving cybersecurity puzzles and challenges. These challenges are excellent for enhancing your practical skills.

By regularly engaging in practice exercises, you not only reinforce your theoretical understanding but also build the practical experience necessary to become a competent ethical hacker. Remember that consistent practice is essential for success in cybersecurity.