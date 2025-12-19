# Payloads All The Things

A list of useful payloads and bypasses for Web Application Security.
Feel free to improve with your payloads and techniques!

You can also contribute with a :beers: IRL, or using the sponsor button.

[![Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&link=https://github.com/sponsors/swisskyrepo)](https://github.com/sponsors/swisskyrepo)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Payloads%20All%20The%20Things,%20a%20list%20of%20useful%20payloads%20and%20bypasses%20for%20Web%20Application%20Security%20-%20by%20@pentest_swissky&url=https://github.com/swisskyrepo/PayloadsAllTheThings/)

An alternative display version is available at [PayloadsAllTheThingsWeb](https://swisskyrepo.github.io/PayloadsAllTheThings/).

<p align="center">
  <img src="https://raw.githubusercontent.com/swisskyrepo/PayloadsAllTheThings/master/.github/banner.png" alt="banner">
</p>

## :book: Documentation

Every section contains the following files, you can use the `_template_vuln` folder to create a new chapter:

- README.md - vulnerability description and how to exploit it, including several payloads
- Intruder - a set of files to give to Burp Intruder
- Images - pictures for the README.md
- Files - some files referenced in the README.md

You might also like the other projects from the AllTheThings family :

- [InternalAllTheThings](https://swisskyrepo.github.io/InternalAllTheThings/) - Active Directory and Internal Pentest Cheatsheets
- [HardwareAllTheThings](https://swisskyrepo.github.io/HardwareAllTheThings/) - Hardware/IOT Pentesting Wiki

You want more? Check the [Books](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/_LEARNING_AND_SOCIALS/BOOKS.md) and [YouTube channel](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/_LEARNING_AND_SOCIALS/YOUTUBE.md) selections.

## :open_file_folder: Project Structure

The repository is organized by vulnerability types, with each folder dedicated to a specific web security issue. Here's an overview of the organization:

### Core Content Folders

The repository contains folders for various web vulnerabilities including but not limited to:

- [API Key Leaks](./API%20Key%20Leaks) - Related to API key exposure and exploitation
- [Account Takeover](./Account%20Takeover) - Methods to compromise user accounts
- [Command Injection](./Command%20Injection) - Exploiting command execution vulnerabilities
- [SQL Injection](./SQL%20Injection) - Database exploitation techniques
- [XSS Injection](./XSS%20Injection) - Cross-site scripting payloads
- [XXE Injection](./XXE%20Injection) - XML external entity exploitation
- [File Inclusion](./File%20Inclusion) - Local/remote file inclusion exploits
- [Server Side Request Forgery](./Server%20Side%20Request%20Forgery) - SSRF techniques and payloads

Each vulnerability folder typically contains:
- README.md - Detailed explanation of the vulnerability, exploitation methods, and payloads
- `Files` subdirectory - Related executable files, scripts, or tools
- `Images` subdirectory - Supporting images and diagrams
- `Intruder` subdirectory - Payload collections for Burp Suite Intruder tool

### Special Directories

- [_LEARNING_AND_SOCIALS](./_LEARNING_AND_SOCIALS) - Learning resources and social links
- [_template_vuln](./_template_vuln) - Template for creating new vulnerability chapters
- [CVE Exploits](./CVE%20Exploits) - Various CVE exploit scripts
- [Methodology and Resources](./Methodology%20and%20Resources) - Penetration testing methodologies and resources covering:
  - Active Directory attacks
  - Container penetration testing (Docker/Kubernetes)
  - Windows/Linux privilege escalation
  - Various cheat sheets and techniques

## :rocket: Features and Capabilities

### Comprehensive Vulnerability Coverage
The repository covers almost all common web security vulnerability types, from classic vulnerabilities like SQL injection and XSS to newer ones like prototype pollution and prompt injection.

### Practical Payload Collections
Each vulnerability category contains extensive collections of practical payloads, categorized by different bypass techniques and exploitation methods.

### Tool Integration
Many directories include ready-to-use tool scripts such as:
- CVE exploits in the [CVE Exploits](./CVE%20Exploits) directory
- File upload bypass scripts in [Upload Insecure Files](./Upload%20Insecure%20Files)
- XSLT injection files in [XSLT Injection](./XSLT%20Injection/Files)

### Real-world Case Studies and Methodologies
The [methodology](./Methodology%20and%20Resources) directory contains penetration testing methodologies and resources, including:
- Active Directory attack techniques
- Container penetration testing (Docker/Kubernetes)
- Windows and Linux privilege escalation methods
- Various cheat sheets and technical resources

### Educational Resources
The [_LEARNING_AND_SOCIALS](./_LEARNING_AND_SOCIALS) directory provides links to books, YouTube videos, and other learning materials.

## :technologist: Contributions

Be sure to read [CONTRIBUTING.md](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/CONTRIBUTING.md)

<p align="center">
<a href="https://github.com/swisskyrepo/PayloadsAllTheThings/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=swisskyrepo/PayloadsAllTheThings&max=36" alt="sponsors-list" >
</a>
</p>

Thanks again for your contribution! :heart:

## :beers: Sponsors

This project is proudly sponsored by these companies.

| Logo | Description |
| --- | --- |
| [<img src="https://avatars.githubusercontent.com/u/34724717?s=40&v=4" alt="sponsor-serpapi">](https://serpapi.com) | **SerpApi** is a real time API to access Google search results. It solves the issues of having to rent proxies, solving captchas, and JSON parsing. |
| [<img src="https://avatars.githubusercontent.com/u/50994705?s=40&v=4" alt="sponsor-projectdiscovery">](https://projectdiscovery.io/) | **ProjectDiscovery** - Detect real, exploitable vulnerabilities. Harness the power of Nuclei for fast and accurate findings without false positives. |
| [<img src="https://avatars.githubusercontent.com/u/48131541?s=40&v=4" alt="sponsor-vaadata">](https://www.vaadata.com/) | **VAADATA** - Ethical Hacking Services |

---

## 中文版本

### 项目概述

Payloads All The Things 是一个关于Web应用程序安全的有效载荷和绕过技术的列表。您可以自由地用您的有效载荷和技术来改进它！

### 项目结构

该仓库按漏洞类型组织，每个文件夹专门针对特定的网络安全问题。以下是组织结构概述：

#### 核心内容文件夹

仓库包含各种Web漏洞的文件夹，包括但不限于：

- [API Key Leaks](./API%20Key%20Leaks) - 与API密钥暴露和利用相关
- [Account Takeover](./Account%20Takeover) - 用户账户接管的方法
- [Command Injection](./Command%20Injection) - 命令执行漏洞的利用
- [SQL Injection](./SQL%20Injection) - 数据库利用技术
- [XSS Injection](./XSS%20Injection) - 跨站脚本攻击载荷
- [XXE Injection](./XXE%20Injection) - XML外部实体漏洞利用
- [File Inclusion](./File%20Inclusion) - 本地/远程文件包含漏洞利用
- [Server Side Request Forgery](./Server%20Side%20Request%20Forgery) - SSRF技术和载荷

每个漏洞文件夹通常包含：
- README.md - 漏洞的详细说明、利用方法和载荷
- `Files` 子目录 - 相关的可执行文件、脚本或工具
- `Images` 子目录 - 支持图片和图表
- `Intruder` 子目录 - Burp Suite Intruder工具的载荷集合

#### 特殊目录

- [_LEARNING_AND_SOCIALS](./_LEARNING_AND_SOCIALS) - 学习资源和社交链接
- [_template_vuln](./_template_vuln) - 创建新漏洞章节的模板
- [CVE Exploits](./CVE%20Exploits) - 各种CVE漏洞利用脚本
- [Methodology and Resources](./Methodology%20and%20Resources) - 渗透测试方法学和资源，涵盖：
  - Active Directory攻击
  - 容器渗透测试(Docker/Kubernetes)
  - Windows/Linux提权
  - 各种备忘录和技术

### 功能特性

#### 全面的漏洞覆盖
该仓库涵盖了几乎所有常见的Web安全漏洞类型，从经典的SQL注入和XSS漏洞到较新的原型污染和提示注入等漏洞。

#### 实用的载荷集合
每个漏洞类别都包含大量按不同绕过技术和利用方法分类的实际载荷。

#### 工具集成
许多目录包含即用型工具脚本，例如：
- [CVE Exploits](./CVE%20Exploits) 目录中的CVE利用脚本
- [Upload Insecure Files](./Upload%20Insecure%20Files) 中的文件上传绕过脚本
- [XSLT Injection](./XSLT%20Injection/Files) 中的XSLT注入文件

#### 实际案例和方法学
[methodology](./Methodology%20and%20Resources) 目录包含渗透测试方法学和资源，包括：
- Active Directory攻击技术
- 容器渗透测试(Docker/Kubernetes)
- Windows和Linux提权方法
- 各种备忘录和技术资源

#### 教育资源
[_LEARNING_AND_SOCIALS](./_LEARNING_AND_SOCIALS) 目录提供了书籍、YouTube视频和其他学习材料的链接。

### 贡献

请务必阅读 [CONTRIBUTING.md](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/CONTRIBUTING.md)