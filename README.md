# ⚔ LIFE RPG — Gamified Habit & Productivity Tracker

> Turn your daily habits into an RPG adventure. Track consistency, gain XP, level up your attributes and stay focused — all in one app.

![PWA](https://img.shields.io/badge/PWA-Ready-gold?style=flat-square)
![Language](https://img.shields.io/badge/Language-PT%20%7C%20EN-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Built with](https://img.shields.io/badge/Built%20with-HTML%20%7C%20CSS%20%7C%20JS-orange?style=flat-square)

---

## 🎮 Overview

**LIFE RPG** is a Progressive Web App (PWA) that gamifies habit tracking and personal productivity using RPG mechanics. Complete daily habits to earn XP, level up your character attributes, and use the built-in focus timer to track deep work sessions — all with a clean dark UI designed for mobile.

Built as a solo project to solve a real personal challenge: staying consistent with habits and productive work while managing ADHD.

---

## ✨ Features

### 🗡 Habit System
- Create habits with custom XP rewards and penalties
- Assign one or multiple RPG attributes (FOR / INT / SAB / CON)
- Set frequency by day of week
- Progressive penalty system (3+ consecutive failures = penalty doubles)
- Streak tracking with visual fire indicators
- Daily difficulty multiplier (1× / 1.5× / 2×)

### 📊 Character Attributes
- **FOR** — Fortaleza (Strength)
- **INT** — Inteligência (Intelligence)
- **SAB** — Sabedoria (Wisdom)
- **CON** — Constituição (Constitution)
- XP curve: `300 × level²` — fast early levels, meaningful late levels
- XP floor at 0 — never goes negative

### 🎯 Focus Timer
- Circular progress ring with real-time animation
- Quick presets (25 / 45 / 60 / 90 min) + custom input
- Forest app tag integration — link sessions to tags and distribute XP across multiple attributes
- Weekly focus dashboard (minutes per day chart)
- Session history with tag and XP breakdown

### ✅ To Do List
- Weekly task view with navigation (previous / next week)
- Tasks with XP, attributes, start/end dates and time
- Weekly progress bar (tasks done + XP earned vs available)
- Overdue task highlighting

### 📈 Stats & Analytics
- Attribute cards with XP bars and level display
- XP progress charts: Weekly (bar), Monthly (per attribute), Annual (contribution grid)
- 7-day consistency score
- Best streak across all habits
- Top 5 habits ranked by completion rate (last 14 days)
- Focus distribution by tag (last 30 days)

### 🔧 Other
- Dark / Light theme toggle
- Bilingual: Portuguese 🇧🇷 / English 🇺🇸
- Habit history (last 30 days) — tap any day to view
- Individual habit stats modal (streak, completion rate, XP earned, 7-day grid)
- Drag-to-reorder habits
- Level-up animation with particles and light beams
- Day-end mission recap overlay
- JSON backup export / import
- Fully offline — data stored in localStorage

---

## 🚀 Live Demo

**[https://lucasaicragb.github.io/LIFE-RPG](https://lucasaicragb.github.io/LIFE-RPG/)**

> Open in Safari on iOS → Share → Add to Home Screen to install as a native-like app.

---

## 🛠 Tech Stack

| Layer | Tech |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| Styling | CSS Custom Properties, Flexbox, Grid |
| Storage | localStorage (client-side persistence) |
| Fonts | Google Fonts — Exo 2 |
| Charts | Pure SVG (no libraries) |
| Deployment | GitHub Pages |

No frameworks. No dependencies. Single file, ~150KB.

---

## 📱 PWA Installation (iOS)

1. Open the live demo URL in **Safari**
2. Tap the **Share** button (box with arrow)
3. Scroll down → tap **"Add to Home Screen"**
4. Name it **LIFE RPG** → tap **Add**

---

## 🗂 Project Structure

```
LIFE-RPG/
├── index.html      # Entire app — HTML + CSS + JS in one file
├── README.md       # This file
└── CLAUDE.md       # AI development context (for Claude Code)
```

---

## 💡 Design Decisions

- **Single HTML file** — simplifies PWA deployment and sharing. No build step, no dependencies.
- **localStorage only** — keeps the app fully offline and private. No backend, no accounts.
- **XP floor at 0** — prevents demotivating "debt" spirals common in gamification apps.
- **Quadratic XP curve** — early levels are fast (dopamine hits), later levels take months (real achievement).
- **Progressive penalties** — habits failing 3+ days in a row double the XP penalty, creating natural urgency without being punishing from day one.

---

## 🔮 Roadmap

- [ ] Push notifications (habit reminders)
- [ ] iCloud / Google Drive auto-backup
- [ ] Forest app CSV import
- [ ] Avatar / character sprite that evolves with level
- [ ] Achievements system

---

## 👤 Author

**Lucas Garcia**
IT Freelancer — Data Analytics · AI Development · Web Apps
Perth, Australia 🇦🇺

[LinkedIn](https://www.linkedin.com/in/lucasaicragb/) · [GitHub](https://github.com/lucasaicragb)

---

## 📄 License

MIT — free to use, modify and distribute.
