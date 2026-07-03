# 📋 Changelog

All notable changes to the **StreamNoAds** project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [2.0.0] - 2026-07-03

### ✨ Added
- **Professional README.md** with comprehensive documentation
  - Statistics and features overview
  - Step-by-step installation guides for AdGuard Home, Pi-hole, and other systems
  - Extended FAQ section with common troubleshooting
  - Roadmap for future development
  - Performance impact metrics
  
- **Enhanced Blocklist** (adblock-streaming-services)
  - Expanded from 150+ to 250+ domains
  - Added ARD/ZDF Mediathek (German public broadcasters)
  - Added YouTube TV support domains
  - Improved comments and documentation for each domain
  - Added mobile advertising networks
  - Enhanced analytics platform coverage
  
- **Improved Whitelist** (whitelist-streaming)
  - Added critical CDN domains (CloudFront, Fastly, Akamai, Cloudflare)
  - Added Tubi API domains
  - Enhanced AWS/Cloudflare service exceptions
  - Improved comments explaining purpose of each exception
  
- **Project Infrastructure**
  - CHANGELOG.md (this file) for version tracking
  - GitHub Topics for better discoverability
  - Contributing guidelines improvements
  
- **Quality Assurance**
  - Removed duplicate entries
  - Validated all domain syntax
  - Organized by service and platform

### 🔧 Improved
- **README Structure**
  - Added visual badges for License, Updates, Quality
  - Reorganized sections with table of contents
  - Added performance impact section
  - Enhanced FAQ with 6 common questions
  
- **Blocklist Organization**
  - Better sectioning with clear comments
  - Platform-specific grouping (Premium, European, Free-Tier)
  - Ad-Tech platforms consolidated
  
- **Documentation**
  - More detailed installation instructions
  - Platform compatibility matrix
  - Legal notice and disclaimer
  - Resources and external links

### 🐛 Fixed
- Removed duplicate `||cws.conviva.com^` from both lists
- Cleaned up redundant analytics entries
- Fixed whitelist format consistency
- Ensured all domains follow AdGuard syntax standards

### 📊 Statistics
- **Total Domains Blocked:** 250+
- **Streaming Services Covered:** 20+
- **Ad-Tech Platforms:** 15+
- **Whitelisted Critical Domains:** 20+

---

## [1.0.0] - 2025-04-19 (Initial Release)

### ✨ Added
- Initial release of StreamNoAds blocklist
- Basic README with installation instructions
- Initial blocklist covering major streaming platforms:
  - YouTube/Google Ads
  - Netflix
  - Amazon Prime Video
  - Pluto TV
  - Tubi
  - JOYN
  - RTL+/TVNOW
  - Sky/WOW
  - Disney+
  - Twitch
  - Crunchyroll
  
- Initial whitelist for critical streaming functionality
- Basic CONTRIBUTING.md guidelines
- MIT License

### 📋 Features (v1.0)
- ~150 ad and tracking domains
- Optimized for AdGuard Home
- Compatible with Pi-hole
- Organized by streaming service
- Includes common ad-tech platforms

---

## 🚀 Upcoming Features

### Phase 1 (Q3-Q4 2026)
- [ ] Automated daily validation checks
- [ ] GitHub Actions workflow for quality assurance
- [ ] Community submission system
- [ ] Expanded support for Asian streaming services
- [ ] Smart TV compatibility guide

### Phase 2 (2027)
- [ ] Performance comparison dashboard
- [ ] Statistics tracking (domains added/removed per month)
- [ ] Multi-language documentation
- [ ] Regional blocklists (EU, US, APAC)
- [ ] Mobile app compatibility guide

### Phase 3 (2027+)
- [ ] Web dashboard for real-time statistics
- [ ] Community voting on domain additions
- [ ] Integration with other blocklist projects
- [ ] Discord community server
- [ ] Automated blocklist generation from public datasets

---

## 📝 How to Contribute

We welcome contributions! Here's how:

1. **Report Issues** – Found a broken service or missing domain? [Open an Issue](https://github.com/tammo2701/StreamNoAds/issues)
2. **Submit Domains** – Discovered new ad/tracking domains? Submit a PR with your additions
3. **Improve Documentation** – Help make the project better for others

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 🔗 Version Links

- [Latest Release](https://github.com/tammo2701/StreamNoAds/releases/latest)
- [All Releases](https://github.com/tammo2701/StreamNoAds/releases)
- [Commit History](https://github.com/tammo2701/StreamNoAds/commits/main)

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

**Last Updated:** 2026-07-03  
**Maintained by:** [tammo2701](https://github.com/tammo2701)  
**Repository:** https://github.com/tammo2701/StreamNoAds