
# Computer Networking

This repo contains Computer Networking Basics for **DevOps, Cloud, and Software Engineers**.

## 📚 Table of Contents

- [Introduction](#-introduction)
- [IP Address](#-ip-address)
- [DNS](#-dns-domain-name-system)
- [Ports](#-ports)
- [Protocols](#-protocols)
- [Client Server Model](#-clientserver-model)

---

## 🚀 Introduction

Networking is the **foundation of cloud computing and DevOps**.

Whenever you:
- Open a website
- Connect to a server
- Deploy microservices
- Use Kubernetes

👉 Networking is involved.

Networking simply means:

> **Communication between multiple computers to exchange data.**

## 📌 IP Address

Every device connected to a network has a unique identifier called an **IP Address**.

Example:

```bash
192.168.1.1
```

## 🌍 DNS (Domain Name System)

Humans cannot remember IP addresses easily.

DNS converts:

google.com → 142.251.223.142

So instead of remembering numbers, we use domain names.

## 🔌 Ports

A Port identifies a specific service running on a server.

Example ports:

| Port  | Service   |
|-------|-----------|
| 80    | HTTP      |
| 443   | HTTPS     |
| 22    | SSH       |
| 3306  | MySQL     |

💡 Analogy:

IP Address = Apartment Building

Port = Apartment Number

## 📡 Protocols

Protocols define the rules for communication between computers.

Common protocols:

| Protocol | Purpose |
| -------- | ------- |
| HTTP     | Web communication  |
| HTTPS    | Secure web communication |
| SSH      | File transfer |
| FTP      | File transfer |

## 🔄 Client–Server Model

Most internet communication works using the Request–Response Model.

Client → Request → Server  
Server → Response → Client

Example:

Browser → Request webpage  
Server → Send HTML response  

## 🌐 Example: Opening a Website

When you open:

https://google.com

The process happens like this:

1️⃣ Browser sends request to DNS server  
2️⃣ DNS returns the IP address  
3️⃣ Browser connects to the server using port 443 (HTTPS)  
4️⃣ Server sends the webpage response  

## 🧠 Key Takeaways

✔ IP Address → Identifies devices  
✔ DNS → Converts domain names to IP  
✔ Ports → Identify services  
✔ Protocols → Define communication rules  

These concepts are essential for DevOps, Cloud, and Networking.
