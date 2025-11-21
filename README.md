# Dark Lotus – Corporate Website

The **Dark Lotus corporate website** is a professionally designed, fully responsive, and entirely static marketing site representing the company’s software development services and technical expertise. It is optimized for clarity, brand consistency, maintainability, and deployment across any static hosting provider.

---

## Overview

This repository contains the public-facing website for **Dark Lotus**, a software development company specializing in:

- Full‑stack engineering  
- Cross‑platform mobile development  
- API and backend architecture  
- Cloud integration  
- Long‑term technical support

The website is implemented using clean **HTML**, **CSS**, and minimal **JavaScript**, ensuring strong accessibility, reliability, and performance across modern browsers.

Key goals of the design include:

- Alignment with the Dark Lotus brand identity  
- Clear presentation of services and offerings  
- Straightforward user navigation  
- Full responsiveness across device sizes  
- Minimal external dependencies  

---

## Key Features

### **Responsive Interface**
Built with fluid grids and adaptive layouts supporting desktops, tablets, and mobile devices.

### **Service‑Oriented Content Architecture**
Organized sections for:
- Company overview  
- Service offerings  
- Portfolio examples  
- Contact and consultation workflow  

### **Performance & Accessibility**
- No frontend frameworks or build tools  
- Minimal JavaScript for predictable UX  
- Semantic HTML for assistive technology compatibility  
- Controlled contrast and typography for readability  

### **Branding Components**
Includes:
- Dark Lotus color system  
- Logo and watermark elements  
- Custom section dividers  
- SVG‑ready icon areas  

All components are easily replaceable for future brand evolution.

---

## Technology Stack

| Layer | Technology |
|-------|------------|
| **Markup** | HTML5 |
| **Styling** | CSS3 with custom properties and responsive rules |
| **Interactivity** | Vanilla JavaScript |
| **Fonts** | Google Fonts: Inter, Cormorant Garamond, JetBrains Mono |
| **Icons** | Inline SVG (Lucide‑compatible) |
| **Hosting** | Any static provider (GitHub Pages, Netlify, Vercel, Render, etc.) |

No dependencies or compilation required.

---

## Repository Structure

```
/
├── index.html        # Main site structure and content
├── styles.css        # Global styling and responsive system
├── script.js         # Navigation and UI interactions
├── logo.png          # Brand logo asset
├── favicon.png       # Browser icon
└── README.md         # Project documentation
```

---

## Local Development

### **Clone the Repository**
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### **Preview Locally**
Open `index.html` in your browser, or launch a quick local server:

```bash
npx live-server
```

No installation steps or additional tools required.

---

## Deployment

This static site can be deployed to any hosting provider.

### **GitHub Pages**
1. Push repository  
2. Enable Pages → Deploy from root directory  

### **Netlify**
Drag-and-drop folder or:

```bash
netlify deploy
```

### **Vercel**
```bash
vercel deploy
```

### **Render**
Choose “Static Site”, connect your repository, deploy.

---

## Brand & Content Configuration

### **Styling**
All primary theme variables are defined in `styles.css`:

```css
:root {
  --primary-color: #7F9790;
  --accent-color: #1F2D2A;
  --text-primary: #E8EBE9;
}
```

### **Content Editing**
Service descriptions, portfolio items, and text blocks are managed directly within `index.html`.

### **Icon System**
Supports inline SVGs (Lucide or custom). Replace SVG blocks inside `.service-icon` or `.contact-icon`.

---

## Future Enhancements

Planned improvements include:

- Expanded accessibility and ARIA support  
- Backend integration for contact form (EmailJS, Supabase, serverless functions)  
- Optional dark/light mode  
- Multi‑page structure expansion (Portfolio, Services, Careers)  
- Asset optimization and compression  
- Automated CI/CD deployment pipeline  

---

## Copyright

© 2025 Dark Lotus. All rights reserved.  
All branding, content, and assets are proprietary unless otherwise stated.

