<div align="center">

```
 ██████╗ ██████╗ ██╗███╗   ██╗██████╗ ███████╗██╗  ██╗███████╗
██╔════╝ ██╔══██╗██║████╗  ██║██╔══██╗██╔════╝╚██╗██╔╝██╔════╝
██║  ███╗██████╔╝██║██╔██╗ ██║██║  ██║█████╗   ╚███╔╝ █████╗  
██║   ██║██╔══██╗██║██║╚██╗██║██║  ██║██╔══╝   ██╔██╗ ██╔══╝  
╚██████╔╝██║  ██║██║██║ ╚████║██████╔╝███████╗██╔╝ ██╗███████╗
 ╚═════╝ ╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝╚═════╝ ╚══════╝╚═╝  ╚═╝╚══════╝
```

# ⚙ GRIND.EXE

### _Your personal DSA & Aptitude tracker — synced to GitHub, available everywhere._

<br/>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Deepayan--Thakur.github.io-00c8ff?style=for-the-badge&labelColor=0d1117)](https://Deepayan-Thakur.github.io/grind-exe)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-00ff88?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117)](https://pages.github.com)
[![No Framework](https://img.shields.io/badge/Zero_Dependencies-Pure_HTML%2FJS-ff9f1c?style=for-the-badge&labelColor=0d1117)](https://github.com/Deepayan-Thakur/grind-exe)
[![Storage](https://img.shields.io/badge/Storage-GitHub_Gist_API-a78bfa?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117)](https://gist.github.com)

<br/>

> _"The grind never stops. Every problem solved is a weapon forged."_

<br/>

</div>

---

## 📌 Table of Contents

- [What is GRIND.EXE?](#-what-is-grindexe)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Tech Stack](#-tech-stack)
- [How Data Storage Works](#-how-data-storage-works)
- [Getting Started](#-getting-started)
- [GitHub Token Setup](#-github-token-setup)
- [Deploying to GitHub Pages](#-deploying-to-github-pages)
- [Usage Guide](#-usage-guide)
- [Rank System](#-rank-system)
- [Project Structure](#-project-structure)
- [How to Update the Code](#-how-to-update-the-code)
- [Data Backup & Recovery](#-data-backup--recovery)
- [Privacy & Security](#-privacy--security)
- [Roadmap](#-roadmap)
- [Author](#-author)

---

## 🧠 What is GRIND.EXE?

**GRIND.EXE** is a production-ready, single-file web application built to track your DSA (Data Structures & Algorithms) problem-solving journey and aptitude preparation — all synced automatically to your **private GitHub Gist**, meaning your progress is **never lost**, even across devices, browsers, and days.

Built as part of a DPIIT internship portfolio and personal development toolkit by a CS Engineering student and ML Engineer, GRIND.EXE is designed to:

- Make you **feel the urgency** to solve more problems every time you open it
- Keep your progress **safe in the cloud** (your GitHub account) with zero cost
- Work **offline first** with smart local caching, and sync when connected
- Give you **data-driven insights** on exactly where to improve
- Run **anywhere** — desktop, mobile, tablet — with zero installation

---

## 🌐 Live Demo

```
https://Deepayan-Thakur.github.io/grind-exe
```

Open the link, paste your GitHub Personal Access Token once, and you're ready to track your grind. Your data will persist forever in a private Gist under your own GitHub account.

---

## ✨ Features

### 🔴 DSA Problem Tracker
- Add unlimited DSA problems with **title**, **LeetCode URL**, **difficulty** (Easy / Medium / Hard), and **topic tag**
- Click any problem card to open its LeetCode link directly in a new tab
- Click the **checkbox** to mark a problem as solved — triggers a particle burst animation
- Filter problems by difficulty or solved/unsolved status
- Search problems by title or topic tag in real time
- Delete any problem with confirmation

### 🧠 Aptitude Tracker
- Three dedicated categories: **Logical Reasoning**, **Quantitative Aptitude**, **General Intelligence**
- Same difficulty system (Easy / Medium / Hard) as DSA
- Per-category progress bars with live counters
- Search across all categories simultaneously

### ☁ GitHub Gist Cloud Sync
- All data saves to a **private GitHub Gist** in your account
- Auto-syncs after every action (debounced 1.8s to batch updates)
- Manual sync button in the settings panel
- Conflict-free merge: remote wins for solved status, local wins for new additions
- Offline-first: works from local cache when no internet, syncs when reconnected

### 📊 Analytics Dashboard
- **Animated donut chart** — Easy / Medium / Hard breakdown of solved problems
- **Aptitude breakdown** — per-category progress bars
- **Overall completion rate** with motivational tier labels
- **28-day activity heatmap** — visualises your daily grind history

### 🎯 Improvement Radar
- Personalised insights generated from your actual data
- Identifies weak areas: unattempted problem types, low completion rates
- Flags if you're ignoring aptitude entirely
- Streak warnings and encouragement
- Colour-coded severity: 🟢 Good / 🟡 Warning / 🔴 Danger

### 🔥 Streak & Rank System
- Tracks your **daily solving streak** — increments when you solve at least one problem per day
- **7 rank tiers** based on total problems solved: `NEWBIE → BEGINNER → INTERMEDIATE → ADVANCED → EXPERT → MASTER → LEGENDARY`
- Rank displayed prominently in the sidebar with dynamic colour

### 🎬 Cinematic Intro Animation
Every page load plays a 7-second animated story:
1. **Logo reveal** with glitch effect and star field
2. **Grinder at desk** — SVG illustration of a programmer coding
3. **Brain on fire** — animated sparks and lightning bolts around the figure
4. **Victory stand** — arms raised with energy rays
5. **Gold medal drop** — `#1` medal falls with animated confetti
6. **Bubble wave transition** — 4 expanding colour circles sweep into the app

### 📱 Fully Responsive
- Works on all screen sizes: mobile, tablet, desktop
- Sidebar stacks above content on small screens
- Navigation tabs scroll horizontally on mobile
- Problem cards, analytics, and modals all adapt cleanly

---

## 🖼 Screenshots

| Intro Animation | Setup Screen | DSA Tracker |
|---|---|---|
| Cinematic 7s story | Two-panel GitHub connect | Problem cards with tags |

| Analytics | Improvement Radar | Mobile View |
|---|---|---|
| Donut + Heatmap | Personalised insights | Fully responsive |

> _Screenshots can be added by capturing the live site at `https://Deepayan-Thakur.github.io/grind-exe`_

---

## 🛠 Tech Stack

| Layer | Technology | Why |
|---|---|---|
| **UI** | Pure HTML5 + CSS3 + Vanilla JS | Zero dependencies, fast load, no build step |
| **Fonts** | Google Fonts (Space Mono, Syne, JetBrains Mono) | Distinctive cyberpunk aesthetic |
| **Storage** | GitHub Gist API (REST) | Free, private, tied to your account |
| **Hosting** | GitHub Pages | Free, permanent, no backend |
| **Auth** | GitHub Personal Access Token (PAT) | Scoped to `gist` only — minimal permissions |
| **Animations** | CSS keyframes + SVG SMIL | Pure CSS/SVG, no animation library needed |
| **Caching** | Browser `localStorage` | Offline-first, instant load |

**Zero npm packages. Zero build tools. Zero backend servers. One HTML file.**

---

## 🔐 How Data Storage Works

```
Your Browser
     │
     ├── localStorage (cache)  ←── instant load on every visit
     │
     └── GitHub Gist API  ←── cloud sync after every change
              │
              └── Private Gist in YOUR GitHub account
                   └── grind-exe-data.json  (your progress)
```

### Sync Flow

1. **On page load** → Load from `localStorage` cache immediately (instant)
2. **In background** → Fetch latest data from your private Gist
3. **Merge strategy** → Remote solved-status wins (handles multi-device edits); local new items are preserved
4. **On any change** → Wait 1.8 seconds (debounce), then push to Gist
5. **On error** → Save to `localStorage` only, show warning toast, retry next time

### What is a GitHub Gist?

A Gist is like a mini-repository in your GitHub account for storing small files. GRIND.EXE creates one private Gist named `grind-exe-data.json` in your account. You can view it at `https://gist.github.com/YOUR_USERNAME`. Only you can see it.

---

## 🚀 Getting Started

### Prerequisites
- A GitHub account
- Git installed ([download](https://git-scm.com/download/win))
- VS Code installed ([download](https://code.visualstudio.com))

### Clone or Fork

**Option A — Fork (recommended)**
1. Go to `https://github.com/Deepayan-Thakur/grind-exe`
2. Click **Fork** (top right)
3. Your copy is now at `https://github.com/YOUR_USERNAME/grind-exe`
4. Enable GitHub Pages in your fork's Settings → Pages

**Option B — Clone fresh**
```bash
git clone https://github.com/Deepayan-Thakur/grind-exe.git
cd grind-exe
```

**Option C — Start from scratch (what we did)**
```bash
# Create folder, add index.html manually, then:
git init
git add .
git commit -m "Initial commit: GRIND.EXE tracker"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/grind-exe.git
git push -u origin main --force
```

---

## 🔑 GitHub Token Setup

This is the **one-time setup** you do after opening the live site for the first time.

### Step 1 — Go to GitHub Token Settings
Open: [https://github.com/settings/tokens/new](https://github.com/settings/tokens/new)

### Step 2 — Fill in the form

| Field | Value |
|---|---|
| **Note** | `grind-exe` |
| **Expiration** | `No expiration` |
| **Scopes** | ✅ `gist` only — nothing else |

### Step 3 — Generate and copy

Click **Generate token** → Copy the token starting with `ghp_`

> ⚠️ **Save this token somewhere safe.** GitHub shows it only once. If you lose it, generate a new one at the same URL.

### Step 4 — Connect in the app

Open your live site → paste the `ghp_...` token → click **Connect & Start Grinding →**

The app will:
- Verify your token with the GitHub API
- Search for an existing `grind-exe-data.json` Gist in your account
- Load your previous data if it exists
- Create a new private Gist if it's your first time

---

## 📦 Deploying to GitHub Pages

### Step 1 — Create repository on GitHub
- Go to [github.com/new](https://github.com/new)
- Name: `grind-exe`
- Visibility: **Public** (required for free GitHub Pages)
- Do **not** initialise with README

### Step 2 — Push code from VS Code terminal

```bash
cd path/to/your/grind-exe/folder

git init
git add .
git commit -m "Initial commit: GRIND.EXE tracker"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/grind-exe.git
git push -u origin main --force
```

### Step 3 — Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** tab
3. In left sidebar → **Pages**
4. Under **Branch** → select `main`
5. Folder → `/ (root)`
6. Click **Save**

### Step 4 — Wait 1–2 minutes

Your site goes live at:
```
https://YOUR_USERNAME.github.io/grind-exe
```

GitHub will show a green banner in the Pages settings when it's ready.

---

## 📖 Usage Guide

### Adding a DSA Problem

1. Go to the **⚙ DSA Problems** tab
2. Click **+ Add Problem**
3. Fill in:
   - **Title** — e.g. `Two Sum`
   - **LeetCode URL** — e.g. `https://leetcode.com/problems/two-sum/`
   - **Difficulty** — Easy / Medium / Hard
   - **Topic** — e.g. `Arrays`, `DP`, `Binary Tree`
4. Click **Add →**
5. Problem appears instantly, auto-saved to GitHub

### Marking a Problem as Solved

- Click the **checkbox** on the left of any problem card
- A particle burst animation fires from your click position
- The problem is marked with a green ✓ and strikethrough
- Your streak counter increments if it's your first solve today
- Data saves to GitHub automatically

### Opening a LeetCode Problem

- Click anywhere on the **problem card body** (not the checkbox)
- The LeetCode URL opens in a new tab
- Or click the **🔗 link button** on the right of the card

### Adding Aptitude Questions

1. Go to the **🧠 Aptitude** tab
2. Click **+ Add Question**
3. Select category: **Logical Reasoning**, **Quantitative Aptitude**, or **General Intelligence**
4. Set difficulty and title
5. Click **Add →**

### Viewing Analytics

- Go to the **📊 Analytics** tab
- View donut chart, aptitude breakdown, completion rate, 28-day heatmap
- The heatmap updates automatically as you solve problems each day

### Reading Improvement Insights

- Go to the **🎯 Improve** tab
- Insights are generated live from your current data
- Colour-coded: 🟢 strong area / 🟡 needs work / 🔴 urgent gap
- Updates every time you switch to this tab

### Settings Panel

- Click the **⚙** button in the top-right header
- View connected GitHub username, Gist ID, last sync time
- **↻ Sync Now** — force a manual push + pull
- **⬇ Export JSON Backup** — download your full data as a `.json` file
- **Disconnect Account** — removes token from browser (data stays safe in Gist)

---

## 🏆 Rank System

| Rank | Problems Solved | Colour |
|---|---|---|
| `NEWBIE` | 0 – 4 | Grey |
| `BEGINNER` | 5 – 14 | 🔴 Red |
| `INTERMEDIATE` | 15 – 29 | 🟠 Orange |
| `ADVANCED` | 30 – 59 | 🟢 Green |
| `EXPERT` | 60 – 99 | 🔵 Cyan |
| `MASTER` | 100 – 199 | 🟣 Purple |
| `LEGENDARY` | 200+ | 🥇 Gold |

Total count includes both DSA and Aptitude problems solved.

---

## 📁 Project Structure

```
grind-exe/
│
├── index.html          ← The entire application (HTML + CSS + JS)
│
└── README.md           ← This file
```

The entire app lives in a **single `index.html` file**. No `node_modules`, no `package.json`, no build process, no backend.

### Why single-file?

- ✅ Zero build step — edit and push, done
- ✅ Deploys instantly to any static host
- ✅ No dependency vulnerabilities
- ✅ Anyone can read the entire codebase in one scroll
- ✅ Works by just opening the file locally in a browser

### Internal Architecture

```
index.html
│
├── <style>
│   ├── CSS Variables (design tokens)
│   ├── Cinematic Intro Animation styles
│   ├── Setup Screen styles
│   ├── App layout (header, nav, sidebar, content)
│   ├── Component styles (cards, modal, analytics, improve)
│   └── Responsive breakpoints (720px, 900px, 600px)
│
├── <body>
│   ├── #introScreen     ← 7s cinematic story animation
│   ├── #setupScreen     ← GitHub token connect UI
│   ├── .header          ← Sticky top bar
│   ├── .nav-tabs        ← DSA / Aptitude / Analytics / Improve
│   ├── .sidebar         ← Stats, progress bars, filters
│   ├── .content
│   │   ├── #page-dsa
│   │   ├── #page-aptitude
│   │   ├── #page-analytics
│   │   └── #page-improve
│   ├── .settings-panel  ← Slide-in settings drawer
│   └── #modal           ← Add problem/question modal
│
└── <script>
    ├── Constants & State
    ├── Intro Animation (story phases + bubble wave)
    ├── Boot function (localStorage → Gist → show app)
    ├── GitHub Gist API (load, save, merge, debounce)
    ├── Render functions (DSA, Aptitude, both)
    ├── Toggle solved + particle animation
    ├── Stats updater + Rank system
    ├── Analytics (donut, heatmap, breakdown)
    ├── Improve insights generator
    ├── Settings panel + export
    └── Toast notification system
```

---

## 🔄 How to Update the Code

Whenever you make changes to `index.html` in VS Code:

```bash
# Stage all changes
git add .

# Commit with a description
git commit -m "feat: describe what you changed"

# Push to GitHub
git push
```

GitHub Pages auto-rebuilds within **1–2 minutes**. Refresh your live site and changes appear.

### Common update examples

```bash
# Added new quotes
git commit -m "chore: add motivational quotes"

# Fixed mobile layout
git commit -m "fix: mobile nav tab overflow"

# Added new feature
git commit -m "feat: add notes field to problem cards"

# Visual update
git commit -m "style: improve analytics card spacing"
```

---

## 💾 Data Backup & Recovery

### Automatic Backup

Your data automatically lives in a private Gist at:
```
https://gist.github.com/YOUR_USERNAME
```

Look for the file named `grind-exe-data.json`.

### Manual Backup

1. Open the app → click **⚙** (settings)
2. Click **⬇ Export JSON Backup**
3. A `.json` file downloads to your device

### Restore from Backup

If you ever lose access or switch accounts:
1. Open your backup `.json` file
2. Go to `https://gist.github.com` → create a new **private** Gist
3. Name the file `grind-exe-data.json`
4. Paste your backup JSON content → Save
5. Open GRIND.EXE with a new token → it will find and load your Gist

### What happens if I clear my browser?

Your data is safe. It lives in GitHub's servers, not your browser. Just reconnect with your token and everything loads back.

### What if I use multiple devices?

Open GRIND.EXE on any device → paste your GitHub token once → your full history loads. Changes sync across devices via the Gist.

---

## 🔒 Privacy & Security

| Concern | Answer |
|---|---|
| Where is my token stored? | Only in your browser's `localStorage` — never on any server |
| Can anyone see my data? | No — your Gist is **private**. Only you can access it |
| What does the token have access to? | Only the `gist` scope — cannot read code, repos, or anything else |
| Is data sent anywhere else? | No — only to `api.github.com` to read/write your own Gist |
| What if I share my screen? | Token is in a password input field — masked by default |

**To revoke access at any time:**
Go to `https://github.com/settings/tokens` → delete the `grind-exe` token. The app will stop syncing.

---

## 🗺 Roadmap

These features are planned for future versions:

- [ ] **Notes field** — add personal notes to each problem
- [ ] **Company tags** — tag problems by company (Google, Amazon, etc.)
- [ ] **Timed practice mode** — solve problems against a countdown
- [ ] **Import from LeetCode** — paste a LeetCode problem URL and auto-fill details
- [ ] **Weekly goal setting** — set a target of N problems per week
- [ ] **PDF progress report** — export a formatted PDF of your stats
- [ ] **Dark / Light theme toggle**
- [ ] **Custom categories** — create your own aptitude categories
- [ ] **Spaced repetition reminders** — remind you to revisit unsolved problems

---

## 👨‍💻 Author

**Deepayan Thakur**

CS Engineering Student | ML Engineer | Builder

- 🔗 GitHub: [@Deepayan-Thakur](https://github.com/Deepayan-Thakur)
- 🧠 Focus: AI/ML, DSA, Trade Analytics, Human-Computer Interaction
- 🛠 Projects: LIS Hybrid BCI System, Medicinal Plant Detection, HSN Trade Analytics Suite, VibezLang

---

## 📄 License

This project is open-source. Feel free to fork, modify, and use it for your own grinding journey.

If you find it useful, give it a ⭐ — it means a lot!

---

<div align="center">

**Built with 💻 and zero sleep.**

_GRIND.EXE — because dream companies don't hire people who give up._

</div>