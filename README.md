# 🗂️ HTML Portfolio Templates

**6 professional, handcrafted HTML/CSS portfolio templates** — zero dependencies, zero frameworks, zero JavaScript libraries. Just clean HTML, CSS, and subtle vanilla JS animations.

Each template is designed for a different professional persona, with a distinct visual identity, color palette, and typography system.

---

## 📦 Templates

| # | Template | Persona | Style | Colors |
|---|----------|---------|-------|--------|
| 1 | `template-1-executive` | CEO / Executive | Refined Luxury | Navy + Gold |
| 2 | `template-2-architect` | Architect / Designer | Editorial Grid | Warm Paper + Rust |
| 3 | `template-3-consultant` | Management Consultant | Clean Corporate | White + Forest Green |
| 4 | `template-4-finance` | Financial Strategist | Data / Terminal | Midnight + Electric Blue |
| 5 | `template-5-tech-lead` | VP Engineering / Tech Lead | Warm Modern | Cream + Amber |
| 6 | `template-6-creative-director` | Creative Director | Brutalist Editorial | White + Scarlet |

---

## 🚀 Quick Start

1. Clone the repo:
   ```bash
   git clone [https://github.com/EryXenX/html-portfolio-templates.git]
   ```

2. Open any template:
   ```bash
   cd html-portfolio-templates/template-1-executive
   open index.html
   ```

3. Edit the placeholder content — names, descriptions, stats, and links — to make it your own.

---

## ✏️ Customization Guide

### Change Name & Title
Find and replace the placeholder name (e.g., `Jonathan Pierce`) and title throughout the HTML.

### Change Colors
Each template uses CSS custom properties at the top of the `<style>` block:
```css
:root {
  --navy: #08101f;
  --gold: #b8943f;
  /* etc. */
}
```
Edit these variables to retheme the entire template instantly.

### Change Fonts
Each template imports Google Fonts. Replace the `<link>` tag in `<head>` and update the `font-family` references in CSS.

### Add Your Photo
Look for the placeholder `div` with class `hero-img-placeholder` or similar — replace it with an `<img>` tag pointing to your photo.

### Deploy
These are plain HTML files. You can host them on:
- **GitHub Pages** — free, push and go
- **Netlify** — drag and drop the folder
- **Vercel** — `vercel` CLI, one command
- **Render** — static site, free tier

---

## 📁 Folder Structure

```
html-portfolio-templates/
├── template-1-executive/
│   └── index.html
├── template-2-architect/
│   └── index.html
├── template-3-consultant/
│   └── index.html
├── template-4-finance/
│   └── index.html
├── template-5-tech-lead/
│   └── index.html
├── template-6-creative-director/
│   └── index.html
├── LICENSE
└── README.md
```

Each template is fully self-contained in a single `index.html` file — fonts loaded from Google Fonts CDN, everything else inline.

---

## 🌐 Browser Support

Tested and working in:
- Chrome 100+
- Firefox 100+
- Safari 15+
- Edge 100+

All templates are responsive (mobile, tablet, desktop).

---

## 📄 License

MIT License — free to use for personal and commercial projects. See [LICENSE](LICENSE).

Attribution appreciated but not required. If you fork this, a ⭐ star is always welcome.

---

## 🤝 Contributing

Pull requests welcome. If you build a new template variant or improve an existing one:

1. Fork the repo
2. Create a branch: `git checkout -b template-7-yourname`
3. Add your template in a new folder following the naming convention
4. Submit a PR with a brief description of the design direction

---

## 📸 Preview

> Screenshots coming soon. Clone and open locally to preview all templates.

---

Made with care. No AI slop.
