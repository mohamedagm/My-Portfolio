# My Portfolio – HubSpot Theme

Personal portfolio built as a **custom HubSpot CMS theme** using  
**HTML + HubL + CSS + Drag & Drop (DnD)**.

This project demonstrates how to structure a clean, scalable portfolio
inside HubSpot using reusable modules and a flexible page template.

---

## 🔥 Features

- Custom HubSpot Theme
- Drag & Drop page builder support
- Modular architecture (each section = module)
- Clean, modern UI
- Fully responsive layout
- Easy content editing from HubSpot Editor

---

## 📁 Project Structure

```bash
project-theme/
│
├── css/
│   └── global.css              # Global styles (header, footer, layout)
│
├── modules/
│   ├── hero-intro.module/      # Intro / Banner section
│   ├── about-intro.module/     # About Me section
│   ├── skills-section.module/  # Skills (repeater-based)
│   ├── projects-grid.module/   # Projects grid
│   └── contact-cta.module/     # Contact Call-To-Action
│
├── partials/
│   ├── header.html             # Site header
│   └── footer.html             # Site footer
│
├── templates/
│   ├── home.html               # Main portfolio page (DnD enabled)
│   └── page.html               # Base page template
│
├── fields.json                 # Theme fields (global settings)
└── theme.json                  # HubSpot theme configuration
