# Client_Side_Development-


> A multi-page educational web platform to help students study smarter — featuring resources, interactive tools, subject guides, and a notes upload system.

---

## Project Structure

```
/
├── Home.html            # Home page — hero video, feature cards, cookie welcome
├── Resources.html       # Resources — accordion notes with search filter
├── subjects.html        # Subjects — tab switcher + topic reveal cards  ← my pages
├── tools.html           # Tools — GPA calc, Grade calc, Study timer      ← my pages
├── upload.html          # Upload — notes form with validation & LocalStorage
├── contact.html         # Contact — jQuery form validation, cookies
│
├── home.css             # Home page styles
├── home.js              # Home page scripts (cookie, navigation)
├── resources.css        # Resources page styles
├── resources.js         # Resources page scripts (toggle, search)
├── subjects.css         # Subjects page styles                           ← my files
├── subjects.js          # Subjects page scripts (tabs, topic reveal)     ← my files
├── tools.css            # Tools page styles                              ← my files
├── tools.js             # Tools page scripts (GPA, Grade, Timer)         ← my files
│
├── images/              # Local image assets (Java.png, Algebra.jpg …)
│
└── README.md            # This file
```

---

## 🚀 How to Run

No server or build tools required.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Client_Side_Development-.git
   cd Client_Side_Development-
   ```
2. Open `Home.html` in any modern web browser (Chrome, Firefox, Edge).
3. Use the navigation bar to move between pages.

> **Note:** The hero video (`WhatsApp Video 2026-04-16 at 12.48.38.mp4`) must be in the same folder as `Home.html` for it to play correctly.

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| HTML5 | — | Semantic page structure |
| CSS3 | — | Styling, transitions, animations |
| JavaScript | ES6 | Logic, DOM manipulation, LocalStorage |
| jQuery | 3.7.1 | Event handling, animations, AJAX-style DOM updates |
| Bootstrap | 5.3.0 | Layout utilities (upload & contact pages) |

All libraries loaded from CDN — no npm or build step needed.

---

## ✅ Pages & Features

| Page | Key Features |
|---|---|
| **Home** | Hero video background, cookie-based welcome message, feature cards |
| **Resources** | Accordion expand/collapse, live keyword search |
| **Subjects** | Tab switcher (Programming / Math / Science), click-to-reveal topic lists |
| **Tools** | GPA Calculator (4.0 scale), Grade Calculator (UK classification), Study Timer (countdown + stopwatch) |
| **Upload** | Full form validation, LocalStorage persistence, shake animation on error |
| **Contact** | jQuery form validation, floating labels, cookie pre-fill |

---

## ♿ Accessibility

- Semantic HTML elements used throughout (`<header>`, `<nav>`, `<section>`, `<footer>`)
- All inputs have `aria-label` attributes
- `aria-expanded` updated dynamically on toggle buttons (Subjects page)
- `aria-live="polite"` on the Study Timer display
- Keyboard-accessible cards (`tabindex="0"`)
- Colour contrast maintained across all pages

---

## ✔️ Validation

- HTML validated with [W3C Markup Validator](https://validator.w3.org/)
- CSS validated with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

---

## 👥 Team

| Member | Pages / Contribution |
|---|---|
| [Teammate A] | Home page (Home.html, home.css, home.js) |
| [Teammate B] | Resources page (Resources.html, resources.css, resources.js) |
| [Teammate C] | Upload page (upload.html), Contact page (contact.html) |
| Smarika Thapa| **Subjects page, Tools page, GitHub repo setup & README** |

---


