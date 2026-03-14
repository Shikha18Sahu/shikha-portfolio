# Shikha Sahu — Developer Portfolio

A modern, dark-themed developer portfolio inspired by the Harshit Lohani portfolio design.

## 🚀 Quick Start (Standalone HTML — No Build Required)

Simply open `index.html` in any browser:
```bash
open index.html
# OR double-click the file
```

That's it! The standalone `index.html` uses CDN links for all dependencies.

---

## ⚛️ React + Tailwind Version (Full Project)

### Prerequisites
- Node.js 16+
- npm or yarn

### Install & Run

```bash
cd shikha-portfolio
npm install
npm start
```

Then open: http://localhost:3000

### Build for Production

```bash
npm run build
```

Output goes to the `build/` folder — deploy to Netlify, Vercel, or GitHub Pages.

---

## 📁 Folder Structure

```
shikha-portfolio/
├── index.html              ← Standalone (no build needed)
├── public/
│   └── index.html
├── src/
│   ├── App.jsx
│   ├── index.js
│   ├── index.css
│   └── components/
│       ├── Navbar.jsx
│       ├── Hero.jsx
│       ├── Projects.jsx
│       ├── Skills.jsx
│       ├── Experience.jsx
│       ├── Contact.jsx
│       └── Footer.jsx
├── tailwind.config.js
└── package.json
```

## 🎨 Design Notes

- **Color palette**: Cyan `#00d4ff` · Purple `#7c3aed` · Dark `#080d14`
- **Fonts**: Syne (headings) · DM Sans (body) · Space Mono (code/labels)
- **Sections**: Hero → Projects → Skills → Experience + Certifications → Contact
- Matches the layout structure of harshit-lohani-portfolio.netlify.app
- Fully responsive with mobile breakpoints

## ✏️ Customization

Update your info in:
- `index.html` (standalone) — search for any text and replace
- React version: edit the data arrays in each component file

## 🌐 Deploy to Netlify

1. Drag the `index.html` file to [netlify.com/drop](https://app.netlify.com/drop)
2. Done! Or connect your GitHub repo for automatic deployments.
