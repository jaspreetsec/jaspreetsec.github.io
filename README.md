# Jaspreet Singh — Cybersecurity Portfolio

Single-page portfolio website for cybersecurity professional Jaspreet Singh. Built with vanilla HTML, CSS, and JavaScript. Deployed via GitHub Pages.

🌐 **Live Site**: [https://jjaspreetsingh.com](https://jjaspreetsingh.com)

## About This Site

This is a **static single-page portfolio** with anchor-based navigation. It does NOT have:
- Multiple HTML pages (everything is in `index.html`)
- Theme toggle (dark theme only)
- Hamburger menu (simple horizontal nav)

All content is in one place: skills, projects, bio, and contact section.

## ✨ What's Actually Here

- 🎯 **Single-page layout** with smooth anchor scrolling
- 🎨 **Dark theme only** — orange/amber gradient accents on near-black background
- ⬆️ **Scroll-to-top button** that appears after scrolling
- ✨ **Scroll-triggered animations** using IntersectionObserver
- 🖥️ **Terminal aesthetic** in the About section (command-line prompts)
- ♿ **Basic accessibility** — semantic HTML, ARIA labels where needed
- ⚡ **No dependencies** — pure vanilla code, fast load

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — CSS Variables, Flexbox, Grid, keyframe animations
- **JavaScript (ES6+)** — Vanilla JS, IntersectionObserver API
- **GitHub Pages** — Automatic deployments on push to main

## 📁 File Structure

```
.
├── index.html          # Entire site (single page)
├── styles.css          # All styles
├── script.js           # JavaScript functionality
├── favicon.jpg         # Site favicon
├── CNAME              # Custom domain config
├── README.md          # This file
└── SECURITY.md        # Security policy
```

Note: There are NO separate `about.html`, `projects.html`, or `contact.html` files. Those were redirect stubs and have been deleted.

## 🚀 Deployment

GitHub Pages automatic deployment:

1. Push to `main` branch
2. GitHub Actions builds and deploys
3. Site live at `https://jjaspreetsingh.com` within 1-2 minutes

The workflow (`.github/workflows/static.yml`) uploads only necessary files: `index.html`, `styles.css`, `script.js`, `favicon.jpg`, `CNAME`.

## 📄 SEO & Metadata

The site includes:
- Meta description for search engines
- Open Graph tags for social sharing (Twitter/X, LinkedIn)
- Canonical URL tag
- Proper page title

## 🎯 Content Sections

1. **Hero** — Name, title, brief intro, social links
2. **Skills** — Technology badges (Kali, Burp, Metasploit, Python, etc.)
3. **Projects** — Three honest entries:
   - TryHackMe Progress (link to THM profile)
   - Self-Hosted Lab Infrastructure (Docker, Tailscale, etc.)
   - Home Lab C2 Setup (Sliver, WireGuard, Uptime Kuma)
4. **About** — Personal story with terminal prompt UI
5. **Contact** — GitHub, LinkedIn, X, TryHackMe links

## 🔒 Security

See [SECURITY.md](SECURITY.md) for vulnerability reporting. This site is static and has no backend, so attack surface is minimal.

## 📝 License

This portfolio is personal and not open source. All code is provided as-is for educational purposes. Do not copy without permission.

## 🙏 Credits

- Design: Custom dark theme with orange/amber palette
- Icons: SVG paths in HTML (GitHub, LinkedIn, X, TryHackMe)
- Fonts: System fonts with Inter-like stack
- Hosting: GitHub Pages

---

Built with care by Jaspreet Singh. No frameworks, no nonsense.
