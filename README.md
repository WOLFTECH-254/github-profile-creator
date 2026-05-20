<div align="center">

```
██████╗ ███████╗ █████╗ ██████╗ ███╗   ███╗███████╗       ██████╗ ███████╗███╗   ██╗
██╔══██╗██╔════╝██╔══██╗██╔══██╗████╗ ████║██╔════╝      ██╔════╝ ██╔════╝████╗  ██║
██████╔╝█████╗  ███████║██║  ██║██╔████╔██║█████╗        ██║  ███╗█████╗  ██╔██╗ ██║
██╔══██╗██╔══╝  ██╔══██║██║  ██║██║╚██╔╝██║██╔══╝        ██║   ██║██╔══╝  ██║╚██╗██║
██║  ██║███████╗██║  ██║██████╔╝██║ ╚═╝ ██║███████╗      ╚██████╔╝███████╗██║ ╚████║
╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═════╝ ╚═╝     ╚═╝╚══════╝       ╚═════╝ ╚══════╝╚═╝  ╚═══╝
```

### ⚡ WOLF TECH EDITION ⚡
**The most fire GitHub Profile README generator on the internet.**

[![Live Demo](https://img.shields.io/badge/LIVE%20DEMO-00ff00?style=for-the-badge&logo=github&logoColor=black)](https://readme-gen.replit.app)
[![Built With](https://img.shields.io/badge/Built%20With-Vanilla%20JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![License](https://img.shields.io/badge/License-MIT-bf5fff?style=for-the-badge)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-ZERO-00ff00?style=for-the-badge&logo=checkmarx&logoColor=black)](package.json)

</div>

---

## 🐺 What Is This?

**README.GEN** is a blazing-fast, single-file GitHub Profile README generator built with zero frameworks, zero build steps, and zero fluff. Fill in 5 steps → get a production-ready `README.md` you can push directly to GitHub — all from the browser.

No sign-up. No tracking. No BS.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🧙 **5-Step Wizard** | Guided flow: Basic Info → Socials → Skills → Theme → Features |
| 🎨 **10 Color Themes** | Cyberpunk Neon, Radical Purple, Tokyo Night, Nord Ice, Golden Matrix & more |
| 🖼️ **2 Layout Templates** | **Wolf Tech** (cyberpunk neon) · **PRG Classic** (professional clean) |
| 📊 **Live Visual Preview** | See your real GitHub stats, streak, trophies & activity graph load in real time |
| 🔥 **Raw MD Tab** | Instant toggle to see the exact markdown that gets generated |
| 🚀 **GitHub Auto-Push** | 3-step token flow — push your README directly to your GitHub profile repo |
| 📥 **Download / Copy** | One-click copy or `.md` file download |
| 🏆 **Trophies & Snake** | GitHub trophies row + contribution snake animation (dark/light mode) |
| 🛠️ **40+ Skills** | Pre-built skill badges + custom skill input |
| 🌐 **Social Badges** | LinkedIn, Twitter/X, YouTube, Telegram, WhatsApp, Portfolio |
| 💾 **Session Persistence** | Auto-saves your form state to `localStorage` |
| 📱 **Responsive** | Works on mobile, tablet, and desktop |

---

## 🖥️ Preview

<div align="center">

### Wolf Tech Layout
> Dark cyberpunk neon aesthetic with neon glow borders, Orbitron font headers, and matrix-green stats cards.

### PRG Classic Layout
> Clean professional style with `skillicons.dev` colorful tech icons, platform-colored social badges, and a full stats row.

</div>

---

## 🚀 Getting Started

### Run Locally

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/readme-gen.git
cd readme-gen

# Serve with Python (no install needed)
python3 -m http.server 5000

# Open in browser
open http://localhost:5000
```

That's it. Literally one command. No `npm install`. No webpack. No vite. Just a browser and Python.

---

## 🧭 How It Works

```
Step 1 — BASIC INFO
  └─ Name · Username · Role · Location · Bio

Step 2 — SOCIALS
  └─ LinkedIn · Twitter · YouTube · Telegram · WhatsApp · Portfolio

Step 3 — SKILLS
  └─ 40+ pre-built techs + custom skill input

Step 4 — THEME & LAYOUT
  └─ 10 color themes × 2 layout templates

Step 5 — FEATURES
  └─ Toggle: Stats · Streak · Top Langs · Activity Graph · Trophies · Snake · Repos
```

Hit **"Generate README"** → Live preview updates instantly.
Hit **"Push to GitHub"** → Paste your token, confirm, done. ✅

---

## 🎨 Color Themes

| # | Theme | Accent | Stats Theme |
|---|---|---|---|
| 1 | 🟢 Cyberpunk Neon | `#00ff00` | `chartreuse-dark` |
| 2 | 🟣 Radical Purple | `#bf5fff` | `radical` |
| 3 | ⬜ Minimal Dark | `#e0e0e0` | `dark` |
| 4 | 🔵 Ocean Blue | `#00aaff` | `algolia` |
| 5 | 🟠 Sunset Fire | `#ff6b35` | `solarized-dark` |
| 6 | 🔴 Hacker Red | `#ff3333` | `highcontrast` |
| 7 | 🩷 Rose Bloom | `#ff79c6` | `dracula` |
| 8 | 🩵 Tokyo Night | `#7dcfff` | `tokyonight` |
| 9 | 🧊 Nord Ice | `#88c0d0` | `nord` |
| 10 | 🟡 Golden Matrix | `#ffd700` | `gruvbox` |

---

## 🔧 Tech Stack

```
├── index.html          ← The entire app (single file, ~2500 lines)
│
├── Fonts               ← Orbitron · JetBrains Mono (Google Fonts)
├── Icons               ← Font Awesome 6 CDN
│
└── External APIs used in generated READMEs:
    ├── github-readme-stats.vercel.app    (Stats · Top Langs · Pinned Repos)
    ├── streak-stats.demolab.com          (Streak card)
    ├── github-profile-trophy.vercel.app  (Trophies)
    ├── github-readme-activity-graph      (Activity graph)
    ├── capsule-render.vercel.app         (Waving banner header)
    ├── readme-typing-svg.demolab.com     (Typing animation header)
    ├── skillicons.dev                    (PRG Classic tech icons)
    ├── komarev.com/ghpvc                 (Profile view counter)
    └── img.shields.io                    (Skill & social badges)
```

> **Zero external JS libraries.** No React, no Vue, no jQuery. Pure DOM + CSS + Fetch API.

---

## 🔐 GitHub Push — How It Works

The auto-push feature uses the **GitHub Contents API**:

1. You paste a **Personal Access Token** (PAT) with `repo` scope — it never leaves your browser and is never stored on disk.
2. The app calls `GET /repos/{owner}/{repo}/contents/README.md` to fetch the current file SHA.
3. It then calls `PUT` with the new base64-encoded content + SHA to commit the update.
4. Token is cleared from memory when the modal closes.

```
Your Browser → GitHub API (HTTPS) → Your Profile Repo
```

No server. No middleman. Direct.

---

## 📁 Project Structure

```
readme-gen/
├── index.html       ← Full app: HTML + CSS + JS in one file
├── profile.html     ← Legacy copy (kept for reference)
└── README.md        ← You are here
```

---

## 🗺️ Roadmap

- [x] 5-step wizard with live preview
- [x] Wolf Tech & PRG Classic layout templates
- [x] 10 color themes
- [x] GitHub direct push via PAT
- [x] Real live stats preview in Visual tab
- [x] Trophies, streak, activity graph, snake animation
- [x] skillicons.dev integration (PRG Classic)
- [ ] More layout templates
- [ ] Export as ZIP with GitHub Actions workflows included
- [ ] QR code for profile link
- [ ] Dark/Light preview toggle in visual pane

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

```bash
# Fork → Clone → Edit index.html → PR
# It's one file. There's nothing to configure.
```

---

## 📜 License

MIT — do whatever you want with it, just don't remove the wolf 🐺

---

<div align="center">

**Built with 💚 by [WOLF TECH](https://github.com/WOLFTECH-254)**

*No frameworks were harmed in the making of this tool.*

[![Star This Repo](https://img.shields.io/badge/⭐%20Star%20This%20Repo-00ff00?style=for-the-badge&logo=github&logoColor=black)](https://github.com/WOLFTECH-254/readme-gen)

</div>
