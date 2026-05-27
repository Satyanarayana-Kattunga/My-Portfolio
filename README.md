Here's a detailed README description for your portfolio project:

---

## 🌐 Personal Portfolio Website — Satyanarayana Kattunga

A fully responsive, single-page **Data Analyst Portfolio Website** built with pure **HTML, CSS, and Vanilla JavaScript** — no frameworks, no build tools, no dependencies to install. Just open and run.

---

## 🎯 Purpose

This project serves as a **professional online presence** for Satyanarayana Kattunga, a Data Analyst. It is designed to:

- Showcase **skills, projects, and work experience** to potential employers or collaborators
- Provide a **direct contact channel** via email and social links
- Display a **live GitHub README** pulled dynamically from the repository
- Act as a **digital resume** that is more interactive and visually engaging than a traditional PDF

---

## 🚀 How to Run

Since this is a plain HTML project, running it is effortless:

**Option 1 — Open Directly in Browser**
```
Just double-click index.html → opens in any browser instantly
```

**Option 2 — VS Code Live Server**
```
1. Open the project folder in VS Code
2. Install the "Live Server" extension
3. Right-click index.html → "Open with Live Server"
4. Visit http://127.0.0.1:5500 in your browser
```

**Option 3 — Deploy Online (Recommended)**
```
GitHub Pages:
1. Push the file to a GitHub repository
2. Go to Settings → Pages
3. Set source to main branch
4. Your site goes live at: https://<username>.github.io/<repo-name>
```

> ✅ No Node.js, no npm install, no build step required.

---

## ⚙️ How It Works

### 🧭 Navigation
- A **fixed top navbar** with smooth scroll links to each section
- On scroll, the active section is **auto-highlighted** in the nav using `window.scrollY`
- On mobile, a **hamburger menu** toggles a full-screen overlay for navigation

### 🎨 Visual Design
- Deep dark background (`#0a0d12`) with three animated **glow blobs** (cyan, purple, green) that float using CSS `@keyframes`
- A subtle **SVG noise texture** is overlaid across the entire page for a premium feel
- All section entries use the **Intersection Observer API** to trigger `fade-in` animations as you scroll down

### 📄 Sections Breakdown

| Section | What it does |
|---|---|
| **Hero** | Name, title, short bio, CTA buttons, social links |
| **About** | Background summary and key facts |
| **Skills** | Tools and technologies with visual tags |
| **Projects** | Cards showcasing data analytics projects |
| **Experience** | Work history in a timeline layout |
| **Certifications** | Credentials and courses completed |
| **Contact** | Form that generates a pre-filled `mailto:` email |
| **GitHub README** | Live-fetched and rendered from GitHub API |

### 📬 Contact Form
- Collects Name, Email, Subject, and Message
- On submit, builds a `mailto:` URL and opens the user's email client with everything pre-filled
- Basic validation ensures Name, Email, and Message are not empty

### 🐙 Live GitHub README Viewer
This is the standout feature — it **dynamically fetches your actual README.md** from GitHub at page load:

```
1. Fetches raw README.md from GitHub (tries main → master branch)
2. Sends the markdown to the GitHub Markdown Render API
3. Injects the rendered HTML into the page
4. Fixes relative image/asset URLs to point to GitHub raw content
5. Falls back to a basic built-in markdown parser if the API fails
```

---

## 📁 Project Structure

```
portfolio/
│
└── index.html       # Entire project — HTML + CSS + JS in one file
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (Custom Properties, Flexbox, Grid, Animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Icons | Font Awesome 6.5 |
| Fonts | Google Fonts — Syne & DM Sans |
| APIs | GitHub Raw Content API, GitHub Markdown Render API |

---

## 📌 Key Highlights

- ⚡ **Zero dependencies** — no npm, no bundler, no framework
- 📱 **Fully responsive** — works on mobile, tablet, and desktop
- 🌙 **Dark theme** with animated background effects
- 🔄 **Live GitHub README** rendered in real-time from the repo
- 🎞️ **Smooth animations** on scroll with Intersection Observer
- 📧 **One-click contact** via mailto integration

---

Feel free to copy this directly into your `README.md`. Want me to also generate a preview badge section (built with, license, live demo button) to go at the top?
