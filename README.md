# 🎯 网络安全新手实验室 / Cybersecurity Beginner Lab

一个集成了多种Web安全测试环境的VMware本地化虚拟机靶场平台 / A VMware-based localized virtual machine platform integrating multiple web security testing environments  
基于Ubuntu 22.04 系统搭建，包含DVWA、Pikachu、XSS-labs、sqli-labs等经典漏洞练习环境 / Built on Ubuntu 22.04 with classic vulnerability practice environments including DVWA, Pikachu, XSS-labs, sqli-labs, etc.



![Security](https://img.shields.io/badge/Security-Pentesting-blue) 
![Docker](https://img.shields.io/badge/Container-Docker-green)
![Halo](https://img.shields.io/badge/CMS-Halo-9cf)



## 🖼️ 实验室概览 / Lab Overview

###  ![Main Interface](https://cloud.komll.com/f/anSK/Komll-Labs.jpg)  



## ⚡ 快速开始 / Quick Start
### 开始 / Getting Started

- [安装 VMware Workstation Pro]() / [Install VMware Workstation Pro]()
- 解压压缩包 / Extract the compressed package
- 点击靶场.vmx / Click the "靶场.vmx" file

### 访问方式 / Access Methods

**默认HTTPS服务 / Default HTTPS Service**  
🔗 [https://localhost:8443](https://localhost:8443)  
切记使用 **https://** 否则无法访问 / Remember to use **https://** otherwise access will fail

> 📌 如需使用80端口版本，请恢复至【靶场 V1.1 快照 80 端口版】/ To use the 80-port version, please restore to [靶场 V1.1 快照 80 端口版] snapshot

### 技术栈 / Tech Stack
- Web服务器 / Web Server: Apache (自签名SSL证书 / Self-signed SSL certificate)
- 数据库 / Database: MySQL 8
- PHP: 8.1
- CMS: [Halo](https://halo.run)
- Halo容器 / Halo Container: Docker

## 🗃️ 集成靶场 / Integrated Labs

| 靶场名称 / Lab Name | 本地状态 / Local Status | 访问方式 / Access Method | 默认凭证 / Default Credentials |
|---------------------|-------------------------|--------------------------|--------------------------------|
| DVWA        | ✅ 本地 / Local   | `/labs/dvwa`             | admin/password |
| Pikachu     | ✅ 本地 / Local   | `/labs/pikachu`          | -              |
| XSS-labs    | ✅ 本地 / Local   | `/labs/xss-labs`         | -              |
| sqli-labs   | ✅ 本地 / Local   | `/labs/sqli-labs`        | -              |
| upload-labs | 🌐 在线 / Online  | [c0ny1在线版 / Online Version](https://upload-labs.bachang.org/) | - |

> 📝 upload-labs因PHP兼容性问题采用外部链接方案 / upload-labs uses an external link solution due to PHP compatibility issues.  
> 特别感谢 / Special thanks to [c0ny1](https://github.com/c0ny1) for the online upload-labs project.  
> 如有版权问题请联系 / For copyright issues please contact: mu@smmna.cn

## 🔐 认证信息 / Authentication Info

| 服务 / Service       | 用户名 / Username | 密码 / Password |
|----------------------|-------------------|-----------------|
| Ubuntu系统 / Ubuntu OS | ubuntu | labs7788 |
| root账户 / root account | root   | labs7788 |
| Halo后台 / Halo Admin | ubuntu | labs7788 |
| DVWA       | admin  | password |

## ⚠️ 注意事项 / Important Notes
1. 首次访问需信任自签名SSL证书 / First access requires trusting the self-signed SSL certificate
2. 建议在隔离网络环境中使用 / Recommended to use in an isolated network environment
3. 所有服务密码请及时修改以保证安全 / Change all service passwords promptly for security

## 📜 版本历史 / Version History
- **V1.1**: 80端口基础版 / 80-port basic version（需通过快照恢复至【靶场 V1.1 快照 80 端口版】/ Need to restore to [靶场 V1.1 快照 80 端口版] snapshot）
- **Current**: 8443端口HTTPS版 / 8443-port HTTPS version

---

