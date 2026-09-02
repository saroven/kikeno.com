# KiKeno — Knowledge Hub & Learning Ecosystem

[![Project Status: Active Development](https://img.shields.io/badge/Project%20Status-Active%20Development-brightgreen)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#)
[![Language: English & Bangla](https://img.shields.io/badge/Platform-Q%26A%20%26%20Learning-orange)](#)

> **"Ask, Discover, Understand & Learn"** — A modern community Q&A forum, deep-dive explanation hub, product/tech comparison engine, and self-paced learning roadmap platform.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Ecosystem Architecture](#-ecosystem-architecture)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Planning & Documentation](#-planning--documentation)
- [Getting Started](#-getting-started)
- [License](#-license)

---

## 📖 Overview

**KiKeno** is a comprehensive community forum, knowledge-sharing platform, and interactive learning ecosystem. Users can ask questions, receive answers from experienced community members, explore deep-dive explanations on complex technical topics, compare product and technology options side-by-side, and follow structured learning roadmaps with free guides and master cheatsheets.

---

## ✨ Key Features

- 🔍 **Discover (Janun)**: Search and explore topics across technology, finance, health, career, and gadgets.
- 💡 **Understand (Bujhun)**: In-depth analytical answers and explanations breaking down complex topics.
- ⚖️ **Compare (Tulona)**: Feature comparison matrices (e.g., SSD vs HDD, FDR vs DPS, Laravel vs Node.js).
- 🎓 **Learn (Shikhun)**: Chapter-by-chapter learning guides, interactive roadmaps, cheatsheets, and progress tracking.
- 🌗 **Dark / Light Theme**: Premium visual design system with smooth transitions, modern typography, and glassmorphism styling.
- 🗳️ **Voting & Reputation**: Community-driven upvoting, downvoting, and accepted answer badges.

---

## 🌐 Ecosystem Architecture

KiKeno guides users through a 4-step knowledge journey:

```
[ Search / Ask Question ] ➔ [ Discover Information ] ➔ [ Understand Concepts ] ➔ [ Compare Options ] ➔ [ Master via Learning Pathways ]
```

---

## 🛠️ Tech Stack

### Frontend Prototype
- **HTML5**: Accessible, semantic layout structure with meta SEO optimization.
- **CSS3**: Custom CSS design system with CSS variables, responsive grid, and native dark/light mode toggle.
- **Typography**: Google Fonts (Hind Siliguri, Inter, Playfair Display).

### Backend & Database (Planned)
- **Backend Framework**: Laravel (PHP) / Node.js (Express/NestJS) REST API.
- **Database**: MySQL / MariaDB / PostgreSQL (using `utf8mb4_unicode_ci`).
- **Authentication**: JWT / Session-based Auth with Role-Based Access Control (RBAC).

---

## 📁 Project Structure

```
kikeno.com/
├── README.md               # Main project documentation and guide
├── PROJECT_PLANNING.md     # Vision, user roles, feature breakdown & roadmap
├── DATABASE_PLANNING.md    # ER diagram, table schemas, relationships & SQL scripts
├── index.html              # Frontend web UI prototype & design system
├── v2.html                 # UI layout backup/variant
└── assets/                 # Image assets and thumbnails
    └── images/
```

---

## 📚 Planning & Documentation

Detailed project architecture and database design documents are available in the repository:

- 📋 [**Project Planning (PROJECT_PLANNING.md)**](PROJECT_PLANNING.md) — Comprehensive vision, user roles, module definitions, non-functional requirements, and development milestones.
- 🗄️ [**Database Planning (DATABASE_PLANNING.md)**](DATABASE_PLANNING.md) — Entity-Relationship (ER) diagram, table schemas, index strategies, foreign keys, and ready-to-use DDL SQL migration scripts.

---

## 🚀 Getting Started

1. Clone or navigate to the repository:
```bash
git clone https://github.com/saroven/kikeno.com.git
cd kikeno.com
```

2. Open `index.html` in your browser or run a local HTTP server:
```bash
# Python local server
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

---

## 📄 License

This project is licensed under the MIT License.