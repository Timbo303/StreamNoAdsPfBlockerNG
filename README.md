# 🚀 StreamNoAds – Premium Streaming Ad Blocklist

> **Block ads on your favorite streaming services with a curated, actively maintained blocklist optimized for AdGuard Home**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026-green.svg)](CHANGELOG.md)
[![Quality Check](https://img.shields.io/badge/Quality-Validated-brightgreen.svg)](#-quality-assurance)

---

## 📋 Table of Contents

- [✨ Features](#-features)
- [📊 Statistics](#-statistics)
- [🎯 Supported Streaming Services](#-supported-streaming-services)
- [📦 Installation Guide](#-installation-guide)
- [🛠️ Compatibility](#️-compatibility)
- [❓ FAQ](#-faq)
- [🤝 Contributing](#-contributing)
- [🗺️ Roadmap](#-roadmap)
- [📄 License](#-license)

---

## ✨ Features

✅ **Comprehensive Coverage** – Blocks ads on 20+ streaming platforms
✅ **Actively Maintained** – Updated regularly with new tracking domains
✅ **Non-Invasive** – Whitelist prevents breaking core streaming functionality
✅ **AdGuard Optimized** – Crafted specifically for AdGuard Home with syntax validation
✅ **Pi-hole Compatible** – Also works with other DNS-based blockers
✅ **Well Documented** – Clear comments for each domain and platform section
✅ **Quality Assured** – Automated validation removes duplicates and syntax errors

---

## 📊 Statistics

| Metric | Count |
|--------|-------|
| **Total Blocked Domains** | 200+ |
| **Streaming Services Covered** | 20+ |
| **Ad-Tech Platforms** | 15+ |
| **Whitelisted Domains** | 15+ |
| **Last Updated** | 2026 |

---

## 🎯 Supported Streaming Services

### Premium Platforms
- 🎬 **YouTube** – YouTube ads and tracking
- 🎥 **Netflix** – Pre-roll ads and analytics
- 🏠 **Amazon Prime Video** – Amazon Ads System domains
- 🎭 **Disney+** – Ads and tracking
- 🎮 **Twitch** – Ads and analytics
- 🍿 **Crunchyroll** – Ads and tracking

### European Services
- 🇩🇪 **JOYN** (ProSiebenSat.1) – German streaming platform
- 🇩🇪 **RTL+/TVNOW** – German premium content
- 🇩🇪 **Sky/WOW** – Premium German TV
- 🇩🇪 **ARD/ZDF** – Public German broadcasters

### Free Tier Services
- 📺 **Pluto TV** – Ads and tracking
- 📺 **Tubi** – Ad-supported streaming

### Ad-Tech Platforms (Multi-Service)
- FreeWheel
- SpotX
- Yospace
- Conviva
- Moat Analytics
- IAS / Integral Ad Science

---

## 📦 Installation Guide

### 1️⃣ AdGuard Home Setup (Recommended)

**Step-by-Step Instructions:**

1. Open your **AdGuard Home Web Interface**
2. Navigate to **Filters → DNS Blocklists**
3. Click **Add Blocklist**
4. Copy and paste the following URL:
   ```
   https://raw.githubusercontent.com/tammo2701/StreamNoAds/main/adblock-streaming-services
   ```
5. Click **Save** and enable the filter
6. *(Optional)* Add the whitelist to preserve functionality:
   ```
   https://raw.githubusercontent.com/tammo2701/StreamNoAds/main/whitelist-streaming
   ```

> 💡 **Tip:** Add both blocklist and whitelist for optimal performance. The whitelist prevents login and streaming features from breaking.

### 2️⃣ Pi-hole Setup

1. Log into your **Pi-hole Admin Console**
2. Go to **Adlists**
3. Add the URL from step 4 above
4. Click **Add**
5. Perform a **gravity update** for changes to take effect

### 3️⃣ Other DNS-Based Blockers

For compatible DNS blockers (uBlock Origin, NextDNS, Quad9, etc.):
- Use the raw GitHub URL of `adblock-streaming-services`
- Follow your software's instructions for adding custom blocklists
- Syntax compatibility may vary

---

## 🛠️ Compatibility

| System | Status | Notes |
|--------|--------|-------|
| **AdGuard Home** | ✅ Fully Supported | Primary target platform |
| **Pi-hole** | ✅ Fully Supported | Tested and working |
| **AdGuard Browser** | ⚠️ Partial | Use with caution |
| **uBlock Origin** | ⚠️ Partial | May need syntax conversion |
| **Nextgen DNS** | ✅ Compatible | Standard blocklist format |

---

## ❓ FAQ

### Q: Will this block ads on all streaming platforms?
**A:** Not necessarily. This list covers major platforms where ad domains are publicly known. Some platforms use sophisticated ad delivery (server-side ads) that cannot be blocked at the DNS level.

### Q: Does this list work on mobile phones?
**A:** Yes, if you set up your phone's DNS to use AdGuard Home or Pi-hole. For native apps, effectiveness depends on the platform's implementation.

### Q: Will I lose access to my account?
**A:** No. The **whitelist ensures core functionality** (login, streaming APIs, CDNs) continues working while blocking ads.

### Q: How often is this list updated?
**A:** The list is reviewed and updated regularly. Check the [CHANGELOG](CHANGELOG.md) for latest changes.

### Q: Why are some domains whitelisted?
**A:** Some domains are used for both ads AND essential functionality (e.g., authentication, quality control). The whitelist ensures these critical services work while blocking advertising-specific domains.

### Q: Can I use this with VPNs?
**A:** Yes! AdGuard Home/Pi-hole works alongside VPN services. Just ensure your DNS is routed through AdGuard Home.

### Q: Will this work on smart TVs?
**A:** Yes. Configure your smart TV's DNS settings to point to your AdGuard Home instance.

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Report Issues
- Found an ad domain that's not blocked?
- Discovered a service breaking? 
- Open an [Issue](https://github.com/tammo2701/StreamNoAds/issues)

### Submit New Domains
- Fork the repository
- Add new ad/tracking domains to the appropriate section
- Create a Pull Request with a clear description
- Our team will validate and merge

### See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 🗺️ Roadmap

### Phase 1 (Q3 2026)
- [ ] Expand to 250+ domains
- [ ] Add YouTube TV support
- [ ] Integrate community submissions

### Phase 2 (Q4 2026)
- [ ] Automated daily updates
- [ ] Statistics dashboard
- [ ] Mobile app compatibility guide

### Phase 3 (2027)
- [ ] Region-specific blocklists (EU, US, APAC)
- [ ] Performance optimization tools
- [ ] Community Discord/Forum

---

## 📈 Performance Impact

- **Blocklist Size:** ~50KB (minimal impact on DNS performance)
- **Query Impact:** <1ms additional latency (imperceptible)
- **Memory Usage:** <5MB on typical systems
- **Update Frequency:** Weekly (can be adjusted)

---

## ⚖️ Legal Notice

> ⚠️ **Disclaimer:** This blocklist is provided for personal use only. Users are responsible for understanding their local laws regarding ad-blocking. This project is **not affiliated** with any streaming service.

---

## 🔗 Resources & Links

- 🏠 [AdGuard Home Official](https://adguard.com/en/adguard-home/overview.html)
- 🕳️ [Pi-hole Documentation](https://docs.pi-hole.net/)
- 📖 [DNS Blocklist Guide](https://en.wikipedia.org/wiki/Hosts_(file)#Blocking)

---

## 💬 Support & Community

- **Questions?** Open an [Issue](https://github.com/tammo2701/StreamNoAds/issues)
- **Want to contribute?** See [CONTRIBUTING.md](CONTRIBUTING.md)
- **Found a bug?** Report it with details about your setup

---

## 📊 Repository Stats

![GitHub Stars](https://img.shields.io/github/stars/tammo2701/StreamNoAds?style=social)
![GitHub Forks](https://img.shields.io/github/forks/tammo2701/StreamNoAds?style=social)
![License](https://img.shields.io/github/license/tammo2701/StreamNoAds)

---

## 📄 License

This project is licensed under the **MIT License** – see [LICENSE](LICENSE) file for details.

**Attribution:** If you use this list, a mention/attribution would be appreciated but is not required.

---

## 🙏 Special Thanks

- All contributors who submit domains and improvements
- AdGuard and Pi-hole communities for inspiration
- Streaming service researchers who identify ad domains

---

**Made with ❤️ by [tammo2701](https://github.com/tammo2701)**

⭐ **If you find this list useful, please consider starring the repository!**