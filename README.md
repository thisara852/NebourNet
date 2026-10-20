# 🏙️ NeighbourNet (NebourNet)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Lucide Icons](https://img.shields.io/badge/Icons-Lucide-F43F5E?style=for-the-badge&logo=feather&logoColor=white)](https://lucide.dev/)
[![Smart City](https://img.shields.io/badge/Domain-Smart_City_%26_Civic_Tech-10B981?style=for-the-badge)](https://en.wikipedia.org/wiki/Smart_city)

> **A next-generation smart city and neighborhood engagement platform connecting citizens, community events, public opinion polls, civic issue reporting, and sustainability metrics.**

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [System Architecture](#-system-architecture)
- [Pages & Directory Reference](#-pages--directory-reference)
- [Tech Stack](#-tech-stack)
- [Quick Start Guide](#-quick-start-guide)
- [Author](#-author)
- [License](#-license)

---

## 📖 Overview

**NeighbourNet** is a modern civic-tech web portal that empowers urban residents and local communities. It provides intuitive tools for viewing live urban health data, exploring an interactive infrastructure map, participating in public opinion polls, reporting neighborhood issues, tracking green sustainability goals, and discovering local community events.

---

## ✨ Key Features

### 🗺️ Interactive Smart City Map (`Smartcity.html`)
- **Visual Infrastructure Mapping:** Live map with color-coded pins for traffic, energy, community facilities, safety, and green spaces.
- **Point of Interest (POI) Details:** Clickable marker panels showing operational status, live metrics, and quick action links.
- **Dynamic Filter Pills:** Filter map markers by category in real time.

### 📊 City Health Dashboard (`city dashboard.html`)
- **Key Urban Metrics:** Real-time metrics for Air Quality Index (AQI), power grid efficiency, transit mobility, and waste management.
- **Alerts & Advisories:** Weather alerts, city notices, and municipal emergency broadcasts.

### 🗳️ Citizen Public Polling (`Public Polls.html`)
- **Democratic Community Votes:** Vote on neighborhood improvements (e.g., bike paths, park renovations, community hours).
- **Instant Calculations:** Real-time visual progress bars displaying updated vote counts and percentages.
- **Discussion Feed:** Public comment section under each poll for community discussion.

### 🚧 Community Issue & Traffic Tracker (`trafic.html`)
- **Incident Reporting:** Report local issues such as potholes, traffic snarls, broken street lights, and road hazards.
- **Resolution Tracking:** Follow issues across their lifecycle (`Reported` ➔ `In Progress` ➔ `Resolved`).

### 🌿 Sustainability & Eco Tracker (`envi.html`)
- **Green City Goals:** Neighborhood carbon emission stats, tree planting campaigns, recycling metrics, and renewable energy usage.

### 🤝 Community Bulletin & Volunteer Board (`community.html`)
- **Local Events & Drives:** Discover community cleanups, gardening days, charity marathons, and food distribution events.
- **Event Filtering & RSVP:** Filter activities by category with participant counters.

### 📱 Citizen Onboarding & Mobile Guide (`Mobile Guide.html`, `journy.html`)
- Step-by-step visual onboarding guides for mobile and web accessibility.

### 🔐 Authentication Portal (`Signin.html`, `signup.html`, `registration.html`)
- Resident sign-in, account creation, and user profile management.

---

## 🏗️ System Architecture

```mermaid
graph TD
    User([Citizen / Resident]) --> Portal[NeighbourNet Web Portal]
    Portal --> Map[Interactive Smart City Map]
    Portal --> Dash[City Health Dashboard]
    Portal --> Polls[Public Opinion Polling]
    Portal --> Issues[Community Issue Tracker]
    Portal --> Eco[Sustainability & Eco Tracker]
    Portal --> Comm[Community Events Board]
