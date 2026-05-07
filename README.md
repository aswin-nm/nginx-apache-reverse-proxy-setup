# 🔁 Nginx + Apache Reverse Proxy Setup

## 📌 Architecture
Client → Nginx (Port 80) → Apache (Port 8080)

## 🛠️ Tools Used
- Ubuntu 22.04
- Nginx 1.28.3 (Reverse Proxy)
- Apache 2.4.66 (Backend Server)

## 📋 Steps Done
1. Installed Nginx and Apache
2. Changed Apache port to 8080
3. Configured Nginx proxy_pass
4. Opened ports with UFW firewall
5. Tested with curl -I command

## ✅ Proof
- http://192.168.1.39      → Server: nginx/1.28.3
- http://192.168.1.39:8080 → Server: Apache/2.4.66

## 📸 Screenshots
See /screenshots folder

## 📄 Config Files
See /configs folder
