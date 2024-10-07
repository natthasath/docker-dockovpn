# 🎉 Docker Dockovpn

Dockovpn is an open-source, Docker-based VPN server solution using OpenVPN, enabling secure remote access to networks. It simplifies deployment with Docker Compose, providing flexible port configuration and dynamic DNS support, ensuring privacy and protection for users.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### ✅ Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- Dynamic DNS Thailand is [AIS THDDNS](https://www.thddns.net/) or [TRUE DDNS](https://trueddns.com/)
- OpenVPN Connect [Play Store](https://play.google.com/store/apps/details?id=net.openvpn.openvpn&hl=en) or [App Store](https://apps.apple.com/us/app/openvpn-connect-openvpn-app/id590379981)

### 🚀 Setup

1. Download and Install Docker Desktop
2. Configuration IPv4 Mapping `External Port` and `Internal Port`
3. Enable External Port in Dynamic DNS
4. Configuration file `.env`
5. Edit file `client.ovpn` line is `remote {HOST_ADDR} {External_Port}`

### 🏆 Run

- [http://localhost:1194/](http://localhost:1194/) username : `admin` password : `admin`

```shell
docker-compose up -d
```
