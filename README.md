<center>

# 🏫 **Rural School Website**

A responsive and accessible website built for a rural school using **HTML, CSS, and JavaScript**. The site features clean navigation, mobile-first design, and a one-click language toggle that switches the entire UI to **Hindi** using a JSON file — making content accessible to the local community.

</center>

---

## ✨ Project Overview

This project is a real website built for a school to provide information to parents, students, teachers, and visitors. It includes pages for About, Admission, Academics, Teachers, Events/Gallery, Contact, and a special “Hindi” translation toggle that replaces text content across the site from a single `translations.json` file.

Key goals:
- Accessibility for non-English speakers (Hindi support)  
- Simple, easy-to-navigate layout for low-bandwidth contexts  
- Responsive layout that works on phones and desktops  
- Zero backend required — static site deployable to GitHub Pages or any static host

---

## 📦 Tech Stack

- **HTML5** — structure  
- **CSS3** (mobile-first, responsive) — layout & styling  
- **Vanilla JavaScript** — interactivity & i18n  
- **JSON** — translations file (`translations.json`) that drives the one-click Hindi toggle

---

## 🧩 Features

- ✅ Responsive, mobile-first design  
- ✅ Clean multi-page navigation (About, Admissions, Academics, Teachers, Events/Gallery, Contact)  
- ✅ One-click language toggle (English ⇄ , Hindi) powered by a single `i18n.json` file  
- ✅ Fast static site — no server required  
- ✅ Lightweight and optimized for low-bandwidth environments  
- ✅ Easy to update content and translations

---
🎯 Usage & Editing

To add or update text content: edit the HTML file(s) index.html, about.html, etc. — target content should use data-i18n keys if it should be translatable.

To add Hindi translations: open assets/translations.json and add keys under "hi".

To change theme / CSS: update images/css/styles.css.

---
🔮 Future Improvements (Roadmap)

Add bilingual content editing UI for non-technical admins

Add form for offline applications (store in local CSV) or email notifications

Multi-language support beyond Hindi (e.g., regional languages)

Lightweight CMS (static admin page / Netlify CMS) to let staff update content without editing files

Add printable PDF brochures (admission forms)

Improve SEO and add structured data for better discoverability

---
👤 Author

Shaurya Bhaskar

