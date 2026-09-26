# Siddharth Ambare | Developer Portfolio

A responsive, high-performance personal portfolio website built with modern HTML5, Tailwind CSS, and vanilla JavaScript. Designed with a sleek dark-mode glassmorphism aesthetic to showcase frontend engineering projects, hackathon innovations, internship experience, and technical competencies.

---

## 🌟 Key Features

- **Modern Glassmorphic Dark UI:** Carefully designed backdrop blur, ambient neon glows, and gradient highlights.
- **Interactive Project Showcase & Filter:** Filter projects by category (*All*, *AI & Automation*, *Web & Systems*, *Hackathons*) with comprehensive project modal dialogs for deeper case studies.
- **Experience & Academic Timelines:** Visual chronological milestones representing professional internships at Nukaazo and degree education at ICEM, Pune.
- **Categorized Technical Competencies:** Structured skill cards for Frontend, Backend/Core, and Automation/DevOps tools.
- **Responsive Mobile Navigation:** Collapsible hamburger drawer menu built with pure JavaScript.
- **Interactive Contact Form & Feedback:** Simulated responsive message submission with accessible toast feedback.
- **Zero Build Configuration Needed:** Single-file design powered by standard CDNs (Tailwind CSS, Font Awesome, Google Fonts).

---

## 🛠️ Tech Stack

- **Markup & Styling:** [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML), [Tailwind CSS](https://tailwindcss.com/) (CDN)
- **Typography:** [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
- **Iconography:** [Font Awesome 6](https://fontawesome.com/)
- **Scripting:** Vanilla JavaScript (ES6+)

---

## 📁 Project Structure

```text
├── index.html        # Main single-file portfolio application
└── README.md         # Project documentation and guide
```

---

## 🚀 Quick Start / Local Setup

No bundlers (`npm`, `yarn`, `vite`) are required to run or edit this project.

1. **Clone or Download the repository:**
   ```bash
   git clone https://github.com/your-username/portfolio-website.git
   cd portfolio-website
   ```

2. **Open the site:**
   - Double-click `index.html` in your file explorer, or
   - Serve using VS Code's **Live Server** extension, or
   - Serve with Python:
     ```bash
     python -m http.server 3000
     ```
     Then navigate to `http://localhost:3000` in your web browser.

---

## ⚙️ Customization Guide

1. **Personal Information:** Search and replace `Siddharth Ambare`, contact email addresses, and social profile links (`github.com`, `linkedin.com`, `twitter.com`) in `index.html`.
2. **Projects:** Update the `projectDetails` object inside the `<script>` tag in `index.html` to add, edit, or remove project modal descriptions, tags, and icons.
3. **Resume Link:** Modify the `#resume-download-btn` click listener in the `<script>` block to link to an actual hosted PDF (e.g., `window.open('./resume.pdf', '_blank')`).
4. **Form Integration:** Replace the simulated client-side form submission with services such as [Formspree](https://formspree.io/), [EmailJS](https://www.emailjs.com/), or a custom backend webhook.

---

## 🌐 Free Deployment Options

- **GitHub Pages:**
  1. Push this repository to GitHub.
  2. Navigate to **Settings > Pages**.
  3. Set the source branch to `main` (or `master`) and directory to `/ (root)`.
  4. Save and access your live site.
- **Vercel / Netlify:**
  - Drag and drop your project folder directly into the Netlify or Vercel dashboard for instant SSL hosting.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).