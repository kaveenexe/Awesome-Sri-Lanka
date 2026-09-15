# Awesome Sri Lanka 🇱🇰

[![Awesome Sri Lanka](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome APIs, datasets, open source projects, and developer resources related to Sri Lanka. Perfect for developers, researchers, and entrepreneurs building applications for the Sri Lankan market.

## 📑 Table of Contents

- [Government APIs & Open Data](#government-apis--open-data)
- [Telecommunications APIs](#telecommunications-apis)
- [Financial & Economic Data](#financial--economic-data)
- [News & Media APIs](#news--media-apis)
- [Language & Translation](#language--translation)
- [Open Source Projects](#open-source-projects)
- [Datasets](#datasets)
- [Developer Communities](#developer-communities)
- [Educational Resources](#educational-resources)
- [Research & Analytics](#research--analytics)

---

## 🏛️ Government APIs & Open Data

### Official Government Portals
- **[Sri Lanka Open Data Portal](https://data.gov.lk)** - Official government open data initiative
  - **API Endpoints:**
    - Package List: `https://data.gov.lk/api/3/action/package_list`
    - Data JSON: `https://data.gov.lk/data.json`
  - **Coverage:** Agriculture, demography, economy, transport, IT, cybersecurity

- **[Ministry of Health Open Data Portal](https://data.health.gov.lk)** - Health statistics and digital health data
  - **API Endpoints:**
    - CKAN API: `https://data.health.gov.lk/api/3`
    - Package Search: `https://data.health.gov.lk/api/3/action/package_search`
    - Package List: `https://data.health.gov.lk/api/3/action/package_list`

- **[Department of Agriculture API](https://api.doa.gov.lk)** - Real-time and historical agricultural data
  - **Base URL:** `https://api.doa.gov.lk/v1`
  - **Key Features:** Crop data, agricultural statistics, weather data
  - **Authentication:** API key required
  - **Example:** `https://api.doa.gov.lk/v1/crops?access_key=YOUR_ACCESS_KEY`

### Upcoming Government APIs
- **Government API Policies** - New API guidelines and policies being developed for cross-government integration
- **Agriculture Enterprise Architecture APIs** - APIs for agricultural sector being built through FAO collaboration

---

## 📱 Telecommunications APIs

### GSMA Open Gateway Initiative
All four major Sri Lankan mobile operators have launched commercial network APIs:

- **Dialog Axiata PLC**
- **Bharti Airtel Lanka**
- **Hutchison Telecommunications Lanka**
- **SLT-Mobitel**

**Available APIs:**
- **One Time Password (OTP) Validation**
- **Device Location**
- **Carrier Billing**

### Dialog Specific APIs
- **[IdeaMart Platform](https://chat.ideabiz.lk)** - Dialog's service delivery platform
  - SMS API
  - USSD API
  - Charging as a Service (CaaS) API
  - **New:** AI Assistant for developers (Sri Lanka's first AI assistant for developer community)

---

## 💰 Financial & Economic Data

### Central Bank of Sri Lanka
- **[Central Bank Statistics](https://www.cbsl.gov.lk/en/statistics)** - Comprehensive economic data
  - **Economic Data Library** - Search and generate reports on economic indicators
  - **Daily/Weekly/Monthly Economic Indicators**
  - **Real Sector, External Sector, Fiscal Sector, Monetary Sector data**
  - **Sri Lanka Prosperity Index**
  - **Workers' Remittances and Labour Migration data**

### Colombo Stock Exchange (CSE)
- **[CSE Mobile App](https://apps.apple.com/app/cse-mobile-app/id888273823)** - Real-time market data
  - Real-time market updates
  - Research and analytical tools
  - Corporate news and disclosures
  - **Note:** No public API available yet, but app provides comprehensive market data

### Department of Census and Statistics
- **[Official Statistics Portal](https://www.statistics.gov.lk)** - National statistical data
  - **Lanka Datta** - Microdata catalog for academic research
  - Census of Population and Housing 2024
  - Economic Census data
  - Household surveys and microdata

---

## 📰 News & Media APIs

### International News APIs with Sri Lanka Coverage
- **[NewsData.io](https://newsdata.io/news-sources/Sri-Lanka-news-api)** - Sri Lanka news headlines
  - **Country Parameter:** `LK`
  - **Example:** `https://newsdata.io/api/1/latest?country=lk&apikey=YOUR_API_KEY`

- **[APITube News API](https://apitube.io/solutions/search-news-in-sri-lanka)** - Comprehensive news search
  - Historical data from 1998
  - Multiple export formats (JSON, XML, CSV)
  - Sentiment analysis and trend monitoring

---

## 🗣️ Language & Translation

### Sinhala Language Resources
- **[Sinhala Unicode Block](https://si.wikipedia.org/wiki/Sinhala_(Unicode_block))** - Unicode standards for Sinhala
  - **Range:** U+0D80..U+0DFF (128 code points)
  - **Scripts:** Sinhala, Pali, Sanskrit

### Translation APIs
- **[Lingvanex Sinhala APIs](https://lingvanex.com/services/sinhala-translation-api/)**
  - Sinhala Dictionary API
  - Sinhala Translation API
  - Neural Machine Translation (NMT)
  - Contextual understanding

### Open Source Language Tools
- **[OpenSinhala Dictionary](https://github.com/ipmanlk/OpenSinhalaDictionary)** - Open source English-Sinhala dictionary
  - **Online Version:** https://www.zigiriweb.navinda.xyz/
  - Android app available
  - Ad-free and open source

---

## 🚀 Open Source Projects

### Community Collections
- **[OSCSL Awesome Projects](https://github.com/oscsl/awesome-projects)** - Curated list of Sri Lankan open source projects

### Notable Projects
**Web Development & Frameworks**
- **AnimTrap** - CSS Framework for web animations
- **NeutralinoJS** - Portable cross-platform application framework
- **React OffCanvas Component** - Animated sidebars for React
- **ReactJS VideoBG** - Background videos for React apps

**Developer Tools**
- **gh-code** - VS Code plugin for GitHub issues
- **jerverless** - On-premise serverless functions
- **kache** - Redis-compatible in-memory database (Go)
- **timercpp** - JavaScript-like setTimeout for C++

**Language & Localization**
- **OpenSinhala Dictionary Plus** - Web-based dictionary with APIs
- **open-unicode-converter** - Singlish typing tool
- **sinhala-sub-maker** - English to Sinhala subtitle translator
- **OSDB-Project** - 100k+ English-Sinhala definitions database

**Utilities**
- **CeylonNews** - Trilingual news reader
- **topjobs-scraper** - Job listings scraper for topjobs.lk
- **XCalc** - Calculator with prime/factorize functions
- **YouTubeDownloader Bot** - Viber bot for YouTube downloads

### Government Projects (Lanka Software Foundation)
- **Election Management System** - Integrated system for Sri Lankan elections
- **Student Information Management System** - 4.3M students, 10K+ schools
- **National Passenger Service Platform** - Multimodal transport system

---

## 📊 Datasets

### Humanitarian & Development Data
- **[Humanitarian Data Exchange (HDX)](https://data.humdata.org/group/lka)** - 133+ datasets for Sri Lanka
  - Crisis response datasets
  - Disaster recovery data
  - Population and demographic data
  - From 44+ international organizations

### International Development Data
- **[World Bank Sri Lanka](https://www.worldbank.org/en/country/srilanka/overview)** - Economic and development indicators
- **[UNDP Sri Lanka](https://www.undp.org/gender-seal-development/sri-lanka)** - Development and gender equality data

### Displacement & Migration
- **[IOM Displacement Tracking Matrix](https://dtm.iom.int/sri-lanka)** - Population mobility data
  - Demographic data and site information
  - Quality of services assessments
  - Mobility tracking

---

## 👥 Developer Communities

### Active Communities
- **[GDG Sri Lanka](https://gdg.community.dev/gdg-sri-lanka/)** - Google Developer Group
  - **Website:** https://gdgsrilanka.org
  - **Members:** 2,860+
  - **Events:** DevFest, I/O Extended, Build with AI

- **[Sri Lanka Developer Forum](https://www.meetup.com/sldevs/)** - Largest developer community
  - Microsoft Technical Communities
  - Regular meetups and technical sessions
  - LinkedIn: [Sri Lanka Developer Forum](https://lk.linkedin.com/company/sldevforum)

- **[GitHub Community Sri Lanka](https://www.meetup.com/github-sri-lanka/)** - GitHub enthusiasts
  - **Members:** 117+
  - Open source advocacy
  - GitHub Campus Experts program

### Specialized Communities
- **[Open Source Sri Lanka (ProjectOSS)](https://github.com/open-source-srilanka)** - Open source development
- **Supabase Colombo** - Database and backend development
- **DevOps Sri Lanka** - Cloud and infrastructure communities

---

## 🎓 Educational Resources

### Organizations
- **[Lanka Software Foundation](https://opensource.lk)** - Open source development for government
  - **Founded:** 2003
  - **Chair:** Dr. Sanjiva Weerawarana (WSO2 founder)
  - **Focus:** Digital transformation, FOSS research & development

### Learning Platforms
- **Dialog IdeaBiz AI Assistant** - Technical support and documentation
- **GitHub Campus Experts** - Student developer programs
- **GDG Learning Resources** - Google technology training

---

## 🔬 Research & Analytics

### Academic Resources
- **[Columbia University Sri Lanka Research Guide](https://guides.library.columbia.edu/sasia-srilanka/data)** - Academic datasets and statistics
- **Charity & Philanthropy Research** - Economic and social development studies

### Business Intelligence
- **Sri Lanka Computer Emergency Readiness Team (SLCERT)** - AI training subsidies
- **DevOps Consulting** - Technical consulting and implementation

---

## 🤝 Contributing

We welcome contributions! Please read our [contribution guidelines](CONTRIBUTING.md) before submitting.

### How to Contribute
1. Fork this repository
2. Add your resource following the format above
3. Ensure the resource is:
   - Related to Sri Lanka
   - Actively maintained (for projects)
   - Publicly accessible
   - Well-documented
4. Submit a pull request

### Categories for New Resources
- Government services and APIs
- Developer tools and libraries
- Educational content
- Business and economic data
- Cultural and language resources

---

## 📄 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

---

## 🔗 Related Resources

- [Awesome Lists](https://awesome.re) - The awesome list phenomenon
- [Public APIs](https://github.com/public-apis/public-apis) - A collective list of free APIs
- [Open Source Guides](https://opensource.guide/) - Learn how to contribute to open source
- [HostDeFi Token Safety Snapshot](https://hostdefi.com/data/) - Free weekly dataset of token-safety grades across Solana and EVM chains, CC BY 4.0, CSV.


---

**Made with ❤️ by the Sri Lankan developer community**
<br><br>
[![Buy Me a Coffee](https://img.shields.io/badge/-Buy%20me%20a%20coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/kaveenuthtz)

*Last updated: July 2025*
