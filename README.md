[LANDING_README.md](https://github.com/user-attachments/files/29374963/LANDING_README.md)
# Website-1
ShopForge Web 
<div align="center">

<h1>ShopForge — Landing Page</h1>
<p>A single-file marketing website for the ShopForge e-commerce starter project</p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/No_Dependencies-✓-22c55e?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-6c63ff?style=flat-square" />
</p>

</div>

---

## 📄 About

`shopforge-landing.html` is a fully self-contained marketing/project page for the ShopForge full-stack e-commerce starter. It's a single HTML file — no build step, no npm, no framework. Open it in a browser and it works.

Designed to be used as:
- A **GitHub project page** (host on GitHub Pages)
- A **Figma reference** (screenshot or import)
- A **live demo landing page** (deploy on Vercel/Netlify in one click)

---

## ✨ Sections

| Section | Description |
|---------|-------------|
| **Navbar** | Sticky, blurred, links to each section + GitHub CTA |
| **Hero** | Bold headline, subheading, browser mockup of the storefront |
| **Trust bar** | Tech stack icons (Next.js, PostgreSQL, Prisma, NextAuth, Zustand) |
| **Features** | 6-card grid covering every major feature |
| **Stack + Code** | Tech chips + styled `.env.local` setup snippet |
| **Route map** | All 9 pages with path, description, and role badge |
| **Database schema** | Visual Prisma model cards with PK/FK badges |
| **Deploy guide** | 5-step numbered walkthrough from clone to live |
| **CTA strip** | Closing call-to-action with glow effect |
| **Footer** | Logo, license, and nav links |

---

## 🚀 Usage

### View locally

Just open the file — no server needed:

```bash
open shopforge-landing.html       # macOS
start shopforge-landing.html      # Windows
xdg-open shopforge-landing.html   # Linux
```

### Host on GitHub Pages

1. Add `shopforge-landing.html` to your repo root and rename it `index.html`
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site is live at `https://yourusername.github.io/shopforge`

### Deploy on Vercel / Netlify

Drop the file into a new repo, connect it to Vercel or Netlify, and deploy. Both platforms serve static HTML files with zero config.

### Use as a Figma reference

1. Open `shopforge-landing.html` in Chrome
2. Take a full-page screenshot using the **GoFullPage** extension
3. Import the PNG into Figma as a reference frame

Or use the **HTML to Figma** plugin to pull live elements directly into your design file.

---

## 🎨 Design Tokens

All colors and fonts are defined as CSS variables at the top of the file — easy to reskin:

```css
:root {
  --ink:       #0d0d12;   /* page background */
  --ink-2:     #16161f;   /* card background */
  --ink-3:     #1e1e2a;   /* elevated surface */
  --rule:      #28283a;   /* borders / dividers */
  --violet:    #7b6cff;   /* primary accent */
  --lime:      #b8ff57;   /* secondary accent (code, badges) */
  --text:      #f2f2ff;   /* primary text */
  --muted:     #8888aa;   /* secondary text */
  --dim:       #44445a;   /* placeholder / disabled */
}
```

**Fonts** (loaded from Google Fonts):
- **Bricolage Grotesque** — display / headings
- **JetBrains Mono** — code blocks, routes, tags

---

## 🗂️ File Structure

```
shopforge-landing.html    ← entire site in one file
│
├── <style>               CSS variables, reset, layout, components
├── <nav>                 Sticky navigation bar
├── <section.hero>        Hero with browser mockup
├── <section.trust>       Tech stack trust bar
├── <section.features>    6-card features grid
├── <section.stack>       Stack overview + code block
├── <section.pages>       Route map cards
├── <section.schema>      DB schema tables
├── <section.deploy>      5-step deploy guide
├── <section.cta-strip>   Closing CTA
└── <footer>              Footer
```

---

## 🔗 Links to Update

Before publishing, replace these placeholders in the HTML:

| Placeholder | Replace with |
|-------------|-------------|
| `https://github.com` (×4) | Your actual GitHub repo URL |
| `yourusername` in deploy step | Your GitHub username |

Search for `https://github.com` in the file and update all four occurrences.

---

## 📜 License

MIT — use it freely for your own projects.
