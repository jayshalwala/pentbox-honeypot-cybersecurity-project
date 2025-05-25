# 🕵️ Pentbox Honeypot Deployment

This project demonstrates a simple low-interaction **honeypot** using [Pentbox](https://github.com/technicaldada/pentbox), a lightweight security toolkit for penetration testing and network monitoring.

## 🔍 What Is a Honeypot?

A **honeypot** is a fake system designed to attract cyber attackers and log their activity. It helps identify malicious IPs, understand attack methods, and strengthen your defense.

---

## 📦 Tools Used

- 🛠️ **Pentbox v1.8**
- 🐧 Linux (Kali)
- 🖥️ Bash + Terminal

---

## 🚀 How It Works

1. Launch Pentbox in interactive mode
2. Enable the **Network Honeypot** on a custom port (e.g., `2222`)
3. Collect and log connection attempts from unauthorized IPs

---

## 📂 Logs

Sample logs are stored in the `pentbox_logs/` folder.

```log
2025-05-24 21:34:14 Connection from IP: 10.0.0.156 | Port: 40838 | Message: INTRUSION ATTEMPT DETECTED!
