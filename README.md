# 🤖 AI Research Lab Website

> “Great things are not done by impulse, but by a series of small things brought together.” — Vincent van Gogh

A modern, responsive, multi-page academic website built for an AI research lab.  
This project presents research identity, team structure, achievements, publications, and lab activity through a clean interface with interactive visual elements.  

---

## ✨ Overview

The AI Research Lab website is designed to communicate research vision, people, outputs, and ongoing work in a polished and accessible way.  
It combines a storytelling-style homepage with shared navigation, responsive layouts, and a professional design system across the site.

This website includes:

- 🏠 A research-focused homepage
- 👥 Team and member-oriented pages
- 🎓 Student member information
- 📚 Achievements and publication previews
- 📌 Current project highlights
- ℹ️ About page
- 🌗 Light and dark theme toggle
- 📱 Mobile-friendly navigation
- 🎞️ Hero carousel and animated counters
- 🚀 Expandable structure for future pages like `join_us.html` and `contact_us.html`

---

## 💡 Inspiration

> “Research is formalized curiosity. It is poking and prying with a purpose.” — Zora Neale Hurston

This website was developed to represent a research lab not only as a static institution, but as a living space for ideas, experimentation, writing, and impact.

The design language aims to feel:

- **Technical**
- **Optimistic**
- **Collaborative**
- **Research-forward**
- **Professional**

---

## 🧱 Project Structure

```bash
project-folder/
│
├── index.html
├── members.html
├── student-members.html
├── current-projects.html
├── achievements.html
├── about.html
├── join_us.html
├── contact_us.html
│
└── assets/
    ├── style.css
    ├── script.js
    └── images / media files
```

The homepage loads shared styling and JavaScript through external asset files, which keeps the website consistent across pages and easier to maintain. [file:3][file:2][file:1]

---

## 🎨 Design System

The visual system is driven by CSS custom properties defined in `style.css`, including typography scale, spacing, color palette, radii, shadows, and transitions. [file:2]  
The site uses a cool-toned palette with a strong professional blue primary color, light/dark theme support, rounded interface elements, and soft shadows for a modern research identity. [file:2]

### Core design features

- 🎯 CSS variables for scalable styling
- 🌗 Built-in light and dark themes
- 🔵 Professional blue primary accent
- 🧩 Reusable buttons, cards, grids, and section styles
- 📐 Responsive spacing and typography using `clamp()`
- 🪄 Smooth hover and transition behavior

---

## ⚙️ Development

> “First, solve the problem. Then, write the code.” — John Johnson

This project is built as a static front-end website using standard web technologies. [file:3][file:2][file:1]

### Tech stack

- HTML5 for structure and semantic layout [file:3]
- CSS3 for styling, responsiveness, and theming [file:2]
- Vanilla JavaScript for interactivity and UI behavior [file:1]

### Current interactive features

The JavaScript currently supports theme switching, mobile menu toggling, homepage carousel controls, autoplay slider behavior, scroll-triggered member card animation, and animated count-up statistics. [file:1]

### Development approach

- Keep shared styles in `assets/style.css` for consistency across pages. [file:2]
- Keep shared interactive logic in `assets/script.js` so navigation and theme features work site-wide. [file:1]
- Reuse the same header, footer, and container structure across all HTML pages for maintainability. [file:3]

### Local development

To work on the site locally:

1. Clone or download the project files.
2. Open the project folder in VS Code or another editor.
3. Launch `index.html` in a browser.
4. For best workflow, use a local development server such as VS Code Live Server.

Example:

```bash
# If using VS Code Live Server
Right click index.html → Open with Live Server
```

---

## 📄 Homepage Features

The homepage is structured as a narrative experience that introduces the lab, shows active work, and guides visitors deeper into the site. [file:3]

### Main homepage sections

- Hero section with carousel and research messaging [file:3]
- Lab snapshot metrics with animated counters [file:3][file:1]
- Latest news cards [file:3]
- Achievements and publication highlights [file:3]
- Timeline-style explanation of visitor flow [file:3]
- Shared footer with site description [file:3]

---

## 🧠 JavaScript Features

The site uses lightweight JavaScript without external frameworks. [file:1]

### Included behaviors

- 🌗 Theme toggle based on system preference and manual switch [file:1]
- 📱 Mobile navigation menu with expandable state [file:1]
- 🎞️ Hero carousel with previous/next buttons and dots [file:1]
- ⏱️ Auto-rotating slides with reset on user interaction [file:1]
- 🧍 Scroll reveal animation for member cards [file:1]
- 🔢 Count-up number animation for statistics [file:1]

This approach keeps the website fast, readable, and easy to extend. [file:1]

---

## 🛠️ Customization Guide

You can easily adapt this project for another lab, research group, department, or academic initiative.

### Update content

- Change text in each `.html` page
- Replace sample publications, news, and achievements
- Add real team member profiles and contact information
- Update page titles and metadata for search visibility

### Update styling

- Modify CSS variables in `:root` to change colors, spacing, and typography globally. [file:2]
- Add new reusable components using the current card and grid system already defined in the stylesheet. [file:2]

### Add new pages

The website already follows a reusable multi-page structure with shared header/footer patterns, so new pages such as `join_us.html` and `contact_us.html` can be added cleanly using the same layout style. [file:3]

---

## 🚀 Future Improvements

Possible next development steps:

- Add a full publications archive
- Add faculty and student profile detail pages
- Add a contact form with validation
- Add application forms for joining the lab
- Connect news and achievements to a CMS or JSON data source
- Improve accessibility testing across all pages
- Add SEO and Open Graph metadata for every page
- Optimize image loading and media organization

---

## ♿ Accessibility Notes

The current site already includes a skip link, semantic layout regions, labeled navigation, and button-based interactive controls, which provide a solid accessibility baseline. [file:3][file:1]  
Further improvements can include stronger keyboard testing, focus-state auditing, landmark refinement on every page, and contrast review for all future added components. [file:3][file:2]

---

## 🌍 Purpose

> “The important thing is to never stop questioning.” — Albert Einstein

This website is more than a presentation layer.  
It is a digital front door for research culture, collaboration, mentorship, and scholarly visibility.

It is intended to support:

- Research communication
- Academic identity
- Team visibility
- Publication discovery
- Student engagement
- Institutional credibility

---

## 👨‍💻 Developer Notes

For future contributors:

- Keep markup semantic and readable.
- Reuse existing class names where possible.
- Avoid duplicating CSS rules unnecessarily.
- Maintain the visual identity built around the blue-accent research theme. [file:2]
- Test responsiveness after every layout update, especially around the mobile navigation breakpoint. [file:2][file:1]

---

## 📬 Contribution Ideas

Want to improve the site? Here are some great next contributions:

- Add structured data for publications
- Build a reusable member card template
- Add filtering for projects and achievements
- Improve dark theme polish
- Create a downloadable lab brochure page
- Add announcement management through JSON or Markdown

---

## 📜 License

```md
MIT License
```

## 🙌 Acknowledgment

Built with curiosity, clarity, and a commitment to research-driven storytelling.

> “We turn ambitious ideas into rigorous outputs.”