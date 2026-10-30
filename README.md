# Sardar Hussain - Modern Single-Page Portfolio Website

A clean, modern, fully responsive single-page portfolio website designed and developed for **Sardar Hussain**, Multiskilled Technology Professional, Data Analyst, and Information Secretary based in Matli, Sindh, Pakistan.

---

## 🌟 Key Highlights & Features

- **Responsive Architecture**: Built mobile-first using Tailwind CSS (via CDN) with semantic HTML5 elements.
- **Dynamic Typing Text Effect**: Rotating titles in the Hero section (*Technology Professional*, *Data Analyst*, *Information Secretary*, *IT Instructor*).
- **Interactive Competency Filters**: Real-time filtering across Web & E-Commerce, Data Analytics & AI, Taxation & Accounting, and Digital Design & Admin with animated progress bars.
- **Experience Timeline Accordion**: Career timeline connecting IBA Sindh, Tax Inn Karachi, M-Logicx Education, Govt. GBLSS, and Bright Future College with expandable achievement logs and an "Expand All" master toggle.
- **Credential Verification Modal**: Detailed interactive modal system showcasing Level 7 Power BI (CIQ UK, 96%), Google AI Professional, Master ChatGPT Level 5 (90%), Mobile Development (MUET), and STEVTA certifications with one-click credential ID copying.
- **Printable Resume Viewer**: Built-in resume modal with clean print stylesheets (`window.print()`) for direct PDF downloading.
- **Interactive Contact Section**:
  - One-click phone calling and email launching.
  - Global click-to-copy utility with interactive toast notifications.
  - Form validation with inline feedback and simulated submission.
- **Dark / Light Theme Switcher**: CSS variable driven theming stored in `localStorage` with system preference auto-detection.
- **Circular Scroll-to-Top**: Smooth scrolling with an SVG progress ring tracking user depth on the page.

---

## 📁 File Structure

```
sardar-hussain-portfolio/
│
├── index.html          # Semantic HTML5 single-page structure with Tailwind integration
├── css/
│   └── style.css       # Custom glassmorphic styling, animations, CSS variables & print styles
├── js/
│   └── app.js          # Modular vanilla JavaScript (theme, typing, filters, modals, validation)
└── README.md           # Documentation and setup guide
```

---

## 🚀 How to Run Locally

Because this project is built using vanilla HTML5, CSS3, and JavaScript, no build steps or Node.js dependencies are required:

1. **Direct Browser Launch**:
   Double click `index.html` or open it in any modern browser (Chrome, Edge, Firefox, Safari).

2. **Using a Local Server (Recommended for development)**:
   ```powershell
   # Using Python 3:
   python -m http.server 8000
   
   # Or using npx serve:
   npx serve .
   ```
   Then open `http://localhost:8000` in your web browser.

---

## 👤 Profile & Attribution

- **Name**: Sardar Hussain
- **Location**: Matli, Sindh, Pakistan
- **Contact**: +92 305 3886931 / +92 348 3981664 | sardarbrohi000@gmail.com
- **Languages**: English, Urdu, Sindhi, Balochi
- **Reference**: Sir Munawar Ali Bhurgri (Web & Software Developer & Google Analytics Expert)
