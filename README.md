# My Portfolio – HubSpot Theme

Personal portfolio built as a **custom HubSpot CMS theme** using  
**HTML + HubL + CSS + Drag & Drop (DnD)**.

This project demonstrates how to structure a clean, scalable portfolio
inside HubSpot using reusable modules and a flexible page template.

---

## 🌍 Live Demo

You can try the portfolio live right now at:

🔗 https://147143932.hs-sites-eu1.com/abogm

Explore the full homepage and all sections (Hero, About, Skills, Projects, Contact) in action!

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
```
## 🧩 Sections Overview

### 1️⃣ Hero / Intro

The main entry point of the portfolio and the first visual impression.

**Purpose:**
Introduce the developer and clearly communicate identity and role.

**Content:**
- Profile image
- Main headline (name or branding)
- Subheadline (role / short description)
- Call-to-action button

<img width="100%" alt="Hero Section" src="https://github.com/user-attachments/assets/d197748b-5ddf-4357-be63-f5832cb1c971" />

---

### 2️⃣ About Me

A personal introduction section that explains background and goals.

**Purpose:**
Give visitors a clear understanding of who the developer is.

**Content:**
- Section title
- Editable descriptive text
- Clean and minimal layout

<img width="100%" alt="About Section" src="https://github.com/user-attachments/assets/f2464642-407b-4506-b6aa-4611b7234724" />

---

### 3️⃣ Skills

A structured section for showcasing technical skills.

**Purpose:**
Highlight technologies, tools, and areas of expertise.

**Content:**
- Repeater-based skills list
- Skill name
- Skill description
- Fully editable from the editor

<img width="100%" alt="Skills Section" src="https://github.com/user-attachments/assets/ccd6cf62-69b3-47b0-a608-6140d55f923a" />

---

### 4️⃣ Projects

A visual grid displaying selected projects.

**Purpose:**
Showcase real work and practical experience.

**Content:**
- Project cards
- Project image
- Project title
- Short description
- Optional GitHub / Live Demo link

<img width="100%" alt="Projects Section 1" src="https://github.com/user-attachments/assets/d42eb0a0-a936-4028-9549-f83feec6577a" />

<img width="100%" alt="Projects Section 2" src="https://github.com/user-attachments/assets/e57fd1df-4146-4439-b080-3b23ac219e40" />

---

### 5️⃣ Contact CTA

A call-to-action section encouraging user interaction.

**Purpose:**
Guide visitors to initiate contact.

**Content:**
- Short message
- Call-to-action button
- Simple and focused layout

<img width="100%" alt="Contact Section" src="https://github.com/user-attachments/assets/d04cd908-0452-4df8-9cd7-603d54e26b62" />

---

## 🛠 Technologies Used

- HubSpot CMS  
- HubL  
- HTML5  
- CSS3  
- Drag & Drop (DnD) Architecture  

---

## 🚀 How to Use

1. Upload the theme folder to **HubSpot Design Manager**
2. Activate the theme
3. Create a new page using `home.html`
4. Add, remove, or reorder sections using **Drag & Drop**
5. Edit content directly from the page editor
6. Publish 🚀

---

## 📌 Notes

- Designed for easy customization  
- No coding required for content updates  
- Optimized for readability and clean UI  

---

## 📄 License

This project is open-source and available for customization.
