# 🔍 DORKX - Advanced Dorking Tool for Termux

**DORKX** is a powerful, professional dorking tool designed for Termux (Android) and Linux systems. It automates Google, Bing, and DuckDuckGo dorking to find exposed sensitive information, admin panels, personal data (NIK, NISN, KK), database files, and much more.

Developed by **Lukash** for security researchers and penetration testers.

---

## 🚀 Features

| Feature | Description |
|---------|-------------|
| 🔐 **Admin Login Finder** | Find admin panels on single or mass targets |
| 📄 **Personal Data Scraper** | Find NIK, NISN, KK, student data (PDF/Excel) |
| 🗄️ **Database File Finder** | Find SQL, DB, backup files exposed online |
| 🔑 **Sensitive File Finder** | Find .env, config.php, passwords, credentials |
| 🐍 **SQL Injection Scanner** | Find potential SQLi vulnerabilities |
| 🔄 **Multi-Engine Support** | Google, Bing, DuckDuckGo |
| 🌐 **Proxy Support** | Auto-rotate proxies, manual proxy, proxy checker |
| ⚡ **Multi-Threading** | Fast scanning with adjustable threads |
| 💾 **Auto Download** | Download discovered files automatically |
| 📁 **Export Results** | Save results as TXT, CSV, or JSON |
| 📅 **Scheduler** | Schedule recurring scans |
| 🔍 **Status Checker** | Check HTTP status of bulk URLs |
| 🕸️ **Crawler** | Crawl internal links from target URL |
| 📊 **Compare Results** | Compare two scan result files |

---

## 📦 Installation

### Method 1: Clone Repository (Recommended)

```bash
git clone https://github.com/lukashfatality/dorkx
cd dorkx
pip install requests beautifulsoup4 schedule
python dork --help
