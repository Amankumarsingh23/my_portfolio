# 🚀 Aman Kumar Singh — Personal Portfolio

> **Live:** [amankumarsingh.netlify.app](https://aman-kumar-singh.netlify.app) &nbsp;|&nbsp; **Built by:** [Aman Kumar Singh](https://github.com/Amankumarsingh23)

A dark terminal-aesthetic personal portfolio website built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no build tools, no dependencies. Just 5 self-contained HTML files.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-00ff9d?style=flat-square&labelColor=0a0a0f)
![Language](https://img.shields.io/badge/Built_with-HTML%20%2F%20CSS%20%2F%20JS-00d4ff?style=flat-square&labelColor=0a0a0f)
![License](https://img.shields.io/badge/License-MIT-ffd700?style=flat-square&labelColor=0a0a0f)

---

## 📁 File Structure

```
portfolio/
├── index.html          # Main portfolio — hero, about, skills, projects, achievements, contact
├── minigit.html        # Project detail — MiniGit (Custom VCS in C++)
├── huffcompress.html   # Project detail — HuffCompress (Lossless compression in C++)
├── leetcode.html       # Project detail — LeetCode Daily Solutions
├── apod.html           # Project detail — APOD Explorer (Android / Kotlin)
└── README.md
```

---

## ✨ Features

- **Loader animation** — glitch logo with progress bar and status messages
- **Custom cursor** — green dot with lagging ring, enlarges on hover
- **Cosmos starfield banner** — canvas-based animated stars, meteors, nebula glow, rotating quotes
- **Scroll reveal animations** — elements fade and slide in as you scroll
- **Terminal typewriter** — hero terminal lines appear sequentially
- **Stat counters** — numbers animate up when scrolled into view
- **Section dividers** — styled with terminal filenames between every section
- **Formspree contact form** — submissions land directly in Gmail
- **Email protection** — all mailto links assembled in JS to prevent CDN mangling
- **Scroll progress bar** — green line at the top of the page
- **Active nav highlight** — nav link glows for the current section
- **Fully responsive** — works on mobile, tablet, and desktop

---

## 🛠️ Tech Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | JetBrains Mono + Syne via Google Fonts |
| Contact Form | [Formspree](https://formspree.io) |
| Deployment | [Netlify Drop](https://app.netlify.com/drop) |

Zero npm. Zero build step. Zero frameworks.

---

## 📄 Pages

### `index.html` — Main Portfolio
The single-page portfolio covering:
- **Hero** — name, terminal typewriter, stats (CF rating, problems solved, SPI)
- **About** — photo, bio, academic facts, social links
- **Skills** — 6 skill categories with tags
- **Projects** — 4 projects each with a "View Details" link
- **Achievements** — JEE ranks, CF national rank, sports, academics
- **Resume** — Google Drive link + contact button
- **Contact** — Formspree form + direct links

### `minigit.html` — MiniGit Detail Page
Deep-dive into the custom VCS: architecture diagram, `.minigit/` directory structure, object model (blob/tree/commit), CLI usage examples, and feature breakdown.

### `huffcompress.html` — HuffCompress Detail Page
Deep-dive into the compression tool: full algorithm pipeline, worked example with codes and bit savings, CLI usage, and tech concepts.

### `leetcode.html` — LeetCode Daily Detail Page
Stats, topics covered (Trees, DP, Graphs, Heaps, Greedy, Backtracking...), and documented problem-solving approach.

### `apod.html` — APOD Explorer Detail Page
Android app showcase with real screenshots, phone mockup, feature list, tech stack, and NASA API details.

---

## 🚀 Deployment

### Netlify Drop (Recommended — free, under 5 minutes)

1. Download all files into one folder
2. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
3. Drag the **entire folder** onto the page
4. Get a free `*.netlify.app` URL instantly
5. Rename: **Site Settings → Change site name**

### Custom Domain (Optional)
Buy a domain on [Porkbun](https://porkbun.com) (~₹500/yr for `.dev` or `.tech`), then:
1. Netlify → **Domain Management → Add custom domain**
2. Add Netlify's nameservers to your registrar DNS
3. HTTPS is provisioned automatically

---

## ⚙️ Local Development

No build tools needed — just open in a browser:

```bash
git clone https://github.com/Amankumarsingh23/portfolio
cd portfolio
# Open index.html in your browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or use Live Server in VS Code for hot reload.

---

## 📬 Contact

| | |
|---|---|
| **Email** | logiclord67@gmail.com |
| **LinkedIn** | [aman-singh-iitkanpur](https://www.linkedin.com/in/aman-singh-iitkanpur/) |
| **GitHub** | [Amankumarsingh23](https://github.com/Amankumarsingh23) |
| **Codeforces** | [amansingh23](https://codeforces.com/profile/amansingh23) — Rating 1582 |
| **LeetCode** | [amansinghiitk23](https://leetcode.com/u/amansinghiitk23/) — 300+ problems |

---

## 📜 License

MIT — feel free to use the structure and design as inspiration, but please swap in your own content and don't copy directly.

---

<div align="center">
  <sub>Built with ☕ and too many late nights at IIT Kanpur</sub>
</div>
