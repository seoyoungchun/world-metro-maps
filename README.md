# 🚇 World Metro Maps Database

> **Official subway/metro maps and metadata for 150+ cities worldwide**

[![Cities](https://img.shields.io/badge/Cities-8%2F150-blue.svg)](./api/cities.json)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![API](https://img.shields.io/badge/API-v1.0-orange.svg)](./docs/API.md)

## 🌍 Overview

A comprehensive, open-source database of official subway/metro system maps from transportation authorities worldwide.

## 🗺️ Available Cities

| City | Country | Lines | Stations | Status |
|------|---------|-------|----------|--------|
| 🇰🇷 Seoul | South Korea | 23 | 624 | ✅ Active |
| 🇯🇵 Tokyo | Japan | 13 | 285 | 🔄 Planned |
| 🇺🇸 New York | United States | 26 | 472 | 🔄 Planned |
| 🇬🇧 London | United Kingdom | 11 | 272 | 🔄 Planned |
| 🇨🇳 Shanghai | China | 18 | 500+ | 🔄 Planned |
| 🇩🇪 Berlin | Germany | 10 | 173 | 🔄 Planned |
| 🇫🇷 Paris | France | 16 | 303 | 🔄 Planned |
| 🇪🇸 Barcelona | Spain | 8 | 166 | 🔄 Planned |

## 🚀 Quick Start

```bash
# Get all cities
curl https://raw.githubusercontent.com/username/world-metro-maps/main/api/cities.json

# Get Seoul metro data
curl https://raw.githubusercontent.com/username/world-metro-maps/main/api/v1/seoul.json
```

## 📁 Repository Structure

```
world-metro-maps/
├── 📁 maps/                 # Map files by city
├── 📁 api/                  # REST API endpoints  
├── 📁 examples/             # Sample implementations
└── 📁 docs/                 # Documentation
```

## 🤝 Contributing

Help us reach 150 cities! See [CONTRIBUTING.md](./docs/CONTRIBUTING.md)

---

Made with ❤️ for the global transit community 🌍🚇
